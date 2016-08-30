#### Test 83276082953d005_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-30 22:39:50.672   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-30 22:39:50.672   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-30 22:39:51.692   289   289 E SMD     : DCD OFF
08-30 22:39:51.732  6242  6242 D AndroidRuntime: 
08-30 22:39:51.732  6242  6242 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 22:39:51.732  6242  6242 D AndroidRuntime: CheckJNI is OFF
08-30 22:39:51.742  6242  6242 D AndroidRuntime: readGMSProperty: start
08-30 22:39:51.742  6242  6242 D AndroidRuntime: readGMSProperty: already setted!!
08-30 22:39:51.742  6242  6242 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 22:39:51.742  6242  6242 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 22:39:51.742  6242  6242 D AndroidRuntime: readGMSProperty: end
08-30 22:39:51.742  6242  6242 D AndroidRuntime: addProductProperty: start
08-30 22:39:51.872  6242  6242 E AffinityControl: AffinityControl: registerfunction enter
08-30 22:39:51.892  6242  6242 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 22:39:51.902  1015  1217 E PersonaManagerService: inState():  stateMachine is null !!
08-30 22:39:51.902  1015  1217 I PersonaManagerService: PersonaId don't exist
08-30 22:39:51.902  1015  1217 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-30 22:39:51.912  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-30 22:39:51.922  1015  1217 W ActivityManager: mDVFSHelper.acquire()
08-30 22:39:51.932  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 22:39:51.932  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-30 22:39:51.932  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:39:51.932  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:39:51.932  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:39:51.932  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:39:51.942  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-30 22:39:51.942  1015  1217 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6253 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 22:39:51.942  1015  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-30 22:39:51.942  6253  6253 I libpersona: KNOX_SDCARD checking this for 10155
08-30 22:39:51.942  1015  1217 D InputDispatcher: Focused application set to: xxxx
08-30 22:39:51.942  6253  6253 I libpersona: KNOX_SDCARD not a persona
08-30 22:39:51.942  6253  6253 E Zygote  : MountEmulatedStorage()
08-30 22:39:51.942  6253  6253 E Zygote  : v2
08-30 22:39:51.942  1015  1217 D InputDispatcher: Focus left window: 3160
08-30 22:39:51.952  6242  6242 D AndroidRuntime: Shutting down VM
08-30 22:39:51.952  6253  6253 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:39:51.952  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 22:39:51.952  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-30 22:39:51.952   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-30 22:39:51.962  6253  6253 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:39:51.962  6253  6253 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-30 22:39:51.982  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 22:39:51.982  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-30 22:39:51.982  6253  6253 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:39:51.982  6253  6253 D ActivityThread: Added TimaKeyStore provider
08-30 22:39:51.992  1015  1015 V ActivityManager: Display changed displayId=0
08-30 22:39:51.992  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 22:39:52.012  1015  2973 D PersonaManager: isKioskContainerExistOnDevice
08-30 22:39:52.052   259  1037 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-30 22:39:52.052   259   455 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-30 22:39:52.052  3160  3160 V ActivityThread: updateVisibility : ActivityRecord{98f4750 token=android.os.BinderProxy@266ca9e7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-30 22:39:52.132  6253  6253 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-30 22:39:52.142  6253  6253 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 657-659)
08-30 22:39:52.152  6253  6253 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 22:39:52.152  6242  6242 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 22:39:52.182  6253  6253 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25286a0c}
,08-30 22:39:52.182  6253  6253 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 22:39:52.192  6253  6253 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 22:39:52.212  6253  6253 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 22:39:52.222  6253  6253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:39:52.222  6253  6253 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 22:39:52.242  6253  6253 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 22:39:52.242  6253  6253 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-30 22:39:52.242  6253  6253 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-30 22:39:52.242  6253  6253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 22:39:52.242  6253  6253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 22:39:52.242  6253  6253 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 22:39:52.242  6253  6253 I Adreno-EGL: Local Branch: 
08-30 22:39:52.242  6253  6253 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 22:39:52.242  6253  6253 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 22:39:52.242  6253  6253 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 22:39:52.362  6253  6280 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-30 22:39:52.402  6253  6253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:39:52.412  6253  6253 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 22:39:52.422  6253  6253 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-30 22:39:52.422  6253  6253 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-30 22:39:52.432  6253  6253 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-30 22:39:52.442  6253  6253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:39:52.442  6253  6253 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:39:52.482  6253  6293 D OpenGLRenderer: Render dirty regions requested: true
,08-30 22:39:52.492  1015  4358 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 22:39:52.492  1015  4358 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 22:39:52.492  1015  4358 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 22:39:52.492  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 22:39:52.492  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 22:39:52.502  6253  6253 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-30 22:39:52.502  6253  6253 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-30 22:39:52.512   259   259 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-30 22:39:52.522  1015  1027 D InputDispatcher: Focus entered window: 6253
,08-30 22:39:52.532  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 22:39:52.532  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 22:39:52.532  6253  6253 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 22:39:52.532  6253  6293 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 22:39:52.542  6253  6293 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-30 22:39:52.542  6253  6293 D OpenGLRenderer: Enabling debug mode 0
,08-30 22:39:52.562  6253  6253 V ActivityThread: updateVisibility : ActivityRecord{32f8fe27 token=android.os.BinderProxy@29a1bb41 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-30 22:39:52.592  1015  1133 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 22:39:52.592  1173  1173 D PanelView: There is/are notification(s) 
,08-30 22:39:52.602  1015  6296 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 22:39:52.612  1015  1046 I ActivityManager: Displayed Component not be shown by security: +593ms (total +684ms)
,08-30 22:39:52.612  1015  1046 W ActivityManager: mDVFSHelper.release()
08-30 22:39:52.612  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39fd8112 u0 com.test.thalitest/.MainActivity t128} time:111125
,08-30 22:39:52.622   259  4454 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-30 22:39:52.622   259   455 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-30 22:39:52.622  1769  1769 I SamsungIME: getCurrentCandidateView
,08-30 22:39:52.622  6253  6253 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-30 22:39:52.622  6253  6253 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29a1bb41 time:111139
,08-30 22:39:52.702  6253  6253 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6253
,08-30 22:39:52.702  1769  1769 D SamsungIME: Dismiss ExpandCandiate
,08-30 22:39:52.842  1769  1769 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 22:39:52.852  6253  6253 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 22:39:52.872  1769  1769 I SamsungIME: getDebugLevel  : 0x4f4c
,08-30 22:39:52.892  1769  1769 I SamsungIME: KeybaordView init() : load resources
,08-30 22:39:52.912  1769  1769 I SamsungIME: getCurrentKeyboard
,08-30 22:39:52.912  1769  1769 I SamsungIME: getTextKeyboard
,08-30 22:39:52.932  1769  1769 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 22:39:52.942  6253  6298 D jxcore_app_log: JniHelper::setJavaVM(0xb8dee328), pthread_self() = -1187685216
,08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 22:39:52.952  6253  6298 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a07bf17 added. We now have 1 listener(s)
,08-30 22:39:52.962  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB,
08-30 22:39:52.962  6253  6298 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:39:52.962  6253  6298 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-30 22:39:52.962  6253  6298 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE,
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 22:39:52.972  6253  6298 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d0e2722 added. We now have 1 listener(s)
08-30 22:39:52.972  6253  6298 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:39:52.972  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 22:39:52.972  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 22:39:52.972  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 22:39:52.972  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-30 22:39:52.972  6253  6298 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 22:39:52.982  6253  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-30 22:39:52.982  6253  6298 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-30 22:39:52.992  6253  6298 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:39:52.992  6253  6298 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:39:52.992  6253  6298 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register,
08-30 22:39:52.992  6253  6298 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:39:52.992  6253  6298 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 22:39:52.992  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:39:53.002  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:39:53.032  6253  6253 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 22:39:53.462  1769  6302 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-30 22:39:53.572  6253  6307 W jxcore-log: Initializing JXcore engine
08-30 22:39:53.572  6253  6307 W jxcore-log: JXcore engine is ready
,08-30 22:39:53.622  1907  1907 E audit   : type=1400 msg=audit(1472589593.622:205): avc:  denied  { ioctl } for  pid=6307 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-30 22:39:53.622  1907  1907 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:39:53.622  1907  1907 E audit   : type=1300 msg=audit(1472589593.622:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eb008f8 items=0 ppid=307 ppcomm=main pid=6307 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,08-30 22:39:53.622  1907  1907 E audit   : type=1320 msg=audit(1472589593.622:205): 
,08-30 22:39:53.632  6253  6307 W jxcore-log: Starting JXcore engine
,08-30 22:39:53.742  6253  6307 W jxcore-log: Platform android
08-30 22:39:53.742  6253  6307 W jxcore-log: 
08-30 22:39:53.742  6253  6307 W jxcore-log: Process ARCH arm
08-30 22:39:53.742  6253  6307 W jxcore-log: 
,08-30 22:39:53.952  6253  6307 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 22:39:53.952  6253  6307 I jxcore-log: 
08-30 22:39:53.952  6253  6307 W jxcore-log: JXcore engine is started
,08-30 22:39:53.952  6253  6298 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 22:39:53.952  6253  6253 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 22:39:54.692   289   289 E SMD     : DCD OFF
,08-30 22:39:55.672   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 22:39:56.622  5454  5454 D FactoryTest: Not factory mode
,08-30 22:39:56.622  5454  5454 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-30 22:39:56.622  5454  5454 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-30 22:39:56.632  5454  5454 D MTPRx   : still no open session command from host, so toast
,08-30 22:39:56.632  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-30 22:39:56.632  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-30 22:39:56.632  5454  5454 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115142
,08-30 22:39:56.632  1015  1027 E PersonaManagerService: inState():  stateMachine is null !!
,08-30 22:39:56.632  1015  1027 I PersonaManagerService: PersonaId don't exist
08-30 22:39:56.632  1015  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-30 22:39:56.632  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 22:39:56.632  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:39:56.632  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:39:56.632  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-30 22:39:56.642  1015  1027 W ActivityManager: mDVFSHelper.acquire(),
,08-30 22:39:56.652  1015  1027 D PersonaManager: isKioskContainerExistOnDevice,
,08-30 22:39:56.662  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 22:39:56.662  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-30 22:39:56.662  1015  1027 D InputDispatcher: Focused application set to: xxxx
,08-30 22:39:56.662  1015  1027 D InputDispatcher: Focus left window: 6253
,08-30 22:39:56.672  5454  5454 E MTPRx   : started activity for popup
,08-30 22:39:56.672  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 22:39:56.672  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 22:39:56.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:39:56.692  5454  5454 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:39:56.712  5454  5454 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-30 22:39:56.712  1015  2973 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-30 22:39:56.712  1015  2973 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 22:39:56.712  1015  2973 D InputDispatcher: Focused application set to: xxxx
,08-30 22:39:56.712  1015  2973 D InputDispatcher: Focus entered window: 6253
,08-30 22:39:56.712  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 22:39:56.722  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 22:39:56.722  1015  4152 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 22:39:56.722  1015  4152 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1b666bed attribute=null, token = android.os.BinderProxy@16d3297d
,08-30 22:39:56.752  5454  5454 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-30 22:39:56.762  5454  5454 D PhoneWindow: *FMB* installDecor mIsFloating : true,
08-30 22:39:56.762  5454  5454 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-30 22:39:56.782  6253  6253 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 22:39:56.782  6253  6253 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-30 22:39:56.782  6253  6253 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-30 22:39:56.782  6253  6253 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-30 22:39:56.782  1015  1133 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-30 22:39:56.782  1015  1133 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-30 22:39:56.782  1015  1133 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 22:39:56.782  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-30 22:39:56.782  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 22:39:56.802  6253  6253 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 22:39:56.802  6253  6253 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 22:39:56.802  6253  6253 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ba06e3c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9bf42a4, 16908290=android.view.AbsSavedState$1@9bf42a4}, android:focusedViewId=100}]}]
08-30 22:39:56.802  6253  6253 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 22:39:56.802  6253  6253 V ActivityThread: updateVisibility : ActivityRecord{32f8fe27 token=android.os.BinderProxy@29a1bb41 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-30 22:39:56.802  6253  6253 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 22:39:56.802  6253  6253 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-30 22:39:56.802  6253  6253 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@29a1bb41 time:115318
,08-30 22:39:56.812  1015  1382 D PersonaManager: isKioskContainerExistOnDevice
,08-30 22:39:57.532  1015  3002 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 22:39:57.532  1015  3002 D BatteryService: level:63, scale:100, status:2, health:2, present:true, voltage: 3917, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 22:39:57.532  1015  3002 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 22:39:57.532  1015  3002 D BatteryService: stay LED for charging
08-30 22:39:57.542  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 22:39:57.542  1015  1015 I MotionRecognitionService: Plugged
,08-30 22:39:57.542  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 22:39:57.542  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 22:39:57.542  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 22:39:57.542  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 22:39:57.542  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 63
,08-30 22:39:57.562  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 22:39:57.562  2649  2760 D HeadsetStateMachine: Disconnected process message: 10
,08-30 22:39:57.572  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:39:57.572  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:39:57.572  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:39:57.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:39:57.692   289   289 E SMD     : DCD OFF,
,08-30 22:39:58.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 22:39:58.762  1015  2770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-30 22:39:59.642  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-30 22:39:59.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-30 22:39:59.802  1015  2735 D SSRM:n  : SIOP:: AP = 320
,08-30 22:39:59.992  1015  1094 V AlarmManager: waitForAlarm result :8
,08-30 22:40:00.682   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-30 22:40:00.692   289   289 E SMD     : DCD OFF
,08-30 22:40:01.492  1015  1094 V AlarmManager: waitForAlarm result :4
,08-30 22:40:01.492  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-30 22:40:01.502  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-30 22:40:01.502  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-30 22:40:01.512  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-30 22:40:01.512  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
08-30 22:40:01.512  1173  1173 D KeyguardUpdateMonitor: handleTimeUpdate
,08-30 22:40:01.522  1173  1173 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-30 22:40:01.522  1173  1173 D SecKeyguardClockView: HomeTimezone(): 1
,08-30 22:40:01.532  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 22:40:01.532  1173  1173 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-30 22:40:01.532  1173  1173 I KeyguardEffectViewController: *** don't update sliding image ***
,08-30 22:40:01.542  1932  1932 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 22:40:01.722  1015  1488 I art     : Explicit concurrent mark sweep GC freed 66374(3MB) AllocSpace objects, 29(921KB) LOS objects, 33% free, 28MB/42MB, paused 2.500ms total 164.202ms
,08-30 22:40:01.732  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 22:40:01.732  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 22:40:01.732  1173  1173 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 22:40:01.742  1015  4358 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:01.742  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-30 22:40:01.742  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:01.742  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:01.742  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:01.742  3802  3802 D ConnectivityManager: CallingUid : 10012, CallingPid : 3802
,08-30 22:40:01.752  1015  1028 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-30 22:40:01.752  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-30 22:40:01.752  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-30 22:40:01.752  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-30 22:40:01.752  3802  6316 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 22:40:01.762  1173  1173 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-30 22:40:01.822  3802  6317 W DriveInitializer: Background init thread started
,08-30 22:40:01.842   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-30 22:40:01.842   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:01.842  3802  6317 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-30 22:40:01.902  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:01.902  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-30 22:40:01.902  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:01.902  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:01.902  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:01.932  1015  4151 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-30 22:40:01.932  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-30 22:40:01.942  3802  6317 W DriveInitializer: Background init thread ended
,08-30 22:40:01.942  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:01.942  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-30 22:40:01.942  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:01.942  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:01.942  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:01.962  3802  6325 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 22:40:01.962  3802  6325 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 22:40:01.982  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-30 22:40:02.002  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 22:40:02.042  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.042  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.042  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.112  1015  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:02.112  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-30 22:40:02.112  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.112  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.112  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.142  1015  1503 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:02.142  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-30 22:40:02.142  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.142  1015  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.142  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.202  1015  1382 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.202  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.202  1015  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.202  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.252  1015  4152 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.252  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.252  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.252  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.352  1932  6328 I art     : Explicit concurrent mark sweep GC freed 70719(4MB) AllocSpace objects, 18(528KB) LOS objects, 39% free, 13MB/23MB, paused 1.454ms total 78.400ms
,08-30 22:40:02.372  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.382  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.382  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.382  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.392  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 22:40:02.392  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:02.392  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:02.392  1015  1489 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:02.402  6330  6330 E Zygote  : MountEmulatedStorage()
08-30 22:40:02.402  6330  6330 I libpersona: KNOX_SDCARD checking this for 10012
08-30 22:40:02.402  6330  6330 E Zygote  : v2
08-30 22:40:02.402  6330  6330 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:02.402  1015  1489 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6330 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-30 22:40:02.402  6330  6330 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 22:40:02.412  6330  6330 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:02.412  6330  6330 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-30 22:40:02.432  6330  6330 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:02.442  6330  6330 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:02.452  6330  6330 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-30 22:40:02.452  6330  6330 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 22:40:02.492  6330  6330 I MultiDex: VM with version 2.1.0 has multidex support
08-30 22:40:02.492  6330  6330 I MultiDex: install
08-30 22:40:02.492  6330  6330 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 22:40:02.532  6330  6330 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 22:40:02.592  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-30 22:40:02.592  6330  6330 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-30 22:40:02.592  6330  6330 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31f9ee21: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 22:40:02.602  6330  6330 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 22:40:02.602  1015  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.602  1015  1217 W ActivityManager: userId = 0, bbcId = -10000,
08-30 22:40:02.602  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.602  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.612  1015  4358 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.612  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:02.612  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.612  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.622  6330  6330 D ChimeraCfgMgr: Reading stored module config
,08-30 22:40:02.642  1932  1932 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b3d2cbcb-cd4f-4aaa-8e5f-b9b89a76635d
,08-30 22:40:02.682  1015  4152 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 22:40:02.682  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 22:40:02.692  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.692  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.692  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.692  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 22:40:02.692  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 22:40:02.712  1015  4152 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:02.712  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:02.712  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:02.712  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:02.722  6330  6349 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 22:40:02.732  6330  6330 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 22:40:02.732  6330  6330 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 22:40:02.832   284   284 D WVCdm   : Instantiating CDM.
,08-30 22:40:02.832   284   705 I WVCdm   : CdmEngine::OpenSession
,08-30 22:40:02.832   284   705 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-30 22:40:02.852   284   705 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-30 22:40:02.872   284   705 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-30 22:40:02.872   284   705 D DrmWidevineDash: Service_Initialize: starts!
08-30 22:40:02.872   284   705 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-30 22:40:02.872   284   705 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 22:40:02.872   284   705 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-30 22:40:02.872   284   705 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 22:40:02.872   284   705 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 22:40:02.872   284   705 D QSEECOMAPI: : App is not loaded in QSEE
08-30 22:40:02.872   284   705 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-30 22:40:02.872   284   705 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-30 22:40:02.872   284   705 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-30 22:40:02.872   284   705 D QSEECOMAPI: : App is not loaded in QSEE
,08-30 22:40:02.892   284   705 D QSEECOMAPI: : Loaded image: APP id = 12
,08-30 22:40:02.902   284   705 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-30 22:40:02.902   284   705 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-30 22:40:02.902   284   705 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-30 22:40:02.902   284   705 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1787000
08-30 22:40:02.902   284   705 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1787000
08-30 22:40:02.902   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.902   433   443 D DrmLibTime: got the req here! ret=0
08-30 22:40:02.902   433   443 D DrmLibTime: command id, time_cmd_id = 770
08-30 22:40:02.902   433   443 D DrmLibTime: time_getutcsec starts!
08-30 22:40:02.902   433   443 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-30 22:40:02.902   433   443 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-30 22:40:02.902   433   443 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-30 22:40:02.902   433   443 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
08-30 22:40:02.902   433   443 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-30 22:40:02.902   433   443 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-30 22:40:02.902   433   443 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,08-30 22:40:02.902   433   443 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-30 22:40:02.902   328   435 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-30 22:40:02.912   328  6354 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-30 22:40:02.912   328  6354 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-30 22:40:02.912   328  6354 D QC-time-services: offset is: 0 for base: 0
08-30 22:40:02.912   433   443 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-30 22:40:02.912   433   443 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-30 22:40:02.912   433   443 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472589602
08-30 22:40:02.912   433   443 D DrmLibTime: time_getutcsec returns 0, sec = 1472589602; nsec = 0
08-30 22:40:02.912   433   443 D DrmLibTime: time_getutcsec finished! 
08-30 22:40:02.912   433   443 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-30 22:40:02.912   433   443 D DrmLibTime: before calling ioctl to read the next time_cmd
08-30 22:40:02.912   328   435 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection,
08-30 22:40:02.912   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 22:40:02.922   284   705 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-30 22:40:02.922   284   705 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 22:40:02.922   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.922   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.922   284   705 D DrmWidevineDash: hlos api version =  9
08-30 22:40:02.922   284   705 D DrmWidevineDash: tz api version =  9
08-30 22:40:02.922   284   705 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
,08-30 22:40:02.922   284   705 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-30 22:40:02.932   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-30 22:40:02.942   284   705 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb193b960
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb79df4f0, dataLength=8
08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-30 22:40:02.942   284   705 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb79ace20, wrapped_rsa_key_length=1280
,08-30 22:40:02.942   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.952   284   705 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 22:40:02.952   284   705 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-30 22:40:02.952   284   705 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 22:40:02.952   284   812 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 22:40:02.952   284   812 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 22:40:02.952   284   812 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 22:40:02.952   284   812 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb79d61f0, idLength=0xb1668730
08-30 22:40:02.952   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.962  1648  4357 I art     : Explicit concurrent mark sweep GC freed 1373(46KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 798us total 43.032ms
,08-30 22:40:02.972  6330  6340 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-30 22:40:02.982  6330  6340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 22:40:02.982  6330  6340 I System.out: (HTTPLog)-Static: isShipBuild true
08-30 22:40:02.982  6330  6340 I System.out: (HTTPLog)-Thread-1058-4781098: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-30 22:40:02.982  6330  6340 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1668746, maximum = 0xb1668747
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: hlos api version =  9
08-30 22:40:02.982   284   812 D DrmWidevineDash: tz api version =  9
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb16687b4
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-30 22:40:02.982   284   812 D WVCdm   : PrepareKeyRequest: nonce=1477278044
08-30 22:40:02.982   284   812 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb79b1f98
08-30 22:40:02.982   284   812 D DrmWidevineDash: message_length=1599, signature=0xb79de8e0, signature_length=0xb1668714
08-30 22:40:02.982   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:02.982   279   963 D EnterpriseController: uids 10012
08-30 22:40:02.982   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:02.982   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-30 22:40:03.002  1932  2105 W GCoreFlp: No location to return for getLastLocation()
,08-30 22:40:03.032  6330  6340 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:03.042  6330  6340 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6330, getuid(): 10012
08-30 22:40:03.042  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 22:40:03.042  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:03.042  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:03.042  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.052  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.052  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.052  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.052  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.052  1015  4358 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.062  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.062  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.062  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.072  3802  6326 D UdcContextInitService: registered all accounts: true
,08-30 22:40:03.072  1932  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 22:40:03.092  1932  2129 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 22:40:03.132   284   812 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:03.132   284   812 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-30 22:40:03.152   284   284 I WVCdm   : CdmEngine::CloseSession
08-30 22:40:03.152   284   284 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-30 22:40:03.152   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:03.152   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-30 22:40:03.152   284   284 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-30 22:40:03.152   284   284 I WVCdm   : L3 Terminate.
08-30 22:40:03.152   284   284 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-30 22:40:03.152   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-30 22:40:03.152   284   284 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-30 22:40:03.152   284   284 D DrmWidevineDash: Service_Uninitialize: starts!
08-30 22:40:03.152   284   284 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-30 22:40:03.152   284   284 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
,08-30 22:40:03.152   284   284 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-30 22:40:03.152   284   284 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-30 22:40:03.222  1015  4151 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:03.222  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-30 22:40:03.222  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.222  1015  4151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.222  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.272  1015  1503 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-30 22:40:03.272  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 22:40:03.272  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.272  1015  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.272  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.312  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.322  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.322  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.322  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.342  1015  4151 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.342  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.342  1015  4151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.342  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.372  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-30 22:40:03.372  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 22:40:03.382  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:03.382  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.382  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.382  1932  2129 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:03.382   279   963 D EnterpriseController: uids 10012
08-30 22:40:03.382   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:03.382   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 22:40:03.392  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.392  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.392  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.392  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.392  1932  6363 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 22:40:03.392  1932  6361 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 22:40:03.392  1015  1476 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.392  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.392  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.392  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.402  6330  6340 I qtaguid : Untagging socket 30
,08-30 22:40:03.412  1932  2129 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:03.412  1932  2129 I qtaguid : Tagging socket 72 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:03.422  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.422  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.422  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.422  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 22:40:03.422  1932  6363 E CommitToConfigurationOperation: Malformed snapshot token (size): ,
08-30 22:40:03.422  1932  6361 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 22:40:03.422  1015  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.422  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:03.422  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.422  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.442  1932  2129 I qtaguid : Tagging socket 75 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:03.452  1015  2973 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:03.452  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:03.452  1015  2973 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:03.452  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:03.452  1932  6363 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 22:40:03.452  1932  6361 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-30 22:40:03.452  1932  6361 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-30 22:40:03.462  1932  6361 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 22:40:03.522  1015  1503 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 22:40:03.552  1932  6361 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:03.552   279   963 D EnterpriseController: uids 10012
08-30 22:40:03.552   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:03.552   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 22:40:03.562  1932  6361 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:03.562  1932  6361 I qtaguid : Tagging socket 77 with tag fffff33b00000000{4294964027,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:03.602  1932  6361 I qtaguid : Tagging socket 80 with tag fffff33b00000000{4294964027,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:03.702   289   289 E SMD     : DCD OFF
,08-30 22:40:03.882  1015  1382 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 22:40:03.882  1932  6361 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:03.892  1932  6361 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:04.032  1015  4151 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 22:40:04.032  1932  6361 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:04.042  1932  6361 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:04.042  6370  6370 I dex2oat : ----------------------------------------------------
08-30 22:40:04.042  6370  6370 I dex2oat : <SS>: S T A R T I N G . . .
08-30 22:40:04.042  6370  6370 I dex2oat : <SS>: Zip is absent. Canceled.
08-30 22:40:04.042  6370  6370 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 22:40:04.082  6370  6370 I dex2oat : dex2oat took 32.067ms (threads: 4)
,08-30 22:40:04.092  6330  6340 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 22:40:04.092  6330  6340 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 22:40:04.092  6330  6340 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 22:40:04.092  6330  6340 I Adreno-EGL: Local Branch: 
08-30 22:40:04.092  6330  6340 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 22:40:04.092  6330  6340 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 22:40:04.092  6330  6340 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 22:40:04.172  6330  6340 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 22:40:04.172  6330  6340 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 22:40:04.172  6330  6340 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 22:40:04.172  6330  6340 I Adreno-EGL: Local Branch: 
08-30 22:40:04.172  6330  6340 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 22:40:04.172  6330  6340 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 22:40:04.172  6330  6340 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 22:40:04.182  1015  1476 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-30 22:40:04.192  1932  6361 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 22:40:04.192  1932  6361 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:04.272  6330  6340 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 22:40:04.272  6330  6340 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 22:40:04.272  6330  6340 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 22:40:04.272  6330  6340 I Adreno-EGL: Local Branch: 
08-30 22:40:04.272  6330  6340 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 22:40:04.272  6330  6340 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 22:40:04.272  6330  6340 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 22:40:04.322  1015  1027 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 22:40:04.342  1932  6361 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:04.342  1932  6361 I qtaguid : Tagging socket 77 with tag 1106583100000000{285628465,0} for uid -1, pid: 1932, getuid(): 10012
,08-30 22:40:04.392  1932  6328 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:04.402  1932  6328 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:04.402  1932  6328 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:04.422  1932  6328 I qtaguid : Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:04.562  1932  2129 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 22:40:04.572  1932  2129 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-30 22:40:04.572  1932  2129 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 22:40:03.186+0200, stopTime=2016-08-30 22:40:04.581+0200, duration=1395ms
,08-30 22:40:04.582  1932  6377 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:04.582   279   963 D EnterpriseController: uids 10012
08-30 22:40:04.582   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:04.582   279   963 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-30 22:40:04.592  1932  6377 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:04.592  1932  6377 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:04.632  1932  6377 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:04.642  1932  6328 I art     : Explicit concurrent mark sweep GC freed 56632(3MB) AllocSpace objects, 70(3MB) LOS objects, 39% free, 14MB/24MB, paused 2.351ms total 99.309ms
,08-30 22:40:04.652  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 22:40:04.852  1932  6377 I qtaguid : Untagging socket 66
,08-30 22:40:04.852  1932  2129 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 22:40:05.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:06.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:06.682  1932  6378 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:06.682  1932  6378 I qtaguid : Tagging socket 66 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1932, getuid(): 10012
,08-30 22:40:06.702   289   289 E SMD     : DCD OFF
,08-30 22:40:06.832  1932  6378 I qtaguid : Untagging socket 66
,08-30 22:40:06.842  1932  2129 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 22:40:06.862  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-30 22:40:07.042  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 22:40:07.042  6253  6307 I jxcore-log: 
,08-30 22:40:07.042  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 22:40:07.042  6253  6307 I jxcore-log: 
,08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:07.052  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:40:07.052  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:40:07.052  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 22:40:07.052  6253  6307 I jxcore-log: 
,08-30 22:40:07.062  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 22:40:07.062  6253  6307 I jxcore-log: 
,08-30 22:40:07.592  1015  4152 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 22:40:07.602  1015  4152 D BatteryService: level:63, scale:100, status:2, health:2, present:true, voltage: 3911, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 22:40:07.602  1015  4152 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-30 22:40:07.602  1015  4152 D BatteryService: stay LED for charging
08-30 22:40:07.602  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 22:40:07.602  1015  1015 I MotionRecognitionService: Plugged
,08-30 22:40:07.602  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 22:40:07.612  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-30 22:40:07.612  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 22:40:07.612  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 22:40:07.612  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 63
,08-30 22:40:07.622  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 22:40:07.622  2649  2760 D HeadsetStateMachine: Disconnected process message: 10
,08-30 22:40:07.632  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:07.632  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:07.632  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:07.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:07.712  6253  6307 I jxcore-log: Unit Test app is loaded,
08-30 22:40:07.712  6253  6307 I jxcore-log: 
,08-30 22:40:07.722  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:07.722  6253  6307 I jxcore-log: 
,08-30 22:40:07.722  6253  6253 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 22:40:07.732  6253  6307 D executeNativeTests: Running unit tests
,08-30 22:40:07.812  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:07.812  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d added. We now have 2 listener(s)
,08-30 22:40:07.822  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:07.822  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:07.822  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:07.822  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:07.822  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 added. We now have 2 listener(s)
08-30 22:40:07.822  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:07.822  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:40:07.822  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:07.822  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:40:07.822  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:07.822  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:07.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:07.832  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:40:07.832  6253  6307 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-30 22:40:07.832  6253  6307 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 22:40:07.832  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:40:07.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:07.832  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:07.832  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:07.832  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:07.832  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:07.832  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.832  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:07.832  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d removed from the list
08-30 22:40:07.832  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.832  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 removed from the list
08-30 22:40:07.832  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:07.832  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.832  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.832  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.842  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-30 22:40:07.842  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:07.842  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:07.842  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:07.842  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.842  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.842  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:07.842  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.842  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:07.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.842  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 22:40:07.842  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 22:40:07.842  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:07.842  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:07.842  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:07.852  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.852  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.852  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.852  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.852  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:07.852  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.852  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.852  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.852  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.852  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.852  6253  6307 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:07.852  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 22:40:07.852  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:40:07.852  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:07.852  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:07.852  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:07.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:40:07.862  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:07.862  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-30 22:40:07.862  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:07.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-30 22:40:07.872  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-30 22:40:07.872  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-30 22:40:07.872  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-30 22:40:07.872  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 22:40:07.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 22:40:07.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-30 22:40:07.892  2649  2994 D BtGatt.GattService: registerClient() - UUID=1ef65d06-cda0-45dd-9bc6-164c0b0c71d6
,08-30 22:40:07.942  2649  2734 D BtGatt.GattService: onClientRegistered() - UUID=1ef65d06-cda0-45dd-9bc6-164c0b0c71d6, clientIf=6
,08-30 22:40:07.942  6253  6262 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 22:40:07.942  2649  2662 D BtGatt.GattService: start scan with filters
,08-30 22:40:07.942  2649  2758 D BtGatt.ScanManager: handling starting scan
,08-30 22:40:07.942  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 22:40:07.942  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 22:40:07.952  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 22:40:07.952  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 22:40:07.952  2649  2758 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:07.952  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:07.952  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 22:40:07.952  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 22:40:07.962  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:07.962  2649  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 22:40:07.962  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:07.962  2649  2758 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:07.962  2649  2758 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 22:40:07.962  2649  2758 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-30 22:40:07.972  6253  6307 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 22:40:07.972  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:40:07.972  6253  6307 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 22:40:07.972  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 22:40:07.972  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:07.972  2649  2758 D BtGatt.ScanManager: Starting BLE batch scan
,08-30 22:40:07.972  2649  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 22:40:07.982  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:07.982  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 22:40:07.982  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:40:07.982  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:40:07.982  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 22:40:07.982  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:07.982  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:07.982  2649  2994 D BtGatt.GattService: stopScan() - queue size =1,
,08-30 22:40:07.982  2649  2659 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 22:40:07.982  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 22:40:07.982  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 22:40:07.992  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:07.992  2649  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 22:40:07.992  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-30 22:40:07.992  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:07.992  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:07.992  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-30 22:40:07.992  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:07.992  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:07.992  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:07.992  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 22:40:07.992  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:07.992  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:07.992  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 22:40:07.992  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:08.002  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 22:40:08.002  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:08.002  6253  6307 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 22:40:08.002  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:08.012  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:40:08.012  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.012  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:08.012  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:08.012  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:40:08.012  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:08.012  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:08.012  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 22:40:08.022  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.022  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 22:40:08.032  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 22:40:08.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:40:08.042  2649  2758 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 88
,08-30 22:40:08.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 22:40:08.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 22:40:08.042  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 22:40:08.042  2649  2662 D BtGatt.GattService: registerClient() - UUID=858c5d34-43e0-4b17-b877-763cd5bb2b26
,08-30 22:40:08.052  2649  2758 D BtGatt.ScanManager: filter size is 1
,08-30 22:40:08.052  2649  2758 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 22:40:08.062  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-30 22:40:08.062  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.062  2649  2758 D BtGatt.ScanManager: stopping BLe Batch
,08-30 22:40:08.072  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 22:40:08.072  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.072  2649  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 22:40:08.082  2649  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 22:40:08.082  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.082  2649  2734 D BtGatt.GattService: onClientRegistered() - UUID=858c5d34-43e0-4b17-b877-763cd5bb2b26, clientIf=6
,08-30 22:40:08.092  6253  6261 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 22:40:08.092  2649  2994 D BtGatt.GattService: start scan with filters
,08-30 22:40:08.092  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 22:40:08.092  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 22:40:08.092  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 22:40:08.092  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 22:40:08.092  2649  2758 D BtGatt.ScanManager: handling starting scan
,08-30 22:40:08.092  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:08.102  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 22:40:08.102  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:08.102  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:08.102  6253  6307 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 22:40:08.102  2649  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 22:40:08.102  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:08.102  2649  2758 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:08.102  2649  2758 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 22:40:08.102  2649  2758 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 22:40:08.112  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-30 22:40:08.112  6253  6307 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 22:40:08.112  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.112  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-30 22:40:08.112  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.112  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 22:40:08.112  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-30 22:40:08.112  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 22:40:08.112  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:08.112  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-30 22:40:08.112  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:08.112  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:08.112  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-30 22:40:08.112  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:08.112  2649  2758 D BtGatt.ScanManager: Starting BLE batch scan
08-30 22:40:08.112  2649  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-30 22:40:08.122  2649  2659 D BtGatt.GattService: stopScan() - queue size =1
,08-30 22:40:08.122  2649  2662 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 22:40:08.122  2649  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 22:40:08.122  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.122  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 22:40:08.122  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 22:40:08.122  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-30 22:40:08.122  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 22:40:08.122  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:08.132  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 22:40:08.132  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.132  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:08.132  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 22:40:08.132  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:40:08.132  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:40:08.132  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:08.142  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:08.142  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.142  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.142  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:08.142  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:08.142  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.142  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.142  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:08.142  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.142  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.142  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.142  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.142  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.142  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.142  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.142  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.142  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.142  6253  6307 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-30 22:40:08.152  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:08.152  2649  2758 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 89
,08-30 22:40:08.152  2649  2758 D BtGatt.ScanManager: filter size is 1
08-30 22:40:08.152  2649  2758 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:08.152  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:40:08.152  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:40:08.152  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 22:40:08.162  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:08.162  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:40:08.162  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:08.162  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:08.162  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:40:08.162  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 22:40:08.162  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.162  2649  2758 D BtGatt.ScanManager: stopping BLe Batch
,08-30 22:40:08.162  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.162  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.172  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 22:40:08.172  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 22:40:08.172  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.172  2649  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 22:40:08.172  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 22:40:08.172  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:40:08.182  2649  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 22:40:08.182  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.182  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 22:40:08.182  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-30 22:40:08.182  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 22:40:08.182  2649  2659 D BtGatt.GattService: registerClient() - UUID=7b331faf-77d8-4ffa-9943-c53ac39e904c
,08-30 22:40:08.232  2649  2734 D BtGatt.GattService: onClientRegistered() - UUID=7b331faf-77d8-4ffa-9943-c53ac39e904c, clientIf=6
,08-30 22:40:08.232  6253  6261 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-30 22:40:08.232  2649  2994 D BtGatt.GattService: start scan with filters
,08-30 22:40:08.232  2649  2758 D BtGatt.ScanManager: handling starting scan
,08-30 22:40:08.232  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 22:40:08.232  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-30 22:40:08.232  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 22:40:08.232  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 22:40:08.242  2649  2734 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 22:40:08.242  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.242  2649  2758 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:08.242  2649  2758 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-30 22:40:08.242  2649  2758 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-30 22:40:08.242  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:08.242  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:08.242  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 22:40:08.252  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:08.252  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 22:40:08.252  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.252  2649  2758 D BtGatt.ScanManager: Starting BLE batch scan
08-30 22:40:08.252  2649  2758 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 22:40:08.252  6253  6307 I io.jxcore.node.ConnectionHelper: start: OK
,08-30 22:40:08.252  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.252  6253  6307 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 22:40:08.252  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-30 22:40:08.262  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 22:40:08.262  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:08.262  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 22:40:08.262  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:40:08.262  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-30 22:40:08.262  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:08.262  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-30 22:40:08.262  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:08.262  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:08.262  2649  2734 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-30 22:40:08.262  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.262  2649  2662 D BtGatt.GattService: stopScan() - queue size =1
,08-30 22:40:08.262  2649  2659 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 22:40:08.272  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 22:40:08.272  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-30 22:40:08.272  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 22:40:08.272  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-30 22:40:08.272  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:08.272  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-30 22:40:08.272  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:40:08.282  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:08.282  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 22:40:08.282  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 22:40:08.282  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:08.282  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.282  6253  6307 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-30 22:40:08.282  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.282  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.282  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.282  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:08.282  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
,08-30 22:40:08.282  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.282  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.282  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.282  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.282  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.292  2649  2758 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 90
,08-30 22:40:08.292  6253  6307 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-30 22:40:08.292  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.292  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.292  2649  2758 D BtGatt.ScanManager: filter size is 1
,08-30 22:40:08.292  2649  2758 D BtGatt.ScanManager: delete FilterIndex - 5
,08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.292  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 22:40:08.292  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.292  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.292  6253  6307 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-30 22:40:08.292  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.292  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.292  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.292  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.292  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.292  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.292  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.302  6253  6307 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-30 22:40:08.302  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.302  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.302  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.302  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.302  2649  2734 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
,08-30 22:40:08.302  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.302  2649  2758 D BtGatt.ScanManager: stopping BLe Batch
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-30 22:40:08.302  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 22:40:08.302  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-30 22:40:08.302  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-30 22:40:08.302  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.302  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.302  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.302  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.302  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.302  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-30 22:40:08.302  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.302  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.312  2649  2734 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-30 22:40:08.312  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:08.312  2649  2758 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-30 22:40:08.312  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:40:08.312  6253  6307 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-30 22:40:08.312  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:40:08.312  6253  6307 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:20,10:2010:2010:2010]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-30 22:40:08.312  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-30 22:40:08.312  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-30 22:40:08.312  6253  6307 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:40:08.312  6253  6307 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-30 22:40:08.312  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:40:08.312  6253  6307 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:40:08.312  6253  6307 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-30 22:40:08.312  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:40:08.312  6253  6307 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-30 22:40:08.312  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-30 22:40:08.312  2649  2734 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 22:40:08.312  2649  2734 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
,08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1,
08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-30 22:40:08.322  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-30 22:40:08.322  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-30 22:40:08.322  6253  6307 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-30 22:40:08.322  6253  6307 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-30 22:40:08.322  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.322  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.322  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.322  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.322  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.322  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-30 22:40:08.322  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.322  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.322  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.322  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.322  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.322  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.322  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:08.322  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6390 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
,08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.332  6253  6307 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-30 22:40:08.332  6253  6389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
08-30 22:40:08.332  6253  6389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
,08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-30 22:40:08.332  6253  6307 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 22:40:08.332  6253  6307 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-30 22:40:08.332  6253  6307 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 22:40:08.332  6253  6307 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
,08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.332  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.332  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.332  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.332  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.332  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.332  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.332  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
,08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:40:08.342  6253  6253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.342  6253  6253 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.342  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.342  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.342  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
,08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.342  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6391 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-30 22:40:08.342  6253  6391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.342  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.342  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-30 22:40:08.342  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:08.342  6253  6253 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-30 22:40:08.342  6253  6307 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-30 22:40:08.342  6253  6307 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-30 22:40:08.342  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-30 22:40:08.342  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.342  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.342  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.342  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.342  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.342  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.342  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.342  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.352  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.352  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.352  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list,
08-30 22:40:08.352  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.352  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:08.352  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:08.352  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e058e7d not in the list
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.352  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:08.352  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:08.352  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:08.352  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b75f172 not in the list
08-30 22:40:08.352  6253  6307 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-30 22:40:08.352  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-30 22:40:08.352  6253  6307 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-30 22:40:08.352  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-30 22:40:08.352  6253  6307 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-30 22:40:08.352  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-30 22:40:08.362  6253  6307 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 22:40:08.362  6253  6307 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-30 22:40:08.362  6253  6307 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-30 22:40:08.362  6253  6307 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-30 22:40:08.362  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:08.362  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@438e304 added. We now have 2 listener(s)
,08-30 22:40:08.362  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:08.362  6253  6307 D BluetoothAdapter: enable()
,08-30 22:40:08.362  6253  6307 D BluetoothAdapter: enable(): BT is already enabled..!
,08-30 22:40:08.362  1015  1382 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-30 22:40:08.362  1015  1382 D WifiService: setWifiEnabled: true pid=6253, uid=10155
08-30 22:40:08.362  1015  1382 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:08.362  1015  1382 W ActivityManager: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 22:40:08.362  1015  1382 D SecContentProvider2: mCursor = null
08-30 22:40:08.362  1015  1382 W WifiService: Failed getting userId using ActivityManagerNative
08-30 22:40:08.362  1015  1382 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 22:40:08.362  1015  1382 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 22:40:08.362  1015  1382 W WifiService: 	,at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 22:40:08.362  1015  1382 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 22:40:08.362  1015  1382 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 22:40:08.362  1015  1382 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-30 22:40:08.362  1015  1382 D SettingsProvider: name = wifi_on
08-30 22:40:08.362  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:08.362  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a7c10ed added. We now have 3 listener(s)
08-30 22:40:08.362  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:08.372  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:08.372  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38499b22 added. We now have 4 listener(s)
08-30 22:40:08.372  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:08.372  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:08.372  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e799b3 added. We now have 5 listener(s)
08-30 22:40:08.372  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:08.372  1015  2973 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 22:40:08.372  1015  2973 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:08.372  1015  2973 D SecContentProvider2: mCursor = null
,08-30 22:40:08.372  1015  2973 D WifiService: setWifiEnabled: false pid=6253, uid=10155
08-30 22:40:08.372  1015  2973 D SettingsProvider: name = wifi_on
,08-30 22:40:08.382  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-30 22:40:08.382  6253  6307 D BluetoothAdapter: disable()
08-30 22:40:08.382  2090  2090 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 22:40:08.382  2090  2090 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-30 22:40:08.382  2090  2090 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 22:40:08.382  1015  4151 D SettingsProvider: name = bluetooth_on
,08-30 22:40:08.382  2090  2090 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 22:40:08.392  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:08.392  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:08.392  2649  2731 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-30 22:40:08.392  2649  2731 D BluetoothAdapterProperties: Setting state to 13
08-30 22:40:08.392  2649  2731 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 22:40:08.392  2649  2731 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:08.392  2649  2731 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 22:40:08.392  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:08.392  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.402  1015  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-30 22:40:08.402  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.402  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.402  1015  1125 E WifiNative-wlan0: do suspend true
08-30 22:40:08.402  2649  2649 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-30 22:40:08.402  2649  2731 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:08.402  2649  2731 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 22:40:08.402  2649  2731 D BluetoothAdapterService: terminating service from this receiver
08-30 22:40:08.402  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1939b41e, channel: 19, state: LISTENING
08-30 22:40:08.402  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1939b41e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3291a82b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fa704ffmSocket: android.net.LocalSocket@19dd02cc impl:android.net.LocalSocketImpl@fbc8915 fd:FileDescriptor[74]
08-30 22:40:08.402  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19dd02cc impl:android.net.LocalSocketImpl@fbc8915 fd:FileDescriptor[74]
,08-30 22:40:08.402  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.402  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.402  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.402  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.402  2649  2731 D BluetoothAdapterProperties: onBluetoothDisable()
08-30 22:40:08.402  2649  2731 D BluetoothAdapterProperties: mDiscovering is false
08-30 22:40:08.402  1015  4151 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 22:40:08.412  1291  1291 D BluetoothPbap: Proxy object disconnected
08-30 22:40:08.412  2649  2731 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-30 22:40:08.412  1291  1291 D PbapServerProfile: Bluetooth service disconnected
,08-30 22:40:08.412  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:08.412  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:40:08.412  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:08.412  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
08-30 22:40:08.412  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.412  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 22:40:08.412  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 22:40:08.412  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.412  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-30 22:40:08.422  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.422  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:08.422  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 22:40:08.422  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-30 22:40:08.422  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-30 22:40:08.422  1769  1769 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 22:40:08.422  1015  4152 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:08.422  1015  4358 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 22:40:08.422  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:08.422  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:08.432  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:08.432  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 22:40:08.432  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:08.432  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 22:40:08.432  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 22:40:08.432  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:08.432  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.442  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-30 22:40:08.442  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 22:40:08.442  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.442  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:08.442  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 22:40:08.442  2649  2734 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 22:40:08.442  2649  2734 D BluetoothAdapterProperties: Scan Mode:20
,08-30 22:40:08.442  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:08.442  1015  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 22:40:08.452  2649  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 22:40:08.452  2649  2731 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-30 22:40:08.452  2649  2731 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-30 22:40:08.452  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-30 22:40:08.452  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.452  2649  2731 E bt-btif : cmd socket is not created
,08-30 22:40:08.452  2649  2731 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-30 22:40:08.452  2649  2821 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-30 22:40:08.452  2649  2821 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-30 22:40:08.452  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:08.452  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:08.452  2649  2821 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-30 22:40:08.452  2649  4823 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-30 22:40:08.452  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:08.452  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.452  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.452  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 22:40:08.462  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:08.462  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bf0f21b, channel: 5, state: LISTENING
08-30 22:40:08.462  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bf0f21b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f809c07, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b3d7fb8mSocket: android.net.LocalSocket@2669a191 impl:android.net.LocalSocketImpl@115a28f6 fd:FileDescriptor[76]
08-30 22:40:08.462  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2669a191 impl:android.net.LocalSocketImpl@115a28f6 fd:FileDescriptor[76]
,08-30 22:40:08.462  2649  2649 I BtOppRfcommListener: stopping Accept Thread
08-30 22:40:08.462  2649  2649 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2294f7, channel: 12, state: LISTENING
08-30 22:40:08.462  2649  2649 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2294f7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36414059, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@626df64mSocket: android.net.LocalSocket@21f5c5cd impl:android.net.LocalSocketImpl@2177de82 fd:FileDescriptor[80]
08-30 22:40:08.462  2649  2649 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21f5c5cd impl:android.net.LocalSocketImpl@2177de82 fd:FileDescriptor[80]
08-30 22:40:08.462  2649  4823 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 22:40:08.472  2649  2649 V BluetoothOppManager: cleanUp...
,08-30 22:40:08.472  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:08.472  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:08.472  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:08.472  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 22:40:08.472  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-30 22:40:08.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:08.492  6398  6398 E Zygote  : MountEmulatedStorage(),
08-30 22:40:08.492  6398  6398 E Zygote  : v2
08-30 22:40:08.492  6398  6398 I libpersona: KNOX_SDCARD checking this for 10003
08-30 22:40:08.492  6398  6398 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:08.492  6398  6398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:08.492  1015  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6398 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-30 22:40:08.492  6398  6398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:08.502  6398  6398 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:08.522  6398  6398 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:08.522  6398  6398 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:08.552  6398  6398 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-30 22:40:08.582  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 22:40:08.582  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 22:40:08.582   279   967 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:40:08.582  1932  4388 V NativeCrypto: Read error: ssl=0xb929a2e8: I/O error during system call, Connection timed out
,08-30 22:40:08.592  1932  4388 V NativeCrypto: SSL shutdown failed: ssl=0xb929a2e8: I/O error during system call, Broken pipe
08-30 22:40:08.592  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.592  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 22:40:08.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:08.592  1932  4388 E GCM     : Wifi connection closed with errorCode 20
,08-30 22:40:08.592  6398  6398 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-30 22:40:08.592  6398  6398 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-30 22:40:08.592  6398  6398 D UserAnalysis: Create SecureDbHelper
,08-30 22:40:08.592  1015  4152 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,08-30 22:40:08.592  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:08.592  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:40:08.592  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-30 22:40:08.592  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:08.592  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-30 22:40:08.602  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:08.602  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:40:08.602  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:08.602  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3,
08-30 22:40:08.602  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-30 22:40:08.602  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-30 22:40:08.602  1015  2205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-30 22:40:08.602  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 22:40:08.602  1015  2205 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,08-30 22:40:08.602  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-30 22:40:08.602  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:08.612  1015  2205 I qtaguid : Untagging socket 361,
08-30 22:40:08.612  1015  2205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:08.612  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.612  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:08.612  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.612  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.612  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.612  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:08.622  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-30 22:40:08.622  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-30 22:40:08.622  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:08.622  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:40:08.622  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
08-30 22:40:08.622  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-30 22:40:08.632  6398  6398 D IntelligenceServiceApplication: onCreate(),
,08-30 22:40:08.632  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 22:40:08.632  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 22:40:08.632  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 22:40:08.632  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 22:40:08.632  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-30 22:40:08.632  1015  1125 E WifiNative-wlan0: do suspend true
08-30 22:40:08.632  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:08.632  1015  1046 D WifiDisplayController: disconnect,
08-30 22:40:08.632  1015  1046 D WifiDisplayController: updateConnection
08-30 22:40:08.632  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:08.632  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 22:40:08.632  1015  1124 D WifiP2pService: P2pDisablingState,
08-30 22:40:08.632  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-30 22:40:08.632  1015  1124 D WifiP2pService: p2p socket connection lost
08-30 22:40:08.632  1015  1124 D WifiP2pService: P2pDisabledState
08-30 22:40:08.632  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-30 22:40:08.632  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
08-30 22:40:08.632  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 22:40:08.632  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-30 22:40:08.632  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 22:40:08.632  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 22:40:08.642  1015  1133 I ActivityManager: Killing 5287:com.dropbox.android/u0a92 (adj 15): empty #31
,08-30 22:40:08.642  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 22:40:08.642  1015  1382 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 22:40:08.642  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 22:40:08.652  6398  6398 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-30 22:40:08.652  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.652  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:08.652  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.652  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.652  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.652  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:08.652  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:08.652  2649  2821 W bt-btif : ag scb idx 1 not allocated
08-30 22:40:08.652  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-30 22:40:08.652  2649  2821 W bt-btif : ag scb idx 2 not allocated
08-30 22:40:08.652  2649  2821 E bt-btif : BTA AG is already disabled, ignoring ...
08-30 22:40:08.652  2649  2916 I bt_userial_mct: exiting userial_read_thread
08-30 22:40:08.652  2649  2916 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 22:40:08.652  2649  2734 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 22:40:08.652  2649  2824 I bt_vendor: hw_epilog_process
,08-30 22:40:08.652  2649  2734 D bt_userial_mct: userial_close
08-30 22:40:08.652  2649  2734 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-30 22:40:08.652  6398  6398 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-30 22:40:08.652  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.652  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.652  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:08.652  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:08.662   279   963 D EnterpriseController: uids 1000
,08-30 22:40:08.662   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:08.662   279   963 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-30 22:40:08.662   279   967 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:40:08.662  6398  6398 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-30 22:40:08.662  1173  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 22:40:08.662  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 22:40:08.662  3802  6316 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-30 22:40:08.662  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-30 22:40:08.662  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 22:40:08.662  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:40:08.662  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-30 22:40:08.662  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-30 22:40:08.662  1460  1460 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:40:08.662  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-30 22:40:08.662  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-30 22:40:08.672  6425  6425 E Zygote  : MountEmulatedStorage()
08-30 22:40:08.672  6425  6425 E Zygote  : v2
08-30 22:40:08.672  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 22:40:08.672  6425  6425 I libpersona: KNOX_SDCARD checking this for 10107
08-30 22:40:08.672  6425  6425 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:08.672  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-30 22:40:08.672  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 22:40:08.672  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-11ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:40:08.672  1015  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6425 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-30 22:40:08.672  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 22:40:08.672  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-30 22:40:08.682  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 22:40:08.682  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-30 22:40:08.682  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:08.682  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:40:08.682  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:08.682  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.682  1015  1122 V NetworkStats: updateIfacesLocked()
08-30 22:40:08.682  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 22:40:08.682  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:08.682  6425  6425 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:08.682  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:08.682  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:08.682  6425  6425 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:08.682  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
08-30 22:40:08.682  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 22:40:08.682  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 22:40:08.682  1173  1173 D StatusBar.NetworkController: updateDataNetType(),
08-30 22:40:08.682  1015  1122 V NetworkStats: performPollLocked() took 7ms
08-30 22:40:08.682  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 22:40:08.682  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 22:40:08.682  2090  2090 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 22:40:08.682  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.692  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-30 22:40:08.682   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-30 22:40:08.682  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.682  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:08.682  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.692  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.692  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 22:40:08.692  6425  6425 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.692  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.692  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.692  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:08.702  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 22:40:08.702  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:08.702  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:08.702  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.702  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:08.702  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:08.702  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 22:40:08.702  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.702  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.702  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.702  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:08.702  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:08.702  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-30 22:40:08.702  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 22:40:08.702  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:08.702  1173  1173 D HotspotTile: onReceive : 0, 0
,08-30 22:40:08.712  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:08.712  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:08.712  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:40:08.712  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.712  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:08.722  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:08.722  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:08.722  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:08.722  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:40:08.722  6425  6425 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:08.722  6425  6425 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:08.782  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.782  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.782  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.782  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.782  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.782  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.792  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 22:40:08.792  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.792  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,08-30 22:40:08.792  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.792  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.792  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.792  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.792  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.792  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.802  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.802  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.812  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.812  1460  1460 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-30 22:40:08.812  1460  1460 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-30 22:40:08.822  2090  2090 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 22:40:08.842  6253  6253 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 22:40:08.892  2090  2090 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 22:40:08.892  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 22:40:08.892  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:08.902  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 22:40:08.902  2649  2734 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 22:40:08.902  2649  2734 I bt_vendor: bluetooth satus is on
08-30 22:40:08.902  2649  2734 I bt_vendor: bt-vendor : resetting BT status
08-30 22:40:08.902  2649  2734 I bt_vendor: Starting hciattach daemon
08-30 22:40:08.902  2649  2734 I bt_vendor: try to set false
,08-30 22:40:08.902  2649  2734 I bt_vendor: Starting hciattach daemon
08-30 22:40:08.902  2649  2734 I bt_vendor: try to set false
,08-30 22:40:08.902  2649  2734 I bt_vendor: cleanup
,08-30 22:40:08.902  2649  2821 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-30 22:40:08.902  2649  2734 I GKI_LINUX: GKI_exit_task 0 done
08-30 22:40:08.902  2649  2734 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 22:40:08.902  2649  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-30 22:40:08.902  2649  2731 D BtConfig.SecureMode: isSecureModeOn:false
08-30 22:40:08.902  2649  2731 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-30 22:40:08.902  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 22:40:08.902  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 22:40:08.902  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 22:40:08.902  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:08.902  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.902  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.902  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.902  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.912  2649  2649 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 22:40:08.912  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 22:40:08.912  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:08.912  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:08.912  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:08.912  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.912  2649  2649 D BtGatt.GattService: Received stop request...Stopping profile...
,08-30 22:40:08.912  2649  2649 D BtGatt.GattService: stop()
08-30 22:40:08.912  2649  2649 D BtGatt.AdvertiseManager: advertise clients cleared
,08-30 22:40:08.912  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:08.912  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.912  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.912  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:08.912  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:08.922  2090  2090 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-30 22:40:08.922  2090  2090 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 22:40:08.922  2090  2090 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 22:40:08.922  2090  2090 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:08.922  2090  2090 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 22:40:08.922  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:08.922  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:08.922  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:08.922  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 22:40:08.922  1015  1128 D Tethering: InitialState.processMessage what=4
08-30 22:40:08.922  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:08.922  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:08.922  1015  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-30 22:40:08.922  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:08.922  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.932  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:08.932  1015  1128 E Tethering: No numeric data
08-30 22:40:08.932  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.932  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.932  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.932  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-30 22:40:08.932  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-30 22:40:08.932  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:40:08.932  1015  1128 D Tethering: clearTetheredNotification()
,08-30 22:40:08.932  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:08.932  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 22:40:08.932  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-30 22:40:08.932  2649  2649 D HeadsetService: Received stop request...Stopping profile...
,08-30 22:40:08.932  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:08.932  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:08.942  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 22:40:08.942  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:08.942  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 22:40:08.942  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 22:40:08.942  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:08.942  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 22:40:08.942  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:08.942  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.942  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.942  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.942  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.942  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 22:40:08.942  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 22:40:08.942  1015  1488 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-30 22:40:08.942  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-30 22:40:08.952  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:08.952  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 22:40:08.952  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:08.952  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:08.952  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 22:40:08.952  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 22:40:08.952  1015  2973 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:08.952  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 22:40:08.952  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.952  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:08.952  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.952  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 22:40:08.952  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 22:40:08.952  1015  1122 V NetworkStats: performPollLocked() took 18ms
08-30 22:40:08.952  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:08.962  1291  1291 D HeadsetProfile: Bluetooth service disconnected
,08-30 22:40:08.962  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 22:40:08.962  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:08.962  1015  4152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:08.962  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 22:40:08.962  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:08.962  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.962  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.962  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.962  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 22:40:08.962  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:08.962  1015  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 22:40:08.962  2649  2731 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:08.962  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-30 22:40:08.962  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.962  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 22:40:08.962  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 22:40:08.962  1015  4151 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:08.962  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 22:40:08.962  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-30 22:40:08.962  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 22:40:08.962  2649  2731 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-30 22:40:08.972  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:08.972  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:08.972  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:08.972  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:08.972  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 22:40:08.972  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 22:40:08.972  2649  2731 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 22:40:08.972  2649  2731 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-30 22:40:08.972  2649  2731 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 22:40:08.972  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-30 22:40:08.972  2649  2649 D A2dpService: Received stop request...Stopping profile...
,08-30 22:40:08.972  2649  2769 D A2dpStateMachine: Exit Disconnected: -1
,08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.k.c(PG:583)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.e.b(PG:170)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.972  6425  6425 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.io.File.exists(File.java:363)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:08.972  6425  6425 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:08.982  1015  1476 I ActivityManager: Killing 5476:com.google.android.music:main/u0a111 (adj 15): empty #31
08-30 22:40:08.972   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb83ac7c8
08-30 22:40:08.972   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-30 22:40:08.982   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-30 22:40:08.982   274   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1204107976)
08-30 22:40:09.002  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.002  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:09.002  2876  2876 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:09.002  1291  1291 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:09.002  1291  1291 D A2dpProfile: Bluetooth service disconnected
08-30 22:40:09.002  2649  2649 D HidService: Received stop request...Stopping profile...
08-30 22:40:09.002  2649  2649 D HidService: Stopping Bluetooth HidService
08-30 22:40:09.002  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-30 22:40:09.002  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 22:40:09.012  2649  2649 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 22:40:09.012  2649  2649 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-30 22:40:09.012  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.012  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-30 22:40:09.012  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:09.012  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 22:40:09.012  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 22:40:09.012  2649  2649 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-30 22:40:09.012  2649  2649 D HealthService: Received stop request...Stopping profile...
08-30 22:40:09.012  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.012  2649  2649 D PanService: Received stop request...Stopping profile...
08-30 22:40:09.022  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.022  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-30 22:40:09.022  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-30 22:40:09.022  1291  1291 D HidProfile: Bluetooth service disconnected
08-30 22:40:09.022  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-30 22:40:09.022  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 22:40:09.022  1291  1291 D PanProfile: Bluetooth service disconnected
08-30 22:40:09.022  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 22:40:09.022  2649  2649 D BluetoothMapService: Received stop request...Stopping profile...
08-30 22:40:09.032  1015  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:09.032  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:09.032  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.032  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.032  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:09.032  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.032  3655  3655 I Hs20UtilService: Starting #8
08-30 22:40:09.032  1291  1291 D BluetoothMap: Proxy object disconnected
08-30 22:40:09.032  1291  1291 D MapProfile: Bluetooth service disconnected
08-30 22:40:09.032  3655  3699 I Hs20UtilService: Message received 5007
08-30 22:40:09.032  2649  2649 D SapService: Received stop request...Stopping profile...
08-30 22:40:09.032  2649  2649 D SapService: Stopping Bluetooth SapService
08-30 22:40:09.032  2649  2649 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:09.032  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:09.032  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 22:40:09.032   274   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-30 22:40:09.032   274   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-30 22:40:09.032   274   334 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1204107976) wakelock released: 1, error no: 0
08-30 22:40:09.032   274   334 I rmt_storage: 
08-30 22:40:09.042   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb83ac7c8
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 22:40:09.042  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 22:40:09.042  2649  2649 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-30 22:40:09.042  2649  2771 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 22:40:09.042  2649  2649 I GKI_LINUX: GKI_exit_task 2 done
08-30 22:40:09.042  2649  2649 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 22:40:09.042  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 22:40:09.042  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-30 22:40:09.042  2649  2649 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:40:09.042  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 22:40:09.042  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:09.042  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 22:40:09.042  2649  2649 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 22:40:09.042  2649  2649 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 22:40:09.042  2649  2649 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 22:40:09.042  2649  2649 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 22:40:09.042  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:09.042  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:09.042  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:09.042  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 22:40:09.042  2649  2649 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-30 22:40:09.042  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 22:40:09.042  1291  1291 D SapProfile: Bluetooth service disconnected
08-30 22:40:09.042  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 22:40:09.042  2649  2731 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 22:40:09.042  2649  2731 D BluetoothAdapterProperties: Setting state to 10
08-30 22:40:09.042  2649  2731 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 22:40:09.042  2649  2731 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:09.042  2649  2731 D BluetoothAdapterService: updateAdapterState state is 10
08-30 22:40:09.042  2649  2731 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:09.042  2649  2731 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 22:40:09.042  2649  2731 I BluetoothAdapterState: Entering OffState
08-30 22:40:09.052  6253  6262 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.052  6253  6262 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.052  6253  6262 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 22:40:09.052  6253  6262 D BluetoothLeAdvertiser: Exit stop advertising
08-30 22:40:09.052  6253  6262 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 22:40:09.052  6253  6262 D BluetoothLeScanner: Exiting stopAllScan
08-30 22:40:09.052  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:40:09.052  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:40:09.052  1291  1306 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.052  1291  1306 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.052  2876  2884 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:40:09.052  1291  1300 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-30 22:40:09.062  1460  1469 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.062  1460  1469 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.062  2876  6463 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.062  2876  6463 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.062  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 22:40:09.062  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 22:40:09.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 22:40:09.062  2649  6394 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.062  2649  6394 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:09.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:09.062  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:09.062  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 22:40:09.062  2649  2662 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:40:09.062  1015  4152 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-30 22:40:09.062  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.072  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.072  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.072  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.072  6425  6457 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-30 22:40:09.082  6465  6465 E Zygote  : MountEmulatedStorage()
08-30 22:40:09.082  6465  6465 E Zygote  : v2
08-30 22:40:09.082  6465  6465 I libpersona: KNOX_SDCARD checking this for 10068
08-30 22:40:09.082  6465  6465 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:09.082  1015  4152 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6465 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:40:09.082  6465  6465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:09.082  1932  1941 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.082  1932  1941 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.082  1291  1300 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 22:40:09.082  1291  1300 D Bluetoothsap: Unbinding service...
,08-30 22:40:09.082  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.082  1441  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:09.082  6465  6465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:09.082  1430  1442 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.082  1430  1442 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:09.082  1291  1306 D BluetoothPbap: onBluetoothStateChange: up=false
08-30 22:40:09.082  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.082  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
08-30 22:40:09.082  1291  1300 D BluetoothMap: onBluetoothStateChange: up=false
08-30 22:40:09.082  1173  3818 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:09.082  1173  3818 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:09.092  6465  6465 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:09.092  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-30 22:40:09.092  2090  2090 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 22:40:09.102  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 22:40:09.102  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:09.102  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 22:40:09.102  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 22:40:09.112  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:09.112  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 22:40:09.112  1173  1700 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:09.112  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:09.112  1173  1173 D BluetoothTile:  getBluetoothState : 10
08-30 22:40:09.112  1173  1700 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:09.112  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:09.112  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:09.112  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:09.112  1769  1769 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 22:40:09.112  1015  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-30 22:40:09.112  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:09.122  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:09.122  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.122  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.122  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:09.122  6465  6465 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:09.152  2090  2090 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-30 22:40:09.152  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:09.152  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:09.152  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:09.182  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-30 22:40:09.182  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-30 22:40:09.202  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:09.202  3160  3160 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-30 22:40:09.202  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.202  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.212  3160  3160 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-30 22:40:09.252  1015  1488 I art     : Explicit concurrent mark sweep GC freed 54222(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 28MB/42MB, paused 2.550ms total 160.229ms
,08-30 22:40:09.252  1015  1488 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 22:40:09.252  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.252  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:09.252  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-30 22:40:09.252  1932  2125 D BluetoothAdapter: 141158976: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:09.252  1932  2125 D BluetoothAdapter: 141158976: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:09.262  1015  3002 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:09.272  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:09.272  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.272  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:09.272  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:09.272  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-30 22:40:09.272  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 22:40:09.272  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 22:40:09.282  2649  2734 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-30 22:40:09.282  2649  2649 I GKI_LINUX: GKI_exit_task 1 done
08-30 22:40:09.282  2649  2649 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 22:40:09.282  2649  2649 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 22:40:09.282  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:09.282  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 22:40:09.282  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:09.282  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:09.282  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:09.282  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:09.282  5248  5248 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:09.282  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:09.282  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-30 22:40:09.282  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:09.282  2649  2649 I art     : System.exit called, status: 0
08-30 22:40:09.282  2649  2649 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-30 22:40:09.282  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 22:40:09.282  1932  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:09.292  1173  1173 D HotspotTile: onReceive : 1, 0
,08-30 22:40:09.292  6465  6465 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 22:40:09.292  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:09.292  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.292  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:09.302  1015  1382 I ActivityManager: Process com.android.bluetooth (pid 2649)(adj 0) has died(46,1089)
,08-30 22:40:09.312  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:09.322  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 22:40:09.342  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 22:40:09.352  1015  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-30 22:40:09.352  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.352  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.352  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.352  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.362  1015  1503 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6485 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:40:09.362  6485  6485 E Zygote  : MountEmulatedStorage()
08-30 22:40:09.362  6485  6485 E Zygote  : v2
08-30 22:40:09.362  6485  6485 I libpersona: KNOX_SDCARD checking this for 10069
08-30 22:40:09.362  6485  6485 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:09.362  1015  1503 I ActivityManager: Killing 5248:com.google.android.talk/u0a104 (adj 15): empty #31
,08-30 22:40:09.362  6485  6485 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:09.372  6485  6485 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:09.372  6485  6485 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:09.382  6485  6485 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:09.382  6485  6485 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:09.392  1015  1217 I ActivityManager: Killing 5587:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-30 22:40:09.412  6485  6485 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:09.422  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.422  1015  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:09.422  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-30 22:40:09.422  1015  1382 I ActivityManager: Killing 5543:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-30 22:40:09.422  1015  1382 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!,
,08-30 22:40:09.422  1015  1382 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver}
08-30 22:40:09.422  1015  1382 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-30 22:40:09.422  1015  1382 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:09.422  1015  1382 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-30 22:40:09.422  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.432  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.432  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.432  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.442  6500  6500 E Zygote  : MountEmulatedStorage(),
08-30 22:40:09.442  6500  6500 E Zygote  : v2
08-30 22:40:09.442  6500  6500 I libpersona: KNOX_SDCARD checking this for 10104
08-30 22:40:09.442  6500  6500 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:09.452  6500  6500 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:09.452  1015  1382 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6500 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-30 22:40:09.452  6500  6500 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:09.452  6500  6500 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 22:40:09.472  6500  6500 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-30 22:40:09.472  6500  6500 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:09.482  1015  1040 W libprocessgroup: failed to open /acct/uid_10104/pid_5248/cgroup.procs: No such file or directory
,08-30 22:40:09.482  6500  6500 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-30 22:40:09.642  6500  6523 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-30 22:40:09.642  6500  6523 I Babel   : MmsConfig.loadMmsSettings
,08-30 22:40:09.642  6500  6523 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-30 22:40:09.642  6500  6523 I Babel   : MmsConfig.loadFromDatabase
,08-30 22:40:09.662  6500  6523 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-30 22:40:09.662  6500  6523 I Babel   : MmsConfig.loadFromResources
,08-30 22:40:09.662  6500  6523 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-30 22:40:09.662  6500  6523 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-30 22:40:09.662  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-30 22:40:09.662  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-30 22:40:09.662  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.662  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:09.672  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 22:40:09.672  6500  6500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:09.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:09.702   289   289 E SMD     : DCD OFF
,08-30 22:40:09.702  6500  6500 I Babel_StickerModule: App launched.
,08-30 22:40:09.722  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 22:40:09.722  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:09.722  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.722  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.722  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:09.722  3655  3655 I Hs20UtilService: Starting #9
,08-30 22:40:09.722  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:09.722  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:09.722  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 22:40:09.722  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:09.722   284   284 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-30 22:40:09.732   284   284 W QCamera2Factory: getCameraInfo: X
08-30 22:40:09.732  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 22:40:09.732  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:09.732  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 22:40:09.732  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:09.732   284   730 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-30 22:40:09.732   284   730 W QCamera2Factory: getCameraInfo: X
,08-30 22:40:09.732  1015  4135 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.732  1015  4135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.732  1015  4135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.742  1015  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:09.742  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:09.742  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.742  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.742  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:09.742  3655  3655 I Hs20UtilService: Starting #10
,08-30 22:40:09.742  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:09.742  1015  4135 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-30 22:40:09.752  1015  4135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.752  1015  4135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.752  1015  4135 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.752  1015  4135 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.752  6500  6500 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-30 22:40:09.762  6525  6525 E Zygote  : MountEmulatedStorage(),
08-30 22:40:09.762  6525  6525 E Zygote  : v2
08-30 22:40:09.762  6525  6525 I libpersona: KNOX_SDCARD checking this for 1000
,08-30 22:40:09.762  6525  6525 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:09.762  1015  4135 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6525 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-30 22:40:09.762  6525  6525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:09.762  6525  6525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 22:40:09.772  6525  6525 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:09.772  6500  6500 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 22:40:09.772  6500  6500 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 22:40:09.782  6500  6500 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-30 22:40:09.782  6500  6500 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-30 22:40:09.792  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:09.792  6525  6525 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:09.802  6500  6500 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-30 22:40:09.802  6500  6500 W AudioCapabilities: Unsupported mime audio/x-ima
,08-30 22:40:09.802  6500  6500 W AudioCapabilities: Unsupported mime audio/qcelp
,08-30 22:40:09.802  6500  6500 W AudioCapabilities: Unsupported mime audio/evrc
,08-30 22:40:09.812  1015  2735 D SSRM:n  : SIOP:: AP = 340
,08-30 22:40:09.812  6500  6500 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 22:40:09.822  6500  6500 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 22:40:09.822  6500  6500 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-30 22:40:09.822  6500  6500 W VideoCapabilities: Unsupported mime video/wvc1
,08-30 22:40:09.832  6500  6500 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-30 22:40:09.832  6500  6500 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-30 22:40:09.832  6500  6500 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-30 22:40:09.832  6500  6500 W VideoCapabilities: Unsupported mime video/mp43
,08-30 22:40:09.842  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 22:40:09.842  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:09.842  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 22:40:09.842  6500  6500 W VideoCapabilities: Unsupported mime video/sorenson
,08-30 22:40:09.842  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:09.842  1015  1382 I ActivityManager: Killing 5655:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-30 22:40:09.852  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.852  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.852  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.852  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.852  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.852  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.852  6500  6500 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-30 22:40:09.862  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.862  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.862  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.862  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.862  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.862  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.872  1015  1043 D Tethering: interfaceRemoved wlan0
08-30 22:40:09.872  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 22:40:09.872  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.872  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.872  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.872  6500  6500 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-30 22:40:09.872  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.872  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.872  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.882  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.882  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.882  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.882  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.882  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.882  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.892  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.892  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.892  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.892  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.902  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.902  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.902  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.902  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-30 22:40:09.912  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:09.912  1015  3002 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-30 22:40:09.912  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 22:40:09.912  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:09.912  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:09.912  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 22:40:09.922  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-30 22:40:09.922  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-30 22:40:09.922  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
08-30 22:40:09.922  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-30 22:40:09.922  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-30 22:40:09.922  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=1243)
08-30 22:40:09.922  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'StartingDockService' (uid=1000, pid=1291, ws=null) (elapsedTime=7)
,08-30 22:40:09.922  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:09.922  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:09.922  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-30 22:40:09.922  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:09.932  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:09.932  1015  4135 I ActivityManager: Killing 4824:com.android.mms/u0a46 (adj 15): empty #31
,08-30 22:40:09.932  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:09.932  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 22:40:09.942  1015  1043 D Tethering: interfaceRemoved p2p0
,08-30 22:40:09.942  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 22:40:09.942  1015  4151 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-30 22:40:09.942  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.942  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.942  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:09.942  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:09.952  6543  6543 E Zygote  : MountEmulatedStorage()
08-30 22:40:09.952  6543  6543 I libpersona: KNOX_SDCARD checking this for 1002
08-30 22:40:09.952  6543  6543 E Zygote  : v2
08-30 22:40:09.952  6543  6543 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:09.952  6543  6543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:09.962  6543  6543 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:09.962  1015  4151 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6543 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-30 22:40:09.962  6543  6543 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:09.982  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:09.982  6543  6543 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:09.992  6543  6543 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-30 22:40:09.992  6543  6543 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:40:10.022  6543  6543 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 22:40:10.042  1015  1028 D CountryDetector: No listener is left
,08-30 22:40:10.052  6543  6543 D BtSettings.ProfileConfig: Adding GattService
,08-30 22:40:10.052  6543  6543 D BtSettings.ProfileConfig: Adding HeadsetService
,08-30 22:40:10.052  6543  6543 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding HidService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding HealthService
08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding PanService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding SapService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding SapClientService
,08-30 22:40:10.062  6543  6543 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 22:40:10.062  6543  6543 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 22:40:10.062  1015  3002 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 22:40:10.062  1015  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.062  1015  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.062  1015  3002 D SettingsProvider: selectionArgs: false
08-30 22:40:10.062  1015  3002 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.062  1015  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.062  1015  3002 D SettingsProvider: ret = -1
,08-30 22:40:10.062  1015  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 22:40:10.072  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.072  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.072  1015  1489 D SettingsProvider: selectionArgs: false
08-30 22:40:10.072  1015  1489 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:10.072  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.072  1015  1489 D SettingsProvider: ret = -1
,08-30 22:40:10.072  1015  1488 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:10.072  1015  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.072  1015  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.072  1015  1488 D SettingsProvider: selectionArgs: false
,08-30 22:40:10.072  1015  1488 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.072  1015  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:10.072  1015  1488 D SettingsProvider: ret = -1
,08-30 22:40:10.072  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-30 22:40:10.072  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 22:40:10.072  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.072  1015  1027 D SettingsProvider: selectionArgs: false
08-30 22:40:10.072  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.072  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.072  1015  1027 D SettingsProvider: ret = -1
,08-30 22:40:10.072  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-30 22:40:10.072  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.072  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.072  1015  1133 D SettingsProvider: selectionArgs: false
08-30 22:40:10.072  1015  1133 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.072  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.072  1015  1133 D SettingsProvider: ret = -1
,08-30 22:40:10.072  1015  4358 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 22:40:10.072  1015  4358 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 22:40:10.072  1015  4358 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.072  1015  4358 D SettingsProvider: selectionArgs: false
08-30 22:40:10.072  1015  4358 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:10.072  1015  4358 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.072  1015  4358 D SettingsProvider: ret = -1
,08-30 22:40:10.072  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:10.072  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.072  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:10.072  1015  1476 D SettingsProvider: selectionArgs: false
08-30 22:40:10.072  1015  1476 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.072  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:10.072  1015  1476 D SettingsProvider: ret = -1
,08-30 22:40:10.082  1015  1503 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-30 22:40:10.082  1015  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.082  1015  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:10.082  1015  1503 D SettingsProvider: selectionArgs: false
08-30 22:40:10.082  1015  1503 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.082  1015  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.082  1015  1503 D SettingsProvider: ret = -1
,08-30 22:40:10.082  1015  4152 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:10.082  1015  4152 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.082  1015  4152 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:10.082  1015  4152 D SettingsProvider: selectionArgs: false
08-30 22:40:10.082  1015  4152 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.082  1015  4152 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:10.082  1015  4152 D SettingsProvider: ret = -1
,08-30 22:40:10.082  1015  1382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService,
08-30 22:40:10.082  1015  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.082  1015  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.082  1015  1382 D SettingsProvider: selectionArgs: false
,08-30 22:40:10.082  1015  1382 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:10.082  1015  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.082  1015  1382 D SettingsProvider: ret = -1
08-30 22:40:10.082  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:10.082  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.082  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.082  1015  1028 D SettingsProvider: selectionArgs: false
08-30 22:40:10.082  1015  1028 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.082  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:10.082  1015  1028 D SettingsProvider: ret = -1
08-30 22:40:10.082  1015  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 22:40:10.082  1015  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:10.082  1015  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:10.082  1015  1217 D SettingsProvider: selectionArgs: false
,08-30 22:40:10.082  1015  1217 D SettingsProvider: selectionArgs: 1002
08-30 22:40:10.082  1015  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:10.082  1015  1217 D SettingsProvider: ret = -1
,08-30 22:40:10.092  1015  2973 I ActivityManager: Killing 5859:com.sec.pcw.device/1000 (adj 15): empty #31
,08-30 22:40:10.102  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:10.102  1015  1488 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:10.102  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-30 22:40:10.102  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.102  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.102  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:10.112  1932  6559 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 22:40:10.112  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:10.112  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:10.112  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:10.112  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.112  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:10.122  1015  3002 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-30 22:40:10.122  1015  3002 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.pcw.device/com.sec.pcw.device.receiver.SYSTEMReceiver}
08-30 22:40:10.122  1015  3002 W BroadcastQueue: android.os.TransactionTooLargeException
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-30 22:40:10.122  1015  3002 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:10.122  1015  3002 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-30 22:40:10.132  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.132  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.132  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.132  1015  3002 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.142  6560  6560 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.142  6560  6560 I libpersona: KNOX_SDCARD checking this for 1000
,08-30 22:40:10.142  6560  6560 E Zygote  : v2
08-30 22:40:10.142  6560  6560 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:10.142  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:10.142  1015  3002 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6560 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 22:40:10.152  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:10.152  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:10.152  1015  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
08-30 22:40:10.152  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.152  1015  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.152  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:10.162  1932  6559 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 22:40:10.172  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.172  6560  6560 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.192  6560  6560 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-30 22:40:10.192  6560  6560 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-30 22:40:10.192  6560  6560 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-30 22:40:10.202  1015  1040 W libprocessgroup: failed to open /acct/uid_1000/pid_5859/cgroup.procs: No such file or directory
,08-30 22:40:10.202  6560  6560 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-30 22:40:10.202  6560  6560 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-30 22:40:10.202  6560  6560 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 22:40:10.202  6560  6560 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:10.212  1015  4151 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-30 22:40:10.212  1015  4151 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-30 22:40:10.212  1015  4151 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-30 22:40:10.212  6560  6575 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-30 22:40:10.212  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.212  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.212  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.212  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.222  1015  4151 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6577 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:40:10.232  6577  6577 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.232  6577  6577 E Zygote  : v2
08-30 22:40:10.232  6577  6577 I libpersona: KNOX_SDCARD checking this for 10111
,08-30 22:40:10.232  6577  6577 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:10.232  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:10.232  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-30 22:40:10.232  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.232  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.232  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.232  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.232  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:10.232  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-30 22:40:10.252  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:10.252  6577  6577 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.252   307   307 I art     : Explicit concurrent mark sweep GC freed 8740(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 725us total 31.290ms
,08-30 22:40:10.282   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 20.239ms,
,08-30 22:40:10.302   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 711us total 19.753ms
,08-30 22:40:10.312  6592  6592 E Zygote  : MountEmulatedStorage(),
08-30 22:40:10.312  6592  6592 I libpersona: KNOX_SDCARD checking this for 10009
08-30 22:40:10.312  6592  6592 E Zygote  : v2
08-30 22:40:10.312  6592  6592 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:10.312  6592  6592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:10.312  1015  1041 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6592 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:40:10.312  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-30 22:40:10.322  1724  1724 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-30 22:40:10.322  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.322  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.322  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.322  6592  6592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:10.322  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.322  6592  6592 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-30 22:40:10.342  6606  6606 E Zygote  : MountEmulatedStorage(),
08-30 22:40:10.342  6606  6606 E Zygote  : v2
08-30 22:40:10.342  6606  6606 I libpersona: KNOX_SDCARD checking this for 10145
08-30 22:40:10.342  6606  6606 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:10.342  6606  6606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:10.342  6606  6606 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:10.342  6606  6606 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:10.352  1015  1041 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6606 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
08-30 22:40:10.352  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:10.352  6592  6592 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.362  1724  1724 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-30 22:40:10.362  1724  1724 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-30 22:40:10.362  1724  1724 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-30 22:40:10.362  1724  1724 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-30 22:40:10.372  1724  1724 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-30 22:40:10.372  1724  1724 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-30 22:40:10.372  1312  3524 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 10
,08-30 22:40:10.372  1015  1217 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-30 22:40:10.382  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.382  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.382  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.382  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.392  6606  6606 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.392  6606  6606 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.402  6622  6622 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.402  6622  6622 E Zygote  : v2
08-30 22:40:10.402  6622  6622 I libpersona: KNOX_SDCARD checking this for 10081
08-30 22:40:10.402  6622  6622 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:10.412  1015  1217 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6622 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:40:10.412  6622  6622 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:10.422  6622  6622 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:10.422  6622  6622 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-30 22:40:10.422  1724  1724 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-30 22:40:10.442  6606  6606 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-30 22:40:10.442  6606  6606 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:40:10.442  6606  6606 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 22:40:10.442  6606  6606 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:10.442  6606  6606 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 22:40:10.452  6622  6622 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:10.452  6622  6622 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.462  1015  1027 I ActivityManager: Killing 5890:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-30 22:40:10.462  6577  6577 I MusicStore: Database version: 108
,08-30 22:40:10.472  3705  3705 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 22:40:10 GMT+02:00 2016
,08-30 22:40:10.472  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 22:40:10.472  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 22:40:10.472  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.472  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:10.472  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 22:40:10.472  3705  3705 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 22:40:10.482  3705  3705 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-30 22:40:10.482  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-30 22:40:10.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.482  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.482  3705  3705 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 22:40:10.482  3705  3705 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-30 22:40:10.492  6643  6643 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.492  6643  6643 E Zygote  : v2
08-30 22:40:10.492  6643  6643 I libpersona: KNOX_SDCARD checking this for 10034
08-30 22:40:10.492  6643  6643 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:10.492  6643  6643 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:10.502  1015  1027 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6643 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
08-30 22:40:10.502  3705  6642 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-30 22:40:10.502  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 22:40:10.502  6643  6643 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:10.502  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-30 22:40:10.502  3705  6642 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-30 22:40:10.502  6643  6643 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:10.502  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.502  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.502  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:10.522  1015  1133 D RCPManagerService: exchangeData() failure , invalid userId
08-30 22:40:10.522  3705  6642 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-30 22:40:10.522  6643  6643 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.522  6643  6643 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.532  3705  6642 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-30 22:40:10.532  3705  3705 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-30 22:40:10.542  1015  4135 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.562  6643  6643 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-30 22:40:10.582  3251  6664 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-30 22:40:10.592  3251  6664 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
08-30 22:40:10.592  1015  1488 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-30 22:40:10.592  3251  6664 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-30 22:40:10.592  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.592  3251  6664 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-30 22:40:10.592  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.592  3251  6664 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-30 22:40:10.592  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.592  1015  2973 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.592  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.602  6577  6577 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 22:40:10.602  6577  6577 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 22:40:10.612  6667  6667 E Zygote  : MountEmulatedStorage(),
08-30 22:40:10.612  6667  6667 E Zygote  : v2
08-30 22:40:10.612  6667  6667 I libpersona: KNOX_SDCARD checking this for 10113
08-30 22:40:10.612  6667  6667 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:10.612  6667  6667 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:10.612  1015  1488 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6667 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-30 22:40:10.622  5955  5955 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-30 22:40:10.622  6667  6667 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:10.622  6667  6667 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-30 22:40:10.622  1015  4135 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-30 22:40:10.622  1015  4135 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-30 22:40:10.622  1015  4135 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.622  1015  4135 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-30 22:40:10.622  1015  4135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
08-30 22:40:10.622  6081  6081 I SA      : [DM] init START
,08-30 22:40:10.632  1015  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.632  6081  6081 I SA      : [DM] This device is not a Vodafone
,08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-30 22:40:10.642  6081  6081 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-30 22:40:10.652  6667  6667 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.652  6081  6081 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
08-30 22:40:10.652  6667  6667 D ActivityThread: Added TimaKeyStore provider
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-30 22:40:10.652  5955  6681 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-30 22:40:10.652  6081  6081 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-30 22:40:10.662  6081  6081 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-30 22:40:10.672  6081  6081 I SA      : [SCU] isHaveSA() - false
,08-30 22:40:10.672  6081  6081 I SA      : support phone number id : false
08-30 22:40:10.672  6081  6081 I SA      : [DM] Supports Ref Jpn : true
,08-30 22:40:10.672  6081  6081 I SA      : [DM] init END
,08-30 22:40:10.672  6081  6081 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-30 22:40:10.682  6081  6081 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-30 22:40:10.682  6081  6081 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-30 22:40:10.682  6577  6577 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 22:40:10.692   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-30 22:40:10.692  6081  6081 I SA      : [SLFUCHKMGR] constructor called
,08-30 22:40:10.702  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 22:40:10.712  6081  6081 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-30 22:40:10.712  6081  6081 I SA      : [OR] == isSIMCardReady false ==
,08-30 22:40:10.712  6081  6081 I SA      : [SCU] == networkStateCheck == false
08-30 22:40:10.712  6081  6081 I SA      : [OR] onReceive END
,08-30 22:40:10.712  1015  1028 I ActivityManager: Killing 5906:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-30 22:40:10.722  1015  1488 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-30 22:40:10.722  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.722  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.722  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:10.722  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.722  1015  1488 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.732  1015  3002 D RCPManagerService: exchangeData() failure , invalid userId,
08-30 22:40:10.742  6688  6688 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.742  6688  6688 I libpersona: KNOX_SDCARD checking this for 10072
,08-30 22:40:10.742  6688  6688 E Zygote  : v2
08-30 22:40:10.742  6688  6688 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:10.742  6688  6688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 22:40:10.742  6688  6688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 22:40:10.742  6688  6688 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-30 22:40:10.742  6577  6577 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 22:40:10.742  6577  6577 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@898bca0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-30 22:40:10.742  6577  6577 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 22:40:10.742  6577  6577 D AndroidMusic: GMSCore installation verified
,08-30 22:40:10.742  1015  1488 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6688 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,08-30 22:40:10.752  1015  1217 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.752  1015  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 22:40:10.752  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-30 22:40:10.752  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:10.752  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.752  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:10.772  6688  6688 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.772  6577  6577 I ConfigStore: Config Database version: 1
,08-30 22:40:10.782  6688  6688 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.782  1015  4358 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.792  1015  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-30 22:40:10.802  1015  1489 I ActivityManager: Killing 5871:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-30 22:40:10.802  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 22:40:10.802  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 22:40:10.802  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
,08-30 22:40:10.802  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:10.812  1015  1503 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-30 22:40:10.812  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.812  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.812  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:10.812  1015  1503 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:10.822  6688  6688 D BadgeProvider: onCreate
,08-30 22:40:10.822  6688  6688 D BadgeProvider: DatabaseHelper
,08-30 22:40:10.822  6707  6707 E Zygote  : MountEmulatedStorage()
08-30 22:40:10.822  6707  6707 I libpersona: KNOX_SDCARD checking this for 10159
08-30 22:40:10.822  6707  6707 E Zygote  : v2
08-30 22:40:10.822  6707  6707 I libpersona: KNOX_SDCARD not a persona
08-30 22:40:10.832  6707  6707 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:10.832  6707  6707 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:10.832  6707  6707 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,08-30 22:40:10.832  1015  1503 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6707 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:40:10.832  1015  1503 I ActivityManager: Killing 5569:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-30 22:40:10.862  6707  6707 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:10.862  6707  6707 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:10.872  6688  6697 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-30 22:40:10.892  6688  6697 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-30 22:40:10.892  6688  6697 D BadgeProvider: sendNotify, [notify] : null
08-30 22:40:10.892  6688  6697 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-30 22:40:10.892  6688  6697 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 22:40:10.892  6688  6697 D BadgeProvider: update, [UpdateCount] : 1
,08-30 22:40:10.902  1477  1477 D Launcher.Model: reloadBadges entered.
,08-30 22:40:10.902  1015  4152 I ActivityManager: Killing 5922:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-30 22:40:10.902  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:10.912  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-30 22:40:10.912  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:10.912  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.912  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:10.932  3802  3802 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-30 22:40:10.932  3802  4607 I iu.UploadsManager: num queued entries: 0
,08-30 22:40:10.932  3802  4607 I iu.UploadsManager: num updated entries: 0
,08-30 22:40:10.932  3802  4607 I iu.SyncManager: NEXT; no task
,08-30 22:40:10.952   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 22:40:10.952   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:10.952  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 22:40:10.962   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 22:40:10.962   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:10.962  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 22:40:10.962   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-30 22:40:10.962   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:10.962  6577  6577 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-30 22:40:10.972  1015  1489 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-30 22:40:10.972  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-30 22:40:10.972  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:10.972  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.972  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:10.982  1015  4358 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:10.982  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-30 22:40:10.982  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:10.992  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:10.992  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:10.992   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 22:40:10.992   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:10.992  6667  6725 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 22:40:11.002   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 22:40:11.002   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:11.002  6667  6725 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 22:40:11.012  1015  4151 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:11.012   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-30 22:40:11.012   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:11.012  6667  6729 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-30 22:40:11.012  1015  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:11.022   258   536 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-30 22:40:11.022   258   536 W Vold    : Returning OperationFailed - no handler for errno 0
,08-30 22:40:11.022  1015  3002 I AudioService: getStreamVolume 3 index 0
,08-30 22:40:11.022  6667  6729 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-30 22:40:11.032  6577  6577 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-30 22:40:11.032  6577  6577 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-30 22:40:11.062  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.062  1015  4151 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-30 22:40:11.062  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.062  1015  1488 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 22:40:11.062  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 22:40:11.062  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:11.062  1015  1488 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:11.062  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:11.062  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.062  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 22:40:11.062  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.062  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:11.062  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:11.062  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:11.072  1015  1503 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:11.072  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.072  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:11.072  1015  1503 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:11.072  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:11.082  1015  4135 I ActivityManager: Killing 5940:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-30 22:40:11.082  1015  1382 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:11.102  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-30 22:40:11.102  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.102  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.102  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.102  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.112  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6734 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-30 22:40:11.112  6734  6734 E Zygote  : MountEmulatedStorage()
08-30 22:40:11.112  6734  6734 E Zygote  : v2
08-30 22:40:11.112  6734  6734 I libpersona: KNOX_SDCARD checking this for 10002
08-30 22:40:11.112  6734  6734 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:11.112  6734  6734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:11.122  6734  6734 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:11.122  6734  6734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:11.132  1015  1028 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-30 22:40:11.132  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-30 22:40:11.132  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:11.132  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:11.132  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 22:40:11.132  6577  6577 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-30 22:40:11.132  1015  4152 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-30 22:40:11.132  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 22:40:11.142  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:11.142  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:11.142  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:11.142  6734  6734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:11.142  6734  6734 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:11.172  1015  4358 I ActivityManager: Killing 5623:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-30 22:40:11.192  1015  4358 I ActivityManager: Killing 5991:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-30 22:40:11.192  1015  4358 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-30 22:40:11.202  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.202  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.202  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.202  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.212  6667  6667 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121),
,08-30 22:40:11.212  6766  6766 E Zygote  : MountEmulatedStorage()
,08-30 22:40:11.212  6766  6766 E Zygote  : v2
08-30 22:40:11.212  6766  6766 I libpersona: KNOX_SDCARD checking this for 1000
08-30 22:40:11.212  6766  6766 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:11.212  6766  6766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:11.212  1015  4358 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 22:40:11.212  6766  6766 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:11.212  1015  1489 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:11.222  6766  6766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 22:40:11.222  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:11.222  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-30 22:40:11.222  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 22:40:11.232  6766  6766 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:11.232  6766  6766 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:11.242  6667  6667 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9748-9750)
08-30 22:40:11.242  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 22:40:11.242  6667  6667 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2669a191}
,08-30 22:40:11.242  6667  6667 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-30 22:40:11.242  6667  6667 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-30 22:40:11.262  6667  6667 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-30 22:40:11.272  6667  6667 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 22:40:11.272  6667  6667 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-30 22:40:11.272  6766  6766 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-30 22:40:11.292  6667  6667 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 22:40:11.292  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-30 22:40:11.292  6667  6667 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-30 22:40:11.292  6667  6667 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-30 22:40:11.292  6667  6667 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-30 22:40:11.292  6667  6667 I Adreno-EGL: Build Date: 04/06/15 Mon
08-30 22:40:11.292  6667  6667 I Adreno-EGL: Local Branch: 
08-30 22:40:11.292  6667  6667 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-30 22:40:11.292  6667  6667 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-30 22:40:11.292  6667  6667 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-30 22:40:11.352  6667  6667 I NSApplication: Starting up...
,08-30 22:40:11.352  6667  6793 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-30 22:40:11.362  1015  4358 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-30 22:40:11.372  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.372  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-30 22:40:11.372  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.372  1015  4358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.382  1015  4358 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6798 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-30 22:40:11.382  6798  6798 E Zygote  : MountEmulatedStorage()
08-30 22:40:11.382  6798  6798 E Zygote  : v2
08-30 22:40:11.382  6798  6798 I libpersona: KNOX_SDCARD checking this for 10120
08-30 22:40:11.382  6798  6798 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:11.382  6798  6798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:11.392  1015  4358 I ActivityManager: Killing 5519:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-30 22:40:11.392  6798  6798 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:11.392  6798  6798 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-30 22:40:11.402  6766  6766 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-30 22:40:11.412  6766  6766 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-30 22:40:11.412  6766  6766 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:11.412  6798  6798 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:11.412  6798  6798 D ActivityThread: Added TimaKeyStore provider
08-30 22:40:11.412  6766  6766 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-30 22:40:11.412  6766  6766 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-30 22:40:11.412  6766  6766 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-30 22:40:11.412  1015  1217 I ActivityManager: Killing 6012:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-30 22:40:11.412  1015  3002 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 22:40:11.412  1015  3002 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:11.412  1015  3002 D SecContentProvider2: mCursor = null
,08-30 22:40:11.422  1015  3002 D WifiService: setWifiEnabled: true pid=6253, uid=10155
,08-30 22:40:11.422  1015  3002 W ActivityManager: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 22:40:11.422  1015  3002 W WifiService: Failed getting userId using ActivityManagerNative
08-30 22:40:11.422  1015  3002 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 22:40:11.422  1015  3002 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 22:40:11.422  1015  3002 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 22:40:11.422  1015  3002 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-30 22:40:11.422  1015  3002 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 22:40:11.422  1015  3002 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:11.422  1015  3002 D SettingsProvider: name = wifi_on
,08-30 22:40:11.422  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 22:40:11.442  6798  6798 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 22:40:11.752  1015  1382 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-30 22:40:11.762  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.762  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.762  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:11.762  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:11.772  6826  6826 E Zygote  : MountEmulatedStorage()
08-30 22:40:11.772  6826  6826 E Zygote  : v2
08-30 22:40:11.772  6826  6826 I libpersona: KNOX_SDCARD checking this for 10125
08-30 22:40:11.772  6826  6826 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:11.772  6826  6826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:11.782  6826  6826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 22:40:11.782  1015  1043 D Tethering: interfaceAdded wlan0
08-30 22:40:11.782  1015  1382 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6826 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-30 22:40:11.782  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:11.782  1015  1382 I ActivityManager: Killing 5977:com.google.android.apps.docs/u0a91 (adj 15): empty #31
08-30 22:40:11.782  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:11.782  1015  1128 E Tethering: No numeric data
08-30 22:40:11.792  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:40:11.792  1015  1128 D Tethering: clearTetheredNotification()
,08-30 22:40:11.792  6826  6826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:11.792  1015  1128 D Tethering: InitialState.processMessage what=4
08-30 22:40:11.792  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:11.792  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:11.792  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-30 22:40:11.792  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:11.792  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:11.792   279   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-30 22:40:11.792   279   967 D SoftapController: Softap fwReload - Ok
,08-30 22:40:11.792  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:11.792  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:11.802  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:11.802  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 22:40:11.802  1015  1128 E Tethering: No numeric data
08-30 22:40:11.802  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:40:11.802  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 22:40:11.802  1015  1128 D Tethering: clearTetheredNotification()
,08-30 22:40:11.802  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:11.802  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:11.802   307   307 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 24.420ms
,08-30 22:40:11.812  1015  1043 D Tethering: interfaceAdded p2p0
08-30 22:40:11.812  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-30 22:40:11.812   279   967 D CommandListener: Setting iface cfg
08-30 22:40:11.812   279   967 D CommandListener: Trying to bring down wlan0
,08-30 22:40:11.812   279   967 D CommandListener: Clearing all IP addresses on wlan0
08-30 22:40:11.812  1015  1122 V NetworkStats: performPollLocked() took 14ms
08-30 22:40:11.812  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:11.812  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:11.812  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:11.812  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:11.812  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:11.812  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:11.812  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:11.812  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
08-30 22:40:11.812  1015  1122 V NetworkStats: performPollLocked() took 3ms
,08-30 22:40:11.812  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:11.822  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:11.822  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:11.822  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-30 22:40:11.822   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 17.194ms
,08-30 22:40:11.832  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 22:40:11.832  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 22:40:11.832  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:11.832  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:11.832  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:11.832  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:11.832  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:11.832  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-30 22:40:11.832  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 22:40:11.832  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:11.832  1173  1173 D HotspotTile: onReceive : 2, 0
,08-30 22:40:11.832  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:11.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:11.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:11.842   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 17.036ms
,08-30 22:40:11.852  6826  6826 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:11.852  6826  6826 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:11.862  6835  6835 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 22:40:11.862  6835  6835 I wpa_supplicant: Successfully initialized wpa_supplicant
08-30 22:40:11.862  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 22:40:11.872  6826  6826 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
08-30 22:40:11.872  6826  6826 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 22:40:11.872  6826  6826 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:40:11.882  6826  6826 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:11.882  6826  6826 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-30 22:40:11.892  6826  6826 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-30 22:40:11.892  1015  1027 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-30 22:40:11.892  1015  1027 I ActivityManager: Killing 6119:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
08-30 22:40:11.892  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-30 22:40:11.892  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:11.892  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:11.892   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6835
08-30 22:40:11.892   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-30 22:40:11.892  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 22:40:11.892  6835  6835 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:11.892  6835  6835 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 22:40:11.892  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-30 22:40:11.892  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:11.892  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:11.892  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:11.892   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6835
08-30 22:40:11.892   403   403 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
08-30 22:40:11.902  3655  3655 I Hs20UtilService: Starting #11
,08-30 22:40:11.902  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:11.902  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 22:40:11.902  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:11.902  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:11.902  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:11.912  1015  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:11.912  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:11.912  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:11.912  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:11.912  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:11.912  3655  3655 I Hs20UtilService: Starting #12
,08-30 22:40:11.922  3655  3699 I Hs20UtilService: Message received 5011
08-30 22:40:11.922  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 22:40:11.922  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:11.922  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:11.922  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:12.032   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-30 22:40:12.052  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-30 22:40:12.112  6835  6835 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-30 22:40:12.112  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 22:40:12.122  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-30 22:40:12.122   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835,
08-30 22:40:12.122   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-30 22:40:12.122  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-30 22:40:12.122  6835  6835 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:12.122  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 22:40:12.122  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:12.122  6835  6835 E wpa_supplicant: SIM READ ERROR
08-30 22:40:12.122  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:12.122  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:12.122  6835  6835 E wpa_supplicant: SIM READ ERROR
08-30 22:40:12.122  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 22:40:12.132  6835  6835 I wpa_supplicant: wpa_default_ap_write_once
08-30 22:40:12.132  6835  6835 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 22:40:12.132  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 22:40:12.132  6835  6835 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 22:40:12.132  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:12.132  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:12.132  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 22:40:12.132  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:12.132  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:12.132  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:12.242  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-30 22:40:12.412  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 22:40:12.412  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-30 22:40:12.422  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 22:40:12.422   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835,
08-30 22:40:12.422   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 22:40:12.432  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-30 22:40:12.432  6835  6835 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:12.432  6835  6835 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-30 22:40:12.432  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-30 22:40:12.442  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-30 22:40:12.442   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835
08-30 22:40:12.442   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 22:40:12.442  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-30 22:40:12.442  6835  6835 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:12.442  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 22:40:12.442  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:12.442  6835  6835 E wpa_supplicant: SIM READ ERROR
08-30 22:40:12.452  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 22:40:12.442  6835  6835 I wpa_supplicant: wpa_default_ap_write_once
08-30 22:40:12.442  6835  6835 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 22:40:12.442  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-30 22:40:12.442  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:12.442  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:12.452  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:12.452  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:12.452  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-30 22:40:12.492  6835  6835 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-30 22:40:12.492  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 22:40:12.582  6835  6835 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-30 22:40:12.582  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-30 22:40:12.582  6835  6835 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 22:40:12.592  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-30 22:40:12.592  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 22:40:12.592  6835  6835 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-30 22:40:12.602  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 22:40:12.602  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:12.602  6835  6835 E wpa_supplicant: SIM READ ERROR,
08-30 22:40:12.602  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,08-30 22:40:12.632  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 22:40:12.642  6835  6835 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-30 22:40:12.642  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:12.642  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:12.642  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:12.642  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:12.642  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:12.642  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:12.652  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
08-30 22:40:12.652  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-30 22:40:12.652  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:12.652  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:12.652  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3),
08-30 22:40:12.652  1173  1173 D HotspotTile: onReceive : 3, 0
08-30 22:40:12.652  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-30 22:40:12.652  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-30 22:40:12.652  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:12.662  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:12.662  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:12.662  1015  4151 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 22:40:12.662  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:12.662  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:12.662  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:12.662  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:12.662  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:40:12.662  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:12.662  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:12.662  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-30 22:40:12.662  1015  1125 E WifiConfigStore: Not a HS20
,08-30 22:40:12.672  3655  3655 I Hs20UtilService: Starting #13
,08-30 22:40:12.672  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-30 22:40:12.672  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:12.672  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 22:40:12.672  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 22:40:12.672  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-30 22:40:12.672  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:12.672  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:12.672  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-30 22:40:12.672  6835  6835 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 22:40:12.672  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 22:40:12.672  6835  6835 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 22:40:12.672  6835  6835 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 22:40:12.672  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 22:40:12.672  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 22:40:12.672  6835  6835 I wpa_supplicant: First Scan Start
,08-30 22:40:12.672  6835  6835 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 22:40:12.682  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-30 22:40:12.682  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 22:40:12.682  1015  1125 I WifiNative-HAL: startHal
08-30 22:40:12.682  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c4a888c
08-30 22:40:12.682  1015  1125 I WifiNative-HAL: Could not start hal
,08-30 22:40:12.682  6500  6500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:12.682  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 22:40:12.682  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 22:40:12.682  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 22:40:12.682  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-30 22:40:12.682  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:12.682  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 22:40:12.682  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 22:40:12.682  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 22:40:12.692  1015  1149 I WifiNative-HAL: startHal
08-30 22:40:12.692  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 22:40:12.692  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 22:40:12.692  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 22:40:12.692  1015  1015 D RttService: SCAN_AVAILABLE : 3
,08-30 22:40:12.692  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 22:40:12.692   279   967 D CommandListener: Setting iface cfg
08-30 22:40:12.692   279   967 D CommandListener: Trying to bring up p2p0
,08-30 22:40:12.692  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 22:40:12.692  1015  1124 D WifiP2pService: P2pEnablingState
08-30 22:40:12.692  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 22:40:12.692  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 22:40:12.692  1015  1150 D RttService: DefaultState got{ when=-3ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:12.692  1015  1124 D WifiP2pService: P2p socket connection successful
08-30 22:40:12.692  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:12.692  1015  1124 D WifiP2pService: P2pEnabledState
08-30 22:40:12.692  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 22:40:12.692  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-30 22:40:12.692  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-30 22:40:12.692  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-30 22:40:12.692  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dc2a9bc
,08-30 22:40:12.692  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:12.692  1015  1149 I WifiNative-HAL: Could not start hal
08-30 22:40:12.692  1015  1046 D WifiDisplayController: disconnect
08-30 22:40:12.692  1015  1149 E WifiScanningService: could not start HAL
08-30 22:40:12.692  1015  1046 D WifiDisplayController: updateConnection
,08-30 22:40:12.692  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:12.692  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:12.692  1015  1125 D SecContentProvider2: mCursor = null
08-30 22:40:12.692  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 22:40:12.692  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-30 22:40:12.692  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-30 22:40:12.692  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 22:40:12.692  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 22:40:12.702  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 22:40:12.702  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-30 22:40:12.702  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 22:40:12.702  1015  4135 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 22:40:12.702  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-30 22:40:12.702   289   289 E SMD     : DCD OFF
,08-30 22:40:12.702  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-30 22:40:12.702  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 22:40:12.702  1015  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-30 22:40:12.702  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 22:40:12.702  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  secondary type: null
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  wps: 0
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  grpcapab: 0
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  devcapab: 0
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  status: 3
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  wfdInfo: null
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-30 22:40:12.702  1015  1046 D WifiDisplayController:  SConnectInfo : null
08-30 22:40:12.702  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:12.702  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:12.712  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 22:40:12.712  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:12.712  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:12.712  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:12.712  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:12.712  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 22:40:12.712  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 22:40:12.722  6485  6485 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:12.732  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 22:40:12.732  1015  1124 D WifiP2pService: InactiveState
,08-30 22:40:12.732  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-30 22:40:12.732  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 22:40:12.732  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-30 22:40:12.732  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-30 22:40:12.732  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 22:40:12.782  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 22:40:12.782  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:12.782  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
,08-30 22:40:13.882  6835  6835 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
,08-30 22:40:13.882  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 22:40:13.892  1015  6847 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-30 22:40:13.892  6835  6835 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-30 22:40:13.892  6835  6835 I wpa_supplicant: Trying to associate with  'G700'
,08-30 22:40:13.892  6835  6835 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-30 22:40:13.892  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-30 22:40:13.912  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:13.912  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:14.012  6835  6835 E wpa_supplicant: Cmd 35605 not handled
,08-30 22:40:14.012  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.012  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.012  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:14.022  6835  6835 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
08-30 22:40:14.022  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 22:40:14.022  6835  6835 I wpa_supplicant: Associated with F4.99.3E,
08-30 22:40:14.022  6835  6835 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 22:40:14.022  6835  6835 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
08-30 22:40:14.022  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:14.022  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.022  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.022  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:14.022  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.022  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.022  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:14.022  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-30 22:40:14.022  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-30 22:40:14.022  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 22:40:14.032  1015  1128 E Tethering: No numeric data
,08-30 22:40:14.032  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:40:14.032  1015  1128 D Tethering: clearTetheredNotification()
,08-30 22:40:14.032  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:14.032  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 22:40:14.032  1015  1125 D SecContentProvider2: mCursor = null
08-30 22:40:14.032  6835  6835 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 22:40:14.032  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:14.032  6835  6835 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-30 22:40:14.032  6835  6835 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 22:40:14.032  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:14.032  6835  6835 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:40:14.032  6835  6835 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 22:40:14.032  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:14.032  6835  6835 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 22:40:14.032  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:14.042  1173  1173 D HotspotTile: updateTetherState():false, false
08-30 22:40:14.042  6835  6835 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 22:40:14.042  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:14.042  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 22:40:14.042  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 22:40:14.042  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-30 22:40:14.042  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-30 22:40:14.042  1015  1122 V NetworkStats: performPollLocked() took 11ms
08-30 22:40:14.042  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:14.052  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:14.052  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:14.052  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:14.052  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:14.052  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 22:40:14.062  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 22:40:14.062  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 22:40:14.062  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 22:40:14.062  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:14.062  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 22:40:14.062  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:14.062  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:14.062  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.062  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.062  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.062  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.072  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:14.072  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:14.072  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:14.072  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:14.072  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:14.072  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:14.082  3655  3655 I Hs20UtilService: Starting #14
,08-30 22:40:14.082  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:14.082  1015  1489 I ActivityManager: Killing 6137:com.samsung.helphub/1000 (adj 15): empty #31
,08-30 22:40:14.092  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:14.092  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:14.092  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:14.092  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 22:40:14.092  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-30 22:40:14.092  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 22:40:14.092  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:14.092  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:14.102   279   967 D CommandListener: Setting iface cfg
,08-30 22:40:14.102  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-30 22:40:14.102  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 22:40:14.102  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:14.112  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 22:40:14.112  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-30 22:40:14.112  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 22:40:14.112  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 22:40:14.112  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.112  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.122  1015  1125 E WifiNative-wlan0: do suspend false
,08-30 22:40:14.122  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 22:40:14.122  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:14.122  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:14.122  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 22:40:14.342  6855  6855 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 22:40:14.352  6855  6855 I dhcpcd  : version 5.5.6 starting,
,08-30 22:40:14.352  6855  6855 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-30 22:40:14.412  6855  6855 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-30 22:40:14.412  6855  6855 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 22:40:14.412  6855  6855 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-30 22:40:14.412  6855  6855 I dhcpcd  : bssid match
08-30 22:40:14.412  6855  6855 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-30 22:40:14.422  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 22:40:14.422  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:14.422  1015  1027 D SecContentProvider2: mCursor = null
,08-30 22:40:14.432  1015  1027 D WifiService: setWifiEnabled: false pid=6253, uid=10155
,08-30 22:40:14.432  1015  1027 D SettingsProvider: name = wifi_on
,08-30 22:40:14.432  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:14.452  1015  1125 E WifiNative-wlan0: do suspend true,
,08-30 22:40:14.462  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 22:40:14.472  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 22:40:14.472   279   967 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:40:14.472  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:14.472  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:14.472  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.472  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.472  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.472  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:14.472  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.472  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 22:40:14.472  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:14.482  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,08-30 22:40:14.482   279   967 E Netd    : no such netId 503,
,08-30 22:40:14.482  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,08-30 22:40:14.482  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-30 22:40:14.482  6855  6855 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-30 22:40:14.482  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '74 network destroy 503' failed with '400 74 destroyNetwork() failed (Machine is not on the network)'
,08-30 22:40:14.482  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-30 22:40:14.482  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-30 22:40:14.482  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:14.492  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-30 22:40:14.482  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-30 22:40:14.492  1015  6853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:14.492  1015  6853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-30 22:40:14.492  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-30 22:40:14.492  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-30 22:40:14.492  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-30 22:40:14.492  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:14.502  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:14.502  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:14.502  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.502  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.502  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.502  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.502  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-30 22:40:14.502  1015  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:14.502  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-30 22:40:14.502  1015  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:40:14.512  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:40:14.512  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-30 22:40:14.512  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 22:40:14.512  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-30 22:40:14.522  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:14.522  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:14.522  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:14.522  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:14.522  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:14.522  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-30 22:40:14.522  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:14.522  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-30 22:40:14.522  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-30 22:40:14.522  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:14.522  1015  1046 D WifiDisplayController: disconnect
08-30 22:40:14.522  1015  1046 D WifiDisplayController: updateConnection
08-30 22:40:14.522  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:14.522  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:14.522  1015  1124 D WifiP2pService: P2pDisablingState
,08-30 22:40:14.522  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-30 22:40:14.532  3655  3655 I Hs20UtilService: Starting #15
08-30 22:40:14.532  1015  1124 D WifiP2pService: p2p socket connection lost
,08-30 22:40:14.532  1015  1125 E WifiNative-wlan0: do suspend true
08-30 22:40:14.532  1015  1124 D WifiP2pService: P2pDisabledState
,08-30 22:40:14.532  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:14.532  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-30 22:40:14.532  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-30 22:40:14.532  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-30 22:40:14.532  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 22:40:14.532  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-30 22:40:14.532  1015  4135 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:14.532  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 22:40:14.542  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 22:40:14.542  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:14.542  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 22:40:14.542  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 22:40:14.542  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:14.542  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:14.542  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:14.552  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-30 22:40:14.552  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-30 22:40:14.562  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-30 22:40:14.562  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:14.562   279   967 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:40:14.562  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 22:40:14.562  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:14.562  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:14.562  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.562  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.562  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.562  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.562  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:14.562  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:14.562  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:14.562  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:14.562  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:14.572  6835  6835 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-30 22:40:14.572  6855  6855 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-30 22:40:14.572  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:14.572  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:14.572  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.572  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.572  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.572  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.582  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
,08-30 22:40:14.592  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 22:40:14.592  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:14.592  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-30 22:40:14.592  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
08-30 22:40:14.592  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:14.592  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 22:40:14.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:14.592  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:14.592  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:14.592  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:14.592  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-30 22:40:14.592  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 22:40:14.592  1173  1173 D HotspotTile: onReceive : 0, 0
,08-30 22:40:14.592  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:14.592  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:40:14.592  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:14.592  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:14.592  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:14.592  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:40:14.592  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:14.592  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:14.602  6485  6485 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-30 22:40:14.602  1015  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:14.602  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:14.602  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:14.602  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:14.602  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:14.612  3655  3655 I Hs20UtilService: Starting #16
08-30 22:40:14.612  3655  3699 I Hs20UtilService: Message received 5007
08-30 22:40:14.612  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:14.612  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-30 22:40:14.612  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-30 22:40:14.612  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:14.612  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:14.612  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:14.612  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-30 22:40:14.622  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:14.622  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:14.622  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:14.622  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:14.622  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:14.622  3655  3655 I Hs20UtilService: Starting #17
08-30 22:40:14.622  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:14.632  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 22:40:14.642  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:14.642  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:14.642  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:14.772  6835  6835 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 22:40:14.882  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-30 22:40:14.882  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-30 22:40:14.882  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
08-30 22:40:14.882  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-30 22:40:14.912  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.912  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.912  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.912  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.912  1015  1128 D Tethering: InitialState.processMessage what=4
08-30 22:40:14.912  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:14.912  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.912  1015  1128 E Tethering: No numeric data
08-30 22:40:14.922  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:14.912  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:40:14.912  1015  1128 D Tethering: clearTetheredNotification()
08-30 22:40:14.922  6835  6835 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-30 22:40:14.922  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:14.922  1015  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-30 22:40:14.922  6835  6835 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-30 22:40:14.922  6835  6835 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-30 22:40:14.922  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:14.922  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:14.922  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-30 22:40:14.922  1173  1173 D HotspotTile: updateTetherState():false, false
08-30 22:40:14.922  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:14.922  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-30 22:40:14.922  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-30 22:40:14.922  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:14.922  1015  1122 V NetworkStats: performPollLocked() took 9ms
08-30 22:40:14.922  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:14.922  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:14.932  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:14.932  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:15.012  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 22:40:15.012  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:15.012  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:15.322  6835  6835 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 22:40:15.402  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 22:40:15.402  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:15.402  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:15.402  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-30 22:40:15.512  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-30 22:40:15.512  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
,08-30 22:40:15.512  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-30 22:40:15.522  6500  6500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:15.522  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:15.522  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
08-30 22:40:15.522  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:15.522  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 22:40:15.522  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:15.522  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-30 22:40:15.522  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-30 22:40:15.522  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 22:40:15.522  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-30 22:40:15.532  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:15.532  1932  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:15.532  1173  1173 D HotspotTile: onReceive : 1, 0
,08-30 22:40:15.532  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:15.532  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:15.542  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:15.542  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 22:40:15.542  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-30 22:40:15.542  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:15.542  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:15.542  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:15.542  3655  3655 I Hs20UtilService: Starting #18
,08-30 22:40:15.542  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:15.552  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 22:40:15.552  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:15.552  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:15.552  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:15.702   289   289 E SMD     : DCD OFF,
,08-30 22:40:16.152   279   961 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-30 22:40:16.152  1015  1043 D Tethering: interfaceRemoved wlan0
,08-30 22:40:16.152  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-30 22:40:16.162  1015  1489 I art     : Explicit concurrent mark sweep GC freed 73813(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.487ms total 163.094ms
08-30 22:40:16.162  1015  1489 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-30 22:40:16.162  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-30 22:40:16.162  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:16.162  1015  1489 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.162  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-30 22:40:16.172  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:16.172  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.172  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.172  6667  6727 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-30 22:40:16.182  1015  1217 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 22:40:16.182  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-30 22:40:16.182  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.182  1015  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.182  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.192  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.192  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:16.192  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.202  1015  4358 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:16.202  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-30 22:40:16.202  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.202  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.202  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.202  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:16.202  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-30 22:40:16.212  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.212  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.212  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.212  1015  2973 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:16.212  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 22:40:16.212  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.212  1015  2973 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.212  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.222  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-30 22:40:16.222  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-30 22:40:16.222  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.222  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.222  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.262  1015  4152 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:16.262  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.262  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.262  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-30 22:40:16.272  1932  1932 D WearableService: callingUid 10012, callindPid: 1932
,08-30 22:40:16.272  1015  1382 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-30 22:40:16.272  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-30 22:40:16.282  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:16.282  1015  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:16.282  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-30 22:40:16.282  1015  1043 D Tethering: interfaceRemoved p2p0
,08-30 22:40:16.282  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-30 22:40:16.282  6577  6886 I MusicLeanback: Conditions not met for autocaching.
08-30 22:40:16.282  6577  6886 I MusicLeanback: Stop autocaching.
,08-30 22:40:16.302  6577  6577 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 22:40:16.312  6577  6891 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-30 22:40:17.142  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-30 22:40:17.442  6253  6307 D BluetoothAdapter: enable()
,08-30 22:40:17.442  1015  4135 W ActivityManager: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 22:40:17.452  1015  4135 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 22:40:17.452  1015  4135 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:17.452  1015  4135 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.452  1015  4135 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.452  1015  4135 D SettingsProvider: name = bluetooth_on,
,08-30 22:40:17.462  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.462  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.472  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-30 22:40:17.472  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 22:40:17.522  6543  6543 D BluetoothAdapterState: make
,08-30 22:40:17.522  6543  6543 I bluedroid: init
,08-30 22:40:17.532  6543  6893 I BluetoothAdapterState: Entering OffState
,08-30 22:40:17.532  6543  6543 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-30 22:40:17.532  6543  6543 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-30 22:40:17.532  6543  6543 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-30 22:40:17.532  6543  6543 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-30 22:40:17.532  6543  6543 E bt-btif : btif_fetch_local_ble_random_bdaddr,
,08-30 22:40:17.532  6543  6543 I bluedroid: get_profile_interface socket
08-30 22:40:17.532  6543  6543 I bluedroid: get_profile_interface map_client
,08-30 22:40:17.542  6543  6896 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-30 22:40:17.542  6543  6543 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 22:40:17.542  6543  6896 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-30 22:40:17.542  6543  6896 E BluetoothServiceJni: populateRssiValuesNative
08-30 22:40:17.542  6543  6896 I bluedroid: getModelRssiValues
08-30 22:40:17.542  6543  6896 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 22:40:17.542  6543  6896 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 22:40:17.542  6543  6896 D BluetoothAdapterProperties: Name is: A5-1
,08-30 22:40:17.542  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 22:40:17.542  6543  6543 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:17.552  1015  4152 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 22:40:17.552  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.552  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.552  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.552  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.552  6543  6552 I bluedroid: config_hci_snoop_log
,08-30 22:40:17.552  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 22:40:17.562  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-30 22:40:17.562  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 22:40:17.562  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 22:40:17.562  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 22:40:17.562  6543  6543 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 22:40:17.572  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.572  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:17.582  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 22:40:17.582  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 22:40:17.592  6543  6893 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 22:40:17.592  6543  6893 D BluetoothAdapterProperties: Setting state to 11
,08-30 22:40:17.592  6543  6893 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 22:40:17.592  6543  6893 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:17.592  6543  6893 D BluetoothAdapterService: updateAdapterState state is 11
,08-30 22:40:17.602  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:17.602  6543  6893 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:17.602  6543  6893 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 22:40:17.602  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-30 22:40:17.602  6543  6893 D BluetoothSecureManager: getInstant: null
08-30 22:40:17.602  6543  6893 D BluetoothSecureManager: calling getMethod for getService
08-30 22:40:17.602  6543  6893 D BluetoothSecureManager: calling getService
,08-30 22:40:17.602  6543  6893 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@279c51d3
,08-30 22:40:17.602  1015  1503 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 22:40:17.602  1015  1503 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-30 22:40:17.602  6543  6893 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 22:40:17.602  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 22:40:17.602  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 22:40:17.602  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:17.602  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 22:40:17.602  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService,
08-30 22:40:17.602  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:17.612  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 22:40:17.612  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:17.612  1173  1173 D BluetoothTile:  getBluetoothState : 11
,08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService,
08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 22:40:17.612  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 22:40:17.612  1769  1769 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 22:40:17.612  1015  3002 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:17.612  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-30 22:40:17.612  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-30 22:40:17.612  6543  6893 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 22:40:17.612  1015  1488 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 22:40:17.612  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:17.622  6543  6893 D BluetoothBondStateMachine: make
,08-30 22:40:17.622  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:17.622  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-30 22:40:17.622  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 22:40:17.622  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 22:40:17.622  6543  6898 I BluetoothBondStateMachine: StableState(): Entering Off State
08-30 22:40:17.622  1015  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:17.622  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.622  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.622  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:17.622  1015  1476 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:17.622  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:17.622  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:17.632  1015  4152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.632  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.632  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.632  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.632  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.632  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 22:40:17.632  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 22:40:17.632  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:17.632  6543  6543 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 22:40:17.632  6543  6543 D BtGatt.GattService: Received start request. Starting profile...
08-30 22:40:17.632  6543  6543 D BtGatt.GattService: start()
08-30 22:40:17.632  6543  6543 D BtGatt.GattService: start()
08-30 22:40:17.632  6543  6543 I bluedroid: get_profile_interface gatt
,08-30 22:40:17.632  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:17.632  6543  6543 D BtGatt.AdvertiseManager: advertise manager created
,08-30 22:40:17.632  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:17.642  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.642  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.642  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.642  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.642  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.642  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:17.642  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 22:40:17.652  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 22:40:17.652  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 22:40:17.652  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:17.652  1015  4151 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:17.652  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.652  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.652  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.652  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.652  1015  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 22:40:17.652  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 22:40:17.652  1015  1133 D BatteryService: level:63, scale:100, status:2, health:2, present:true, voltage: 3940, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-30 22:40:17.652  1015  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 22:40:17.652  1015  1133 D BatteryService: stay LED for charging
,08-30 22:40:17.662  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-30 22:40:17.662  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:17.662  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 22:40:17.662  1015  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.662  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.662  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.662  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:17.662  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 22:40:17.662  6543  6543 D BtGatt.GattService: mStartError = false
08-30 22:40:17.662  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:17.662  6543  6543 D HeadsetService: Received start request. Starting profile...
,08-30 22:40:17.662  6543  6543 D HeadsetService: start()
08-30 22:40:17.662  6543  6543 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-30 22:40:17.662  6543  6543 D HeadsetStateMachine: make
08-30 22:40:17.662  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 22:40:17.662  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 22:40:17.662  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 22:40:17.672  6543  6543 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 22:40:17.672  1015  1015 I MotionRecognitionService: Plugged
08-30 22:40:17.672  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 22:40:17.672  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-30 22:40:17.672  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 63
,08-30 22:40:17.672  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 22:40:17.672  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 22:40:17.682  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
08-30 22:40:17.682  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:17.682  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
08-30 22:40:17.682  1015  2973 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 22:40:17.682  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.682  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.682  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.682  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-30 22:40:17.682  1015  4358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:17.682  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.682  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.682  1015  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.682  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.692  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-30 22:40:17.692  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 22:40:17.692  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 22:40:17.692  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.692  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.692  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.692  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 22:40:17.692  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 22:40:17.692  6543  6543 I bluedroid: get_profile_interface handsfree
,08-30 22:40:17.702  1015  4135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.702  1015  4135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.712  1015  4135 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.712  1015  4135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.712  1015  4135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.712  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 22:40:17.712  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:17.712  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:17.712  1015  2973 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.712  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.712  6543  6543 I DualScoManager: Instantiating Dual Sco Manager
08-30 22:40:17.712  6543  6543 I DualScoManager: Set HeadsetServiceHelper
,08-30 22:40:17.712  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:17.712  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.712  6543  6543 D BluetoothAtMessage: createCMTIContentObservers
,08-30 22:40:17.712  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.712  1015  1488 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-30 22:40:17.712  1015  1488 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:17.712  1015  1488 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:17.712  1015  1488 D SettingsProvider: selectionArgs: false
08-30 22:40:17.712  1015  1488 D SettingsProvider: selectionArgs: 1002
08-30 22:40:17.712  1015  1488 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:17.712  1015  1488 D SettingsProvider: ret = -1
,08-30 22:40:17.712  6543  6903 D HeadsetStateMachine: Enter Disconnected: -2
,08-30 22:40:17.722  6543  6543 D HeadsetService: mStartError = false
08-30 22:40:17.722  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:17.722  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 22:40:17.722  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 22:40:17.722  6543  6893 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 22:40:17.722  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:17.722  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 22:40:17.722  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:17.722  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:17.722  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:17.722  6543  6903 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-30 22:40:17.722  6543  6903 D HeadsetStateMachine: map size, before remove : 0
,08-30 22:40:17.722  6543  6903 D HeadsetStateMachine: map size, after remove: 0
08-30 22:40:17.732  6543  6543 D A2dpService: Received start request. Starting profile...
08-30 22:40:17.732  6543  6543 D A2dpService: start()
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:17.732  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:17.732  6543  6543 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-30 22:40:17.732  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:17.732  6543  6543 I bluedroid: get_profile_interface avrcp
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:17.732  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 22:40:17.732  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 22:40:17.732  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 22:40:17.732  6543  6893 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 22:40:17.742  6543  6543 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 22:40:17.752  6543  6543 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 22:40:17.752  6543  6907 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 22:40:17.752  6543  6543 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:40:17.752  6543  6543 D A2dpStateMachine: make
,08-30 22:40:17.752  6543  6543 I bluedroid: get_profile_interface a2dp
08-30 22:40:17.762  6543  6909 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 22:40:17.762  6543  6543 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 22:40:17.762  6543  6543 D A2dpService: mStartError = false
08-30 22:40:17.762  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:17.762  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 22:40:17.762  6543  6908 D A2dpStateMachine: Enter Disconnected: -2
08-30 22:40:17.762  6543  6543 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 22:40:17.762  6543  6543 D HidService: Received start request. Starting profile...
08-30 22:40:17.762  6543  6543 D HidService: start()
08-30 22:40:17.762  6543  6543 I bluedroid: get_profile_interface hidhost
08-30 22:40:17.762  6543  6543 D HidService: setHidService(): set to: null
08-30 22:40:17.762  6543  6543 D HidService: mStartError = false
08-30 22:40:17.762  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:17.762  6543  6543 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 22:40:17.762  1430  1442 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 22:40:17.762  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-30 22:40:17.762  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 22:40:17.772  1430  1442 I Telecom : BluetoothPhoneService: Result of Message : true
08-30 22:40:17.772  6543  6543 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 22:40:17.772  6543  6543 D HealthService: Received start request. Starting profile...
08-30 22:40:17.772  6543  6543 D HealthService: start()
,08-30 22:40:17.772  6543  6907 D BluetoothMediaBrowser: no now playing list
,08-30 22:40:17.772  6543  6907 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 22:40:17.772  6543  6543 I bluedroid: get_profile_interface health
08-30 22:40:17.772  6543  6543 D HealthService: mStartError = false
08-30 22:40:17.772  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:17.772  6543  6543 D HeadsetStateMachine: Proxy object connected
,08-30 22:40:17.772  6543  6543 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-30 22:40:17.772  6543  6543 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-30 22:40:17.772  6543  6903 D HeadsetStateMachine: Disconnected process message: 11
08-30 22:40:17.772  6543  6543 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-30 22:40:17.772  6543  6543 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-30 22:40:17.772  6543  6903 D HeadsetStateMachine: Disconnected process message: 18
,08-30 22:40:17.772  6543  6543 D PanService: Received start request. Starting profile...
,08-30 22:40:17.772  6543  6543 D PanService: start()
,08-30 22:40:17.782  6543  6543 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 22:40:17.782  6543  6543 I bluedroid: get_profile_interface pan
,08-30 22:40:17.782  6543  6543 D PanService: mStartError = false
08-30 22:40:17.782  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:17.782  6543  6543 D BluetoothMapService: Received start request. Starting profile...
08-30 22:40:17.782  6543  6543 D BluetoothMapService: start()
,08-30 22:40:17.782  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:17.792  6543  6543 D BluetoothMapService: mStartError = false
08-30 22:40:17.792  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:17.792  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 22:40:17.792  6543  6543 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 22:40:17.792  6543  6903 D HeadsetStateMachine: Disconnected process message: 10
,08-30 22:40:17.792  6543  6903 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-30 22:40:17.792  6543  6903 D HeadsetStateMachine: Disconnected process message: 11
08-30 22:40:17.792  6543  6543 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-30 22:40:17.792  6543  6543 D BluetoothA2dp: Proxy object connected
08-30 22:40:17.792  6543  6543 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-30 22:40:17.792  6543  6543 D SapService: Received start request. Starting profile...
08-30 22:40:17.792  6543  6543 D SapService: start()
08-30 22:40:17.792  6543  6543 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 22:40:17.792  6543  6543 I bluedroid: get_profile_interface sap
08-30 22:40:17.792  6543  6543 D SapService: mStartError = false
08-30 22:40:17.792  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:17.792  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 22:40:17.792  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-30 22:40:17.792  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:17.802  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 22:40:17.802  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-30 22:40:17.822  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-30 22:40:17.822  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 22:40:17.832  6543  6893 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-30 22:40:17.832  6543  6893 I bluedroid: enable
,08-30 22:40:17.832  6543  6893 I bt_hci_bdroid: init
,08-30 22:40:17.832  6543  6913 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 22:40:17.832  6543  6893 I bt_vendor: bt-vendor : init
08-30 22:40:17.832  6543  6893 I bt_vendor: bt-vendor : get_bt_soc_type
08-30 22:40:17.832  6543  6893 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 22:40:17.832  6543  6893 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-30 22:40:17.832  6543  6893 D bt_userial_mct: userial_init
,08-30 22:40:17.832  6543  6893 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-30 22:40:17.832  6543  6893 I bt_vendor: Starting hciattach daemon
08-30 22:40:17.832  6543  6893 I bt_vendor: try to set false
,08-30 22:40:17.832  6543  6893 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-30 22:40:17.832  6543  6893 I bt_vendor: Starting hciattach daemon
08-30 22:40:17.832  6543  6893 I bt_vendor: try to set true
,08-30 22:40:17.852  6917  6917 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 22:40:17.912  6923  6923 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 22:40:17.922  6924  6924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 22:40:17.932  6926  6926 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 22:40:17.942  6927  6927 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 22:40:17.952  6928  6928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 22:40:17.962  6929  6929 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 22:40:18.212  6932  6932 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 22:40:18.222  6933  6933 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 22:40:18.242  6543  6893 I bt_vendor: bluetooth satus is on
,08-30 22:40:18.242  6543  6915 D bt_userial_mct: userial_open(port:0)
08-30 22:40:18.242  6543  6915 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-30 22:40:18.242  6543  6915 I bt_vendor: Done intiailizing UART
,08-30 22:40:18.242  6543  6915 I bt_vendor: Done intiailizing UART,
08-30 22:40:18.242  6543  6915 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-30 22:40:18.242  6543  6915 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
,08-30 22:40:18.252  6543  6935 D bt_userial_mct: Entering userial_read_thread(),
,08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_HCI
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_RFCOMM,
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_BNEP
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_BTM,
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_PAN
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_SAP
,08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_SDP
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_SMP,
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 22:40:18.252  6543  6913 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 22:40:18.352  6543  6913 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 22:40:18.362  6543  6913 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3efb6e9 
,08-30 22:40:18.362  6543  6913 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3efb6e9 
,08-30 22:40:18.382  6543  6896 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 22:40:18.382  6543  6896 E bt-btif : Calling BTA_HhEnable
,08-30 22:40:18.382  6543  6896 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-30 22:40:18.392  6543  6896 E BluetoothServiceJni: populateRssiValuesNative
08-30 22:40:18.392  6543  6896 I bluedroid: getModelRssiValues
08-30 22:40:18.392  6543  6896 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: Name is: A5-1
,08-30 22:40:18.392  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 22:40:18.392  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:18.392  6543  6896 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: Scan Mode:20
08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: Discoverable Timeout:120
08-30 22:40:18.392  6543  6896 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-30 22:40:18.392  6543  6896 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 22:40:18.392  6543  6896 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-30 22:40:18.392  6543  6896 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 22:40:18.392  6543  6896 E bt-btif : btif_sock_init: !vhci_init
08-30 22:40:18.392  6543  6896 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 22:40:18.392  6543  6896 D IOP_DB_BT: db_open: db_open : handle 3027689488l, read 13894 bytes onto local cache
08-30 22:40:18.392  6543  6896 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 22:40:18.402  6543  6896 D IOP_DB_BT: db_query: result 1
,08-30 22:40:18.402  6543  6896 I         : iop_db_open: iop_db_open status 0
08-30 22:40:18.402  6543  6896 D bte_conf: Device ID record 1 : primary
08-30 22:40:18.402  6543  6896 D bte_conf:   vendorId            = 0075
,08-30 22:40:18.402  6543  6896 D bte_conf:   vendorIdSource      = 0001
08-30 22:40:18.402  6543  6896 D bte_conf:   product             = 0100
08-30 22:40:18.402  6543  6896 D bte_conf:   version             = 0200
08-30 22:40:18.402  6543  6896 D bte_conf:   clientExecutableURL = 
,08-30 22:40:18.402  6543  6896 D bte_conf:   serviceDescription  = 
08-30 22:40:18.402  6543  6896 D bte_conf:   documentationURL    = 
08-30 22:40:18.402  6543  6896 D bte_conf: bte_load_did_conf no section named DID2.
08-30 22:40:18.402  6543  6896 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 22:40:18.402  6543  6893 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 22:40:18.402  6543  6893 D BluetoothAdapterProperties: ScanMode =  20
08-30 22:40:18.402  6543  6893 D BluetoothAdapterProperties: State =  11
,08-30 22:40:18.402  1015  1382 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 22:40:18.402  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:18.402  6543  6893 D BluetoothAdapterProperties: Setting state to 12
,08-30 22:40:18.402  6543  6893 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-30 22:40:18.412  6543  6896 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 22:40:18.412  6543  6896 D BluetoothAdapterProperties: Scan Mode:21
08-30 22:40:18.412  6543  6896 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 22:40:18.412  6543  6935 E bt_mct  : hci lib postload completed
,08-30 22:40:18.412  1015  3002 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-30 22:40:18.412  1015  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:18.412  1015  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:18.412  1015  3002 D SettingsProvider: selectionArgs: false
08-30 22:40:18.412  1015  3002 D SettingsProvider: selectionArgs: 1002
08-30 22:40:18.412  1015  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:18.412  1015  3002 D SettingsProvider: ret = -1
,08-30 22:40:18.412  6543  6893 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-30 22:40:18.412  6543  6893 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:18.422  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:18.422  1015  4152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:18.422  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.422  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.422  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.422  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.422  1015  1045 D BluetoothPan: Binding service...
,08-30 22:40:18.422  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 22:40:18.422  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.422  6543  6893 D BluetoothAdapterService: Autoconnection is available 
,08-30 22:40:18.422  6543  6893 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-30 22:40:18.422  6543  6893 D BluetoothAdapterService: starting service from this receiver
,08-30 22:40:18.432  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:18.432  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.432  1430  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.432  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.432  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.432  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.432  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:18.432  6543  6893 I BluetoothAdapterState: Entering On State from state = 11
,08-30 22:40:18.442  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 22:40:18.442  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.442  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.442  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.442  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.442  1430  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.442  6253  6261 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:18.442  6253  6261 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.442  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:18.442  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.452  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:18.452  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:18.452  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:40:18.452  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:18.452  1015  1015 D BluetoothA2dp: Proxy object connected
,08-30 22:40:18.452  1291  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.452  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-30 22:40:18.452  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.452  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:18.462  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.462  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.462  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 22:40:18.462  6543  6543 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 22:40:18.462  6543  6899 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-30 22:40:18.462  6543  6899 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:18.462  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-30 22:40:18.462  1291  1300 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:18.462  1291  1300 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:18.462  2876  6463 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:18.462  2876  6463 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.472  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:18.472  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.472  1291  1291 D BluetoothA2dp: Proxy object connected
,08-30 22:40:18.472  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.472  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.472  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-30 22:40:18.472  1291  1291 D A2dpProfile: Bluetooth service connected
,08-30 22:40:18.472  2876  2876 D BluetoothA2dp: Proxy object connected
08-30 22:40:18.472  6425  6439 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:18.472  6425  6439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.472  1291  1306 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 22:40:18.482  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-30 22:40:18.482  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.482  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.482  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.482  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.482  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.482  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:18.482  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.482  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.482  6543  6543 I BluetoothPbapService: Handler(): got msg=1
,08-30 22:40:18.482  1460  1688 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:18.482  1460  1688 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.482  2876  2884 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:18.482  2876  2884 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.482  1460  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.492  1015  1489 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 22:40:18.492  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:18.492  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.492  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.492  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.492  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.492  1460  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.492  1291  1291 D BluetoothInputDevice: Proxy object connected
,08-30 22:40:18.492  1430  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.492  1291  1291 D HidProfile: Bluetooth service connected
,08-30 22:40:18.502  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:18.502  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.502  6543  6940 V BluetoothPbapService: PBAP Service initSocket try: 0
08-30 22:40:18.502  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.502  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.502  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.502  1430  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.502  6543  6940 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:18.502  1291  6938 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.502  6543  6940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-30 22:40:18.502  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:18.502  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.502  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.502  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.502  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.512  1291  6938 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.512  1291  1300 D BluetoothPan: Binding service...
,08-30 22:40:18.512  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-30 22:40:18.512  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 22:40:18.512  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-30 22:40:18.512  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.512  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.512  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.512  6543  6940 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-30 22:40:18.512  1932  2110 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:18.512  1932  2110 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.512  6543  6940 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:18.512  6543  6940 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 22:40:18.512  6543  6940 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f809c07
08-30 22:40:18.512  6543  6940 D BluetoothSocket: channel: 19
08-30 22:40:18.512  6543  6940 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-30 22:40:18.512  1291  6938 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 22:40:18.512  1291  6938 D Bluetoothsap: Binding service...
,08-30 22:40:18.512  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:40:18.512  1291  1291 D PanProfile: Bluetooth service connected
,08-30 22:40:18.512  1291  6938 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-30 22:40:18.512  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-30 22:40:18.522  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.522  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.522  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.522  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.522  1291  6938 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 22:40:18.522  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:18.522  1441  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:18.522  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
08-30 22:40:18.522  1291  1291 D SapProfile: Bluetooth service connected
08-30 22:40:18.522  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-30 22:40:18.522  6543  6899 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:18.522  2876  2887 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.522  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 22:40:18.522  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.532  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.532  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.532  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.532  2876  2887 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.532  1430  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:18.532  1430  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.532  1430  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:18.532  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:18.532  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:18.532  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.532  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:18.532  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.532  1430  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:18.532  1291  1306 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 22:40:18.532  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 22:40:18.532  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.542  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.542  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.542  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.542  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:18.542  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.542  1291  6938 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 22:40:18.542  1291  1291 D BluetoothPbap: Proxy object connected
,08-30 22:40:18.542  1291  1291 D PbapServerProfile: Bluetooth service connected
,08-30 22:40:18.542  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 22:40:18.542  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.542  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.542  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.542  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.542  1173  2332 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:18.542  1173  2332 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:18.542  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 22:40:18.542  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 22:40:18.542  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:18.552  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,08-30 22:40:18.552  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 22:40:18.552  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-30 22:40:18.552  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1d0e2722, true
,08-30 22:40:18.562  1430  1430 D BluetoothHeadset: registerMessageListener
08-30 22:40:18.562  1291  1291 D BluetoothMap: Proxy object connected
08-30 22:40:18.562  1291  1291 D MapProfile: Bluetooth service connected
08-30 22:40:18.562  1291  1291 D BluetoothMap: getConnectedDevices()
,08-30 22:40:18.562  1769  1769 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 22:40:18.562  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 22:40:18.562  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:18.562  1173  1173 D BluetoothTile:  getBluetoothState : 12
,08-30 22:40:18.562  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:18.562  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:18.562  1015  4151 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:18.562  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.562  6543  6899 D HeadsetService: registerMessageListener
,08-30 22:40:18.562  6543  6899 D HeadsetService: registerMessageListener
,08-30 22:40:18.562  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 22:40:18.562  6543  6903 D HeadsetStateMachine: Disconnected process message: 70
08-30 22:40:18.562  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 22:40:18.572  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:18.572  6543  6903 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@db6c134
,08-30 22:40:18.572  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.572  1015  4151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:18.572  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-30 22:40:18.572  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:18.572  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-30 22:40:18.572  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 22:40:18.572  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-30 22:40:18.572  1015  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:18.572  1015  3002 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 22:40:18.582  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:18.582  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 22:40:18.582  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
08-30 22:40:18.582  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 22:40:18.582  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 22:40:18.582  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-30 22:40:18.582  6543  6903 D HeadsetStateMachine: Disconnected process message: 9
08-30 22:40:18.582  6543  6903 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-30 22:40:18.582  6543  6944 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-30 22:40:18.582  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:18.592   284   812 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 22:40:18.592   284   812 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-30 22:40:18.592   284   812 V voice   : voice_set_parameters: exit with code(-2)
08-30 22:40:18.592   284   812 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-30 22:40:18.592   284   812 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 22:40:18.592   284   812 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-30 22:40:18.592   284   812 V audio_hw_primary: adev_set_parameters: exit
,08-30 22:40:18.592  6543  6903 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate,
08-30 22:40:18.592  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:18.592  1015  1489 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 22:40:18.592  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.592  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.592  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.592  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 22:40:18.592  6543  6944 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:18.592  6543  6944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:40:18.602  6543  6944 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-30 22:40:18.602  6543  6944 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:18.602  6543  6944 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 22:40:18.602  6543  6944 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27e64b5d
,08-30 22:40:18.602  6543  6944 D BluetoothSocket: channel: 5
,08-30 22:40:18.602  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:18.612  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:18.612  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:18.612  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 22:40:18.622  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:18.622  6543  6543 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 22:40:18.622  1015  4358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:18.622  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.622  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.622  1015  4358 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:18.622  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:18.632  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:18.632  1015  4151 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:18.642  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 22:40:18.642  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.642  1015  4151 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:18.642  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:18.652  1015  2973 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,08-30 22:40:18.652  1932  6951 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 22:40:18.652  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:18.662  1015  4135 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:18.662  1015  4135 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:18.662  1015  4135 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:18.662  1015  4135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:18.662  6543  6954 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:18.662  6543  6954 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:40:18.672  6543  6954 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 22:40:18.672  6543  6954 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:18.672  6543  6954 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 22:40:18.672  6543  6954 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36414059
08-30 22:40:18.672  6543  6954 D BluetoothSocket: channel: 12
08-30 22:40:18.672  6543  6954 I BtOppRfcommListener: Accept thread started.
,08-30 22:40:18.672  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:18.672  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:18.682  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:18.682  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:18.682  1932  6951 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 22:40:18.702   289   289 E SMD     : DCD OFF
,08-30 22:40:18.762  1015  2770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 22:40:19.832  1015  2735 D SSRM:n  : SIOP:: AP = 330
,08-30 22:40:20.082  1015  1340 E Watchdog: !@Sync 4,
,08-30 22:40:20.472  6253  6307 D BluetoothAdapter: disable()
,08-30 22:40:20.472  1015  4358 D SettingsProvider: name = bluetooth_on
,08-30 22:40:20.482  6543  6893 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-30 22:40:20.482  6543  6893 D BluetoothAdapterProperties: Setting state to 13
08-30 22:40:20.482  6543  6893 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-30 22:40:20.482  6543  6893 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:20.482  6543  6893 D BluetoothAdapterService: updateAdapterState state is 13
,08-30 22:40:20.482  1015  4152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:20.482  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 22:40:20.482  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:20.482  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:20.482  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:20.492  6543  6893 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:20.492  6543  6893 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-30 22:40:20.492  6543  6893 D BluetoothAdapterService: terminating service from this receiver
,08-30 22:40:20.492  6543  6543 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-30 22:40:20.492  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1939b41e, channel: 19, state: LISTENING
08-30 22:40:20.492  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-30 22:40:20.492  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1939b41e, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f809c07, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3fa704ffmSocket: android.net.LocalSocket@19dd02cc impl:android.net.LocalSocketImpl@fbc8915 fd:FileDescriptor[75]
,08-30 22:40:20.492  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19dd02cc impl:android.net.LocalSocketImpl@fbc8915 fd:FileDescriptor[75]
08-30 22:40:20.492  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:20.492  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:20.492  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:20.492  6543  6893 D BluetoothAdapterProperties: onBluetoothDisable(),
08-30 22:40:20.492  6543  6893 D BluetoothAdapterProperties: mDiscovering is false
,08-30 22:40:20.492  1015  4135 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
,08-30 22:40:20.492  6543  6893 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-30 22:40:20.502  1291  1291 D BluetoothPbap: Proxy object disconnected
,08-30 22:40:20.502  1291  1291 D PbapServerProfile: Bluetooth service disconnected
,08-30 22:40:20.512  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:20.512  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 22:40:20.512  6543  6896 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 22:40:20.512  6543  6896 D BluetoothAdapterProperties: Scan Mode:20
,08-30 22:40:20.512  6543  6893 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-30 22:40:20.512  6543  6893 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-30 22:40:20.512  6543  6893 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-30 22:40:20.512  6543  6893 E bt-btif : cmd socket is not created
08-30 22:40:20.512  6543  6954 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-30 22:40:20.512  6543  6893 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-30 22:40:20.512  6543  6913 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-30 22:40:20.512  6543  6913 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-30 22:40:20.512  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:20.512  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:20.512  6543  6913 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-30 22:40:20.512  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:20.512  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:20.522  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:20.522  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:20.522  6253  6253 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-30 22:40:20.522  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:20.532  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:20.532  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-30 22:40:20.542  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-30 22:40:20.542  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 22:40:20.542  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:20.542  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:20.542  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:20.552  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-30 22:40:20.552  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:20.552  1769  1769 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 22:40:20.552  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:20.552  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 22:40:20.552  1015  3002 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 22:40:20.552  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:20.552  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1bf0f21b, channel: 5, state: LISTENING
,08-30 22:40:20.552  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1bf0f21b, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27e64b5d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2b3d7fb8mSocket: android.net.LocalSocket@2669a191 impl:android.net.LocalSocketImpl@115a28f6 fd:FileDescriptor[77]
08-30 22:40:20.552  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2669a191 impl:android.net.LocalSocketImpl@115a28f6 fd:FileDescriptor[77]
,08-30 22:40:20.562  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:20.562  6543  6543 I BtOppRfcommListener: stopping Accept Thread
08-30 22:40:20.562  6543  6543 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2294f7, channel: 12, state: LISTENING
08-30 22:40:20.562  6543  6543 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2294f7, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36414059, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@626df64mSocket: android.net.LocalSocket@21f5c5cd impl:android.net.LocalSocketImpl@2177de82 fd:FileDescriptor[80]
08-30 22:40:20.562  6543  6543 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@21f5c5cd impl:android.net.LocalSocketImpl@2177de82 fd:FileDescriptor[80]
,08-30 22:40:20.562  6543  6954 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-30 22:40:20.562  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:20.562  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:20.562  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-30 22:40:20.562  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:20.562  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:20.562  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:20.562  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:20.572  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:20.572  6543  6543 V BluetoothOppManager: cleanUp...
,08-30 22:40:20.572  1015  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 22:40:20.572  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 22:40:20.582  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:20.582  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:20.582  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 22:40:20.592  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:20.592  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:20.592  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:20.602  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-30 22:40:20.622  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:20.632  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:20.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-30 22:40:20.712  6543  6913 W bt-btif : ag scb idx 1 not allocated
08-30 22:40:20.712  6543  6913 W bt-btif : ag scb idx 2 not allocated
08-30 22:40:20.712  6543  6913 E bt-btif : BTA AG is already disabled, ignoring ...
,08-30 22:40:20.712  6543  6935 I bt_userial_mct: exiting userial_read_thread
08-30 22:40:20.712  6543  6935 D bt_userial_mct: Leaving userial_evt_read_thread()
08-30 22:40:20.712  6543  6896 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-30 22:40:20.712  6543  6915 I bt_vendor: hw_epilog_process
08-30 22:40:20.712  6543  6896 D bt_userial_mct: userial_close
08-30 22:40:20.712  6543  6896 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-30 22:40:21.082  6543  6896 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 22:40:21.082  6543  6896 I bt_vendor: bluetooth satus is on
,08-30 22:40:21.082  6543  6896 I bt_vendor: bt-vendor : resetting BT status
08-30 22:40:21.082  6543  6896 I bt_vendor: Starting hciattach daemon
,08-30 22:40:21.082  6543  6896 I bt_vendor: try to set false
,08-30 22:40:21.082  6543  6896 I bt_vendor: Starting hciattach daemon,
08-30 22:40:21.082  6543  6896 I bt_vendor: try to set false
,08-30 22:40:21.082  6543  6896 I bt_vendor: cleanup,
,08-30 22:40:21.082  6543  6913 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,08-30 22:40:21.082  6543  6896 I GKI_LINUX: GKI_exit_task 0 done
,08-30 22:40:21.082  6543  6896 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-30 22:40:21.092  6543  6893 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-30 22:40:21.092  6543  6893 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 22:40:21.092  6543  6893 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-30 22:40:21.092  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 22:40:21.092  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 22:40:21.092  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-30 22:40:21.092  1015  1382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-30 22:40:21.092  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
,08-30 22:40:21.092  1015  1382 W ActivityManager: userId = 0, bbcId = -10000,
08-30 22:40:21.092  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.092  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-30 22:40:21.102  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:21.102  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 22:40:21.102  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:21.102  6543  6543 D BtGatt.DebugUtils: handleDebugAction() action=null
08-30 22:40:21.102  1015  4151 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:21.102  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.102  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.102  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:21.102  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 22:40:21.102  6543  6543 D BtGatt.GattService: Received stop request...Stopping profile...
08-30 22:40:21.102  6543  6543 D BtGatt.GattService: stop()
,08-30 22:40:21.102  6543  6543 D BtGatt.AdvertiseManager: advertise clients cleared
08-30 22:40:21.102  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 22:40:21.102  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:21.102  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:21.102  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
08-30 22:40:21.102  1015  1217 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:21.102  1015  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.102  1015  1217 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:21.102  1015  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:21.102  1015  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 22:40:21.112  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 22:40:21.112  1015  4135 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:21.112  1015  4135 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.112  6543  6543 D HeadsetService: Received stop request...Stopping profile...
,08-30 22:40:21.112  1015  4135 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:21.112  1015  4135 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.112  1015  4135 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-30 22:40:21.112  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 22:40:21.112  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:21.112  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.112  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.112  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:21.112  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-30 22:40:21.112  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-30 22:40:21.112  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 22:40:21.122  1015  1489 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:21.122  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.122  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.122  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:21.122  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.122  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.122  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.122  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.122  6543  6893 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:21.122  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-30 22:40:21.122  1291  1291 D HeadsetProfile: Bluetooth service disconnected
08-30 22:40:21.122  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:21.122  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.122  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:21.122  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.122  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.122  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-30 22:40:21.122  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 22:40:21.132  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:21.132  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.132  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.132  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.132  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:21.132  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:21.132  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 22:40:21.132  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-30 22:40:21.132  6543  6893 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 22:40:21.132  6543  6893 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 22:40:21.132  6543  6893 D BluetoothAdapterState: Stopping profile services that were post enabled
08-30 22:40:21.132  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-30 22:40:21.132  6543  6543 D A2dpService: Received stop request...Stopping profile...
08-30 22:40:21.132  6543  6908 D A2dpStateMachine: Exit Disconnected: -1
,08-30 22:40:21.132  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.142  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:21.142  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-30 22:40:21.142  1291  1291 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:21.142  1291  1291 D A2dpProfile: Bluetooth service disconnected
,08-30 22:40:21.142  2876  2876 D BluetoothA2dp: Proxy object disconnected
,08-30 22:40:21.142  6543  6543 D HidService: Received stop request...Stopping profile...
,08-30 22:40:21.142  6543  6543 D HidService: Stopping Bluetooth HidService
08-30 22:40:21.142  6543  6543 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-30 22:40:21.142  6543  6543 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-30 22:40:21.142  6543  6543 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-30 22:40:21.142  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.142  6543  6543 D HealthService: Received stop request...Stopping profile...
,08-30 22:40:21.142  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.142  1291  1291 D BluetoothInputDevice: Proxy object disconnected
08-30 22:40:21.142  1291  1291 D HidProfile: Bluetooth service disconnected
,08-30 22:40:21.152  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-30 22:40:21.152  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:21.152  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-30 22:40:21.152  6543  6543 D PanService: Received stop request...Stopping profile...
08-30 22:40:21.152  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.152  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-30 22:40:21.152  1291  1291 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-30 22:40:21.152  6543  6543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-30 22:40:21.152  6543  6543 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-30 22:40:21.152  1291  1291 D PanProfile: Bluetooth service disconnected
08-30 22:40:21.152  6543  6543 D BluetoothMapService: Received stop request...Stopping profile...
,08-30 22:40:21.152  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.162  6543  6543 D SapService: Received stop request...Stopping profile...
08-30 22:40:21.162  6543  6543 D SapService: Stopping Bluetooth SapService
08-30 22:40:21.162  1291  1291 D BluetoothMap: Proxy object disconnected
08-30 22:40:21.162  1291  1291 D MapProfile: Bluetooth service disconnected
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@14d2cd6a
,08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-30 22:40:21.162  6543  6543 D BluetoothA2dp: Proxy object disconnected
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-30 22:40:21.162  6543  6909 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-30 22:40:21.162  6543  6543 I GKI_LINUX: GKI_exit_task 2 done
08-30 22:40:21.162  6543  6543 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-30 22:40:21.162  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-30 22:40:21.162  1291  1291 D SapProfile: Bluetooth service disconnected
08-30 22:40:21.162  6543  6543 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:21.162  6543  6543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-30 22:40:21.162  6543  6543 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 22:40:21.162  6543  6543 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-30 22:40:21.162  6543  6543 E BluetoothAdapterService(349359466): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-30 22:40:21.162  6543  6543 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-30 22:40:21.162  6543  6543 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-30 22:40:21.162  6543  6893 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-30 22:40:21.162  6543  6893 D BluetoothAdapterProperties: Setting state to 10
08-30 22:40:21.162  6543  6893 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-30 22:40:21.162  6543  6893 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:21.162  6543  6893 D BluetoothAdapterService: updateAdapterState state is 10
,08-30 22:40:21.162  6543  6893 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:21.162  6543  6893 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-30 22:40:21.162  6543  6893 I BluetoothAdapterState: Entering OffState
08-30 22:40:21.162  6253  6261 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.162  6253  6261 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:21.162  6253  6261 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-30 22:40:21.162  6253  6261 D BluetoothLeAdvertiser: Exit stop advertising
08-30 22:40:21.162  6253  6261 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-30 22:40:21.162  6253  6261 D BluetoothLeScanner: Exiting stopAllScan
08-30 22:40:21.162  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-30 22:40:21.162  1291  6938 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 22:40:21.172  6543  6552 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 22:40:21.172  6543  6552 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  1291  1300 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.172  1291  1300 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  2876  6463 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 22:40:21.172  6425  6433 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.172  6425  6433 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  1291  1306 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-30 22:40:21.172  1460  1690 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.172  1460  1690 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  2876  2887 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.172  2876  2887 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  1932  2115 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 22:40:21.172  1932  2115 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.172  1291  1306 D Bluetoothsap: onBluetoothStateChange: up=false
08-30 22:40:21.172  1291  1306 D Bluetoothsap: Unbinding service...
,08-30 22:40:21.182  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=false
08-30 22:40:21.182  1441  1457 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.182  6543  6899 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1430  6941 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1430  6941 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.182  1291  6938 D BluetoothPbap: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-30 22:40:21.182  1291  1300 D BluetoothMap: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1173  2984 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-30 22:40:21.182  1173  2984 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-30 22:40:21.182  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-30 22:40:21.192  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 22:40:21.192  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:21.192  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-30 22:40:21.192  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 22:40:21.202  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:21.202  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-30 22:40:21.202  1173  1700 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:21.202  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:21.202  1173  1173 D BluetoothTile:  getBluetoothState : 10
,08-30 22:40:21.202  1173  1700 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:21.202  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:21.202  1173  1173 D BluetoothAdapter: 714043509: getState() :  mService = null. Returning STATE_OFF
08-30 22:40:21.202  1015  1488 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:21.202  1769  1769 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 22:40:21.202  1015  2973 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 22:40:21.202  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:21.202  1932  2125 D BluetoothAdapter: 141158976: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:21.202  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:21.202  1932  2125 D BluetoothAdapter: 141158976: getState() :  mService = null. Returning STATE_OFF
,08-30 22:40:21.212  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:21.212  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:21.212  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:21.212  1015  1382 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:21.212  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.212  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:21.212  1015  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:21.212  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:21.212  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:21.222  1015  1488 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 22:40:21.222  6543  6896 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-30 22:40:21.222  6543  6543 I GKI_LINUX: GKI_exit_task 1 done
08-30 22:40:21.222  6543  6543 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-30 22:40:21.222  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.222  6543  6543 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-30 22:40:21.222  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.222  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:21.222  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-30 22:40:21.222  6543  6543 I art     : System.exit called, status: 0
08-30 22:40:21.222  6543  6543 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-30 22:40:21.232  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:21.232  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:21.232  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:21.232  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-30 22:40:21.342  1015  1476 I ActivityManager: Process com.android.bluetooth (pid 6543)(adj 0) has died(62,1092)
,08-30 22:40:21.362  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:21.362  1015  4358 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:21.362  1015  4358 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 22:40:21.362  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.362  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:21.362  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:21.372  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:21.382  1932  6970 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 22:40:21.382  1015  3002 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:21.382  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:21.382  1015  3002 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:21.382  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:21.392  1932  6970 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-30 22:40:21.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:21.712   289   289 E SMD     : DCD OFF,
,08-30 22:40:22.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:23.482  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop,
08-30 22:40:23.482  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:23.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:24.292  1015  1973 V SAMP_SPCM_test: CSC File load.. 
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time,
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming,
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi,
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account,
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-30 22:40:24.302  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email,
08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn,
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-30 22:40:24.342  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-30 22:40:24.352  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn,
08-30 22:40:24.352  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-30 22:40:24.362  1015  1973 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-30 22:40:24.372  1015  1973 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-30 22:40:24.692   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 22:40:24.712   289   289 E SMD     : DCD OFF
,08-30 22:40:25.692   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-30 22:40:26.482  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 22:40:26.482  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@95cee9 added. We now have 6 listener(s)
,08-30 22:40:26.482  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:26.482  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 22:40:26.482  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@160a476e added. We now have 7 listener(s)
,08-30 22:40:26.482  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:26.492  6253  6307 I System.out: IsBluetoothEnabled
,08-30 22:40:26.492  6253  6307 D BluetoothAdapter: disable()
,08-30 22:40:26.492  1015  4152 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-30 22:40:26.492  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:26.492  6253  6307 D BluetoothAdapter: enable()
,08-30 22:40:26.502  1015  1488 W ActivityManager: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS,
,08-30 22:40:26.502  1015  1488 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-30 22:40:26.502  1015  1488 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:26.502  1015  1488 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-30 22:40:26.502  1015  1488 D SettingsProvider: name = bluetooth_on
08-30 22:40:26.502  1015  1488 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:26.512  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:26.512  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:26.512  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-30 22:40:26.512  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-30 22:40:26.512  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:26.512  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:26.512  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:26.512  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:26.532  6976  6976 E Zygote  : MountEmulatedStorage(),
08-30 22:40:26.532  6976  6976 E Zygote  : v2
08-30 22:40:26.532  6976  6976 I libpersona: KNOX_SDCARD checking this for 1002
08-30 22:40:26.532  6976  6976 I libpersona: KNOX_SDCARD not a persona,
08-30 22:40:26.532  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6976 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-30 22:40:26.542  6976  6976 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-30 22:40:26.542  6976  6976 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 22:40:26.552  6976  6976 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:26.572  6976  6976 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:26.572  6976  6976 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:26.582  6976  6976 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-30 22:40:26.582  6976  6976 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:40:26.602  6976  6976 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding GattService
,08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding HeadsetService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding A2dpService
,08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding HidService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding HealthService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding PanService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding SapService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding SapClientService
08-30 22:40:26.632  6976  6976 D BtSettings.ProfileConfig: Adding HidDevService
,08-30 22:40:26.632  6976  6976 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-30 22:40:26.632  1015  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-30 22:40:26.642  1015  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:26.642  1015  1133 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  1133 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:26.642  1015  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.642  1015  1133 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  1503 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-30 22:40:26.642  1015  1503 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-30 22:40:26.642  1015  1503 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.642  1015  1503 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  1503 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.642  1015  1503 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.642  1015  1503 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  1489 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-30 22:40:26.642  1015  1489 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  1489 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:26.642  1015  1489 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  1489 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.642  1015  1489 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.642  1015  1489 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  4358 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-30 22:40:26.642  1015  4358 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  4358 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.642  1015  4358 D SettingsProvider: selectionArgs: false
,08-30 22:40:26.642  1015  4358 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.642  1015  4358 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:26.642  1015  4358 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  3002 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-30 22:40:26.642  1015  3002 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  3002 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.642  1015  3002 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  3002 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.642  1015  3002 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.642  1015  3002 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  4151 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-30 22:40:26.642  1015  4151 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  4151 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.642  1015  4151 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  4151 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.642  1015  4151 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.642  1015  4151 D SettingsProvider: ret = -1
,08-30 22:40:26.642  1015  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-30 22:40:26.642  1015  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.642  1015  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.642  1015  1217 D SettingsProvider: selectionArgs: false
08-30 22:40:26.642  1015  1217 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:26.652  1015  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.652  1015  1217 D SettingsProvider: ret = -1
,08-30 22:40:26.652  1015  1027 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-30 22:40:26.652  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.652  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.652  1015  1027 D SettingsProvider: selectionArgs: false
08-30 22:40:26.652  1015  1027 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.652  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.652  1015  1027 D SettingsProvider: ret = -1
,08-30 22:40:26.652  1015  1382 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:26.652  1015  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.652  1015  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.652  1015  1382 D SettingsProvider: selectionArgs: false
08-30 22:40:26.652  1015  1382 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.652  1015  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.652  1015  1382 D SettingsProvider: ret = -1
,08-30 22:40:26.652  1015  4152 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:26.652  1015  4152 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.652  1015  4152 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-30 22:40:26.652  1015  4152 D SettingsProvider: selectionArgs: false
08-30 22:40:26.652  1015  4152 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.652  1015  4152 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.652  1015  4152 D SettingsProvider: ret = -1
08-30 22:40:26.652  1015  2973 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:26.652  1015  2973 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.652  1015  2973 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.652  1015  2973 D SettingsProvider: selectionArgs: false
08-30 22:40:26.652  1015  2973 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.652  1015  2973 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:26.652  1015  2973 D SettingsProvider: ret = -1
08-30 22:40:26.652  1015  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-30 22:40:26.652  1015  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.652  1015  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-30 22:40:26.652  1015  1476 D SettingsProvider: selectionArgs: false
08-30 22:40:26.652  1015  1476 D SettingsProvider: selectionArgs: 1002
08-30 22:40:26.652  1015  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-30 22:40:26.652  1015  1476 D SettingsProvider: ret = -1
,08-30 22:40:26.662  6976  6976 D BluetoothAdapterState: make,
,08-30 22:40:26.672  6976  6976 I bluedroid: init
08-30 22:40:26.672  6976  6991 I BluetoothAdapterState: Entering OffState
,08-30 22:40:26.672  6976  6976 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
08-30 22:40:26.672  6976  6976 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-30 22:40:26.672  6976  6976 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-30 22:40:26.672  6976  6976 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-30 22:40:26.672  6976  6976 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-30 22:40:26.672  6976  6976 I bluedroid: get_profile_interface socket
,08-30 22:40:26.672  6976  6976 I bluedroid: get_profile_interface map_client
,08-30 22:40:26.672  6976  6994 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-30 22:40:26.672  6976  6976 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-30 22:40:26.682  6976  6994 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 22:40:26.682  6976  6994 E BluetoothServiceJni: populateRssiValuesNative
08-30 22:40:26.682  6976  6994 I bluedroid: getModelRssiValues
08-30 22:40:26.682  6976  6994 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-30 22:40:26.682  6976  6994 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 22:40:26.682  1015  1015 D SettingsProvider: name = bluetooth_name
08-30 22:40:26.682  6976  6994 D BluetoothAdapterProperties: Name is: A5-1
,08-30 22:40:26.682  6976  6976 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:26.692  1015  1382 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:26.692  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.692  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:26.692  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:26.692  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.692  6976  6984 I bluedroid: config_hci_snoop_log
,08-30 22:40:26.692  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-30 22:40:26.702  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-30 22:40:26.702  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-30 22:40:26.702  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-30 22:40:26.702  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-30 22:40:26.712  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:26.712  6976  6976 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-30 22:40:26.712  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-30 22:40:26.712  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-30 22:40:26.712  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-30 22:40:26.712  6976  6991 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-30 22:40:26.712  6976  6991 D BluetoothAdapterProperties: Setting state to 11
08-30 22:40:26.712  6976  6991 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-30 22:40:26.722  6976  6991 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:26.722  6976  6991 D BluetoothAdapterService: updateAdapterState state is 11
08-30 22:40:26.722  6976  6991 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:26.722  6976  6991 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-30 22:40:26.722  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:26.722  1015  1015 I InputMethodManagerService: [BT Setting State] State =11,
,08-30 22:40:26.722  6976  6991 D BluetoothSecureManager: getInstant: null
08-30 22:40:26.722  6976  6991 D BluetoothSecureManager: calling getMethod for getService
08-30 22:40:26.722  6976  6991 D BluetoothSecureManager: calling getService
08-30 22:40:26.722  6976  6991 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3456c40d
,08-30 22:40:26.722  1015  1503 D BluetoothSecureManagerService: isSecureModeEnabled
08-30 22:40:26.722  1015  1503 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-30 22:40:26.722  6976  6991 D BtConfig.SecureMode: isSecureModeOn:false
08-30 22:40:26.722  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-30 22:40:26.722  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-30 22:40:26.722  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-30 22:40:26.722  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-30 22:40:26.722  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 22:40:26.732  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-30 22:40:26.732  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:26.732  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-30 22:40:26.732  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-30 22:40:26.732  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 22:40:26.732  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-30 22:40:26.732  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 22:40:26.732  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:26.732  1173  1173 D BluetoothTile:  getBluetoothState : 11
,08-30 22:40:26.732  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-30 22:40:26.732  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:26.732  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:26.742  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-30 22:40:26.742  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-30 22:40:26.742  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-30 22:40:26.742  1015  4358 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:26.742  1769  1769 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-30 22:40:26.742  6976  6991 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-30 22:40:26.742  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-30 22:40:26.742  1015  2973 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-30 22:40:26.742  6976  6991 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:26.742  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-30 22:40:26.742  6976  6991 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:26.742  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-30 22:40:26.742  6976  6991 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-30 22:40:26.742  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-30 22:40:26.742  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:26.752  6976  6991 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-30 22:40:26.752  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:26.752  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:26.752  1015  4152 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:26.752  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.752  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:26.752  1015  4152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-30 22:40:26.762  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:26.762  6976  6991 D BluetoothBondStateMachine: make
,08-30 22:40:26.762  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-30 22:40:26.772  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
08-30 22:40:26.772  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-30 22:40:26.772  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-30 22:40:26.772  6976  6995 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-30 22:40:26.772  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-30 22:40:26.772  1015  2973 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:26.772  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.772  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:26.772  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:26.772  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.772  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-30 22:40:26.772  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.772  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-30 22:40:26.772  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-30 22:40:26.772  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-30 22:40:26.772  6976  6976 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-30 22:40:26.772  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.772  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.772  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.782  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-30 22:40:26.782  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-30 22:40:26.782  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-30 22:40:26.782  6976  6976 D BtGatt.GattService: Received start request. Starting profile...
08-30 22:40:26.782  6976  6976 D BtGatt.GattService: start()
08-30 22:40:26.782  6976  6976 D BtGatt.GattService: start()
08-30 22:40:26.782  6976  6976 I bluedroid: get_profile_interface gatt
,08-30 22:40:26.782  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:26.782  6976  6976 D BtGatt.AdvertiseManager: advertise manager created
,08-30 22:40:26.782  1015  4151 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:26.782  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.782  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:26.782  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-30 22:40:26.792  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.792  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.792  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.792  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-30 22:40:26.802  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-30 22:40:26.802  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-30 22:40:26.802  6976  6976 D BtGatt.GattService: mStartError = false
08-30 22:40:26.802  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.802  1015  1382 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:26.802  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.802  6976  6976 D HeadsetService: Received start request. Starting profile...
,08-30 22:40:26.802  6976  6976 D HeadsetService: start()
,08-30 22:40:26.802  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.802  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:26.802  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-30 22:40:26.802  6976  6976 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-30 22:40:26.802  6976  6976 D HeadsetStateMachine: make
,08-30 22:40:26.812  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-30 22:40:26.812  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-30 22:40:26.812  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-30 22:40:26.812  1015  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-30 22:40:26.812  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.812  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:26.812  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.812  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.812  6976  6976 E HeadsetStateMachine: # of Max HF connection is 2
,08-30 22:40:26.812  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-30 22:40:26.812  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-30 22:40:26.812  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-30 22:40:26.812  1015  4152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:26.812  1015  4152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.822  1015  4152 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:26.822  1015  4152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:26.822  1015  4152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.822  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-30 22:40:26.822  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-30 22:40:26.822  6976  6991 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-30 22:40:26.822  1015  1488 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-30 22:40:26.822  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.822  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.822  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.822  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 22:40:26.822  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:26.822  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.822  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.822  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.822  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.832  1015  1133 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-30 22:40:26.832  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.832  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-30 22:40:26.832  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-30 22:40:26.832  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.832  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-30 22:40:26.832  1015  4151 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:26.832  6976  6976 I bluedroid: get_profile_interface handsfree
08-30 22:40:26.832  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 22:40:26.832  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:26.832  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:26.832  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:26.832  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:26.832  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-30 22:40:26.832  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-30 22:40:26.832  6976  6991 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-30 22:40:26.832  6976  6991 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-30 22:40:26.832  6976  6991 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-30 22:40:26.852  6976  6976 I DualScoManager: Instantiating Dual Sco Manager
,08-30 22:40:26.852  6976  6976 I DualScoManager: Set HeadsetServiceHelper
,08-30 22:40:26.852  6976  6976 D BluetoothAtMessage: createCMTIContentObservers
,08-30 22:40:26.852  1015  4135 D SettingsProvider: name = bluetooth_hfp_allowed_bvra,
08-30 22:40:26.852  1015  4135 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:26.852  1015  4135 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:26.852  1015  4135 D SettingsProvider: selectionArgs: false
08-30 22:40:26.852  1015  4135 D SettingsProvider: selectionArgs: 1002
,08-30 22:40:26.852  1015  4135 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:26.852  1015  4135 D SettingsProvider: ret = -1
08-30 22:40:26.852  6976  6999 D HeadsetStateMachine: Enter Disconnected: -2
08-30 22:40:26.852  6976  6976 D HeadsetService: mStartError = false
08-30 22:40:26.852  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c,
08-30 22:40:26.852  6976  6999 D HeadsetStateMachine: Clear mHeadsetBrsf
08-30 22:40:26.852  6976  6999 D HeadsetStateMachine: map size, before remove : 0
08-30 22:40:26.852  6976  6999 D HeadsetStateMachine: map size, after remove: 0
,08-30 22:40:26.852  6976  6976 D A2dpService: Received start request. Starting profile...
,08-30 22:40:26.852  6976  6976 D A2dpService: start()
,08-30 22:40:26.862  6976  6976 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-30 22:40:26.862  6976  6976 I bluedroid: get_profile_interface avrcp
,08-30 22:40:26.862  6976  6976 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-30 22:40:26.882  6976  6976 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-30 22:40:26.882  6976  7004 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-30 22:40:26.882  6976  6976 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-30 22:40:26.882  6976  6976 D A2dpStateMachine: make
,08-30 22:40:26.882  6976  6976 I bluedroid: get_profile_interface a2dp
,08-30 22:40:26.882  6976  7006 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-30 22:40:26.882  6976  6976 E bt-btif : warning : media task started media_task_refcnt 1 
,08-30 22:40:26.882  6976  6976 D A2dpService: mStartError = false
08-30 22:40:26.882  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.882  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-30 22:40:26.882  6976  6976 I BluetoothHidServiceJni: classInitNative: succeeds
,08-30 22:40:26.892  6976  7005 D A2dpStateMachine: Enter Disconnected: -2
,08-30 22:40:26.892  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:26.892  6976  6976 D HidService: Received start request. Starting profile...
08-30 22:40:26.892  6976  6976 D HidService: start()
08-30 22:40:26.892  6976  6976 I bluedroid: get_profile_interface hidhost
08-30 22:40:26.892  6976  6976 D HidService: setHidService(): set to: null
08-30 22:40:26.892  6976  6976 D HidService: mStartError = false
08-30 22:40:26.892  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.892  6976  6976 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-30 22:40:26.902  6976  6976 D HealthService: Received start request. Starting profile...
08-30 22:40:26.902  6976  6976 D HealthService: start()
,08-30 22:40:26.902  6976  6976 I bluedroid: get_profile_interface health
,08-30 22:40:26.902  6976  6976 D HealthService: mStartError = false
08-30 22:40:26.902  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.902  6976  6976 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-30 22:40:26.902  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:26.902  6976  6976 D PanService: Received start request. Starting profile...
08-30 22:40:26.902  6976  6976 D PanService: start()
08-30 22:40:26.902  6976  6976 D BluetoothPanServiceJni: initializeNative(L110): pan
08-30 22:40:26.902  6976  6976 I bluedroid: get_profile_interface pan
,08-30 22:40:26.902  6976  6976 D PanService: mStartError = false
08-30 22:40:26.902  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.902  6976  6976 D HeadsetStateMachine: Try to query the phonestate on bind
,08-30 22:40:26.902  1430  6941 I Telecom : BluetoothPhoneService: queryPhoneState
,08-30 22:40:26.902  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-30 22:40:26.902  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-30 22:40:26.912  1430  6941 I Telecom : BluetoothPhoneService: Result of Message : true
08-30 22:40:26.912  6976  7004 D BluetoothMediaBrowser: no now playing list
08-30 22:40:26.912  6976  7004 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-30 22:40:26.912  6976  6976 D BluetoothMapService: Received start request. Starting profile...
,08-30 22:40:26.912  6976  6976 D BluetoothMapService: start()
,08-30 22:40:26.912  6976  6976 D BluetoothMapService: mStartError = false
,08-30 22:40:26.912  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
08-30 22:40:26.912  6976  6976 D HeadsetStateMachine: Proxy object connected
,08-30 22:40:26.912  6976  6976 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-30 22:40:26.912  6976  6976 D SapService: Received start request. Starting profile...
,08-30 22:40:26.922  6976  6976 D SapService: start()
08-30 22:40:26.922  6976  6976 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-30 22:40:26.922  6976  6976 I bluedroid: get_profile_interface sap
08-30 22:40:26.922  6976  6976 D SapService: mStartError = false
08-30 22:40:26.922  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:26.922  6976  6976 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-30 22:40:26.922  6976  6976 D HeadsetPhoneState: sendDeviceDataStateChanged
08-30 22:40:26.922  6976  6976 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-30 22:40:26.922  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-30 22:40:26.922  6976  6999 D HeadsetStateMachine: Disconnected process message: 11
08-30 22:40:26.922  6976  6976 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-30 22:40:26.922  6976  6976 D BluetoothA2dp: Proxy object connected
08-30 22:40:26.922  6976  6976 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-30 22:40:26.922  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-30 22:40:26.922  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-30 22:40:26.922  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-30 22:40:26.922  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-30 22:40:26.922  6976  6999 D HeadsetStateMachine: Disconnected process message: 18
08-30 22:40:26.922  6976  6999 D HeadsetStateMachine: Disconnected process message: 10
08-30 22:40:26.922  6976  6999 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
08-30 22:40:26.922  6976  6999 D HeadsetStateMachine: Disconnected process message: 11
,08-30 22:40:26.942  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-30 22:40:26.942  6976  6976 E BluetoothAdapterService(623405580): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-30 22:40:26.942  6976  6991 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-30 22:40:26.942  6976  6991 I bluedroid: enable
,08-30 22:40:26.942  6976  6991 I bt_hci_bdroid: init
,08-30 22:40:26.942  6976  7010 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-30 22:40:26.952  6976  6991 I bt_vendor: bt-vendor : init
08-30 22:40:26.952  6976  6991 I bt_vendor: bt-vendor : get_bt_soc_type
,08-30 22:40:26.952  6976  6991 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-30 22:40:26.952  6976  6991 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-30 22:40:26.952  6976  6991 D bt_userial_mct: userial_init
08-30 22:40:26.952  6976  6991 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-30 22:40:26.952  6976  6991 I bt_vendor: Starting hciattach daemon
08-30 22:40:26.952  6976  6991 I bt_vendor: try to set false
,08-30 22:40:26.952  6976  6991 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-30 22:40:26.952  6976  6991 I bt_vendor: Starting hciattach daemon
08-30 22:40:26.952  6976  6991 I bt_vendor: try to set true
,08-30 22:40:26.962  7014  7014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-30 22:40:27.022  7020  7020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-30 22:40:27.032  7021  7021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 22:40:27.042  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 22:40:27.052  7024  7024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-30 22:40:27.062  7025  7025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-30 22:40:27.072  7026  7026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-30 22:40:27.412  7029  7029 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-30 22:40:27.422  7030  7030 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-30 22:40:27.462  6976  6991 I bt_vendor: bluetooth satus is on,
08-30 22:40:27.462  6976  7012 D bt_userial_mct: userial_open(port:0)
08-30 22:40:27.462  6976  7012 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,08-30 22:40:27.462  6976  7012 I bt_vendor: Done intiailizing UART,
,08-30 22:40:27.462  6976  7012 I bt_vendor: Done intiailizing UART
08-30 22:40:27.462  6976  7012 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-30 22:40:27.462  6976  7012 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-30 22:40:27.472  6976  7032 D bt_userial_mct: Entering userial_read_thread(),
,08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_HCI
,08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_AVDT
08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_A2D
08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-30 22:40:27.472  6976  7010 I         : BTE_InitTraceLevels -- TRC_BTM
,08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_GAP
08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_PAN
,08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_SAP
08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_SDP
,08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_GATT
08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_SMP
,08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-30 22:40:27.482  6976  7010 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-30 22:40:27.582  6976  7010 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-30 22:40:27.582  6976  7010 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3efb6e9 
,08-30 22:40:27.582  6976  7010 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3efb6e9 
,08-30 22:40:27.602  6976  6994 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-30 22:40:27.612  6976  6994 E bt-btif : Calling BTA_HhEnable
,08-30 22:40:27.612  6976  6994 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-30 22:40:27.612  6976  6994 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-30 22:40:27.612  6976  6994 E BluetoothServiceJni: populateRssiValuesNative
08-30 22:40:27.612  6976  6994 I bluedroid: getModelRssiValues
,08-30 22:40:27.612  6976  6994 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-30 22:40:27.612  6976  6994 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-30 22:40:27.612  1015  1015 D SettingsProvider: name = bluetooth_name
,08-30 22:40:27.612  6976  6994 D BluetoothAdapterProperties: Name is: A5-1
,08-30 22:40:27.622  6976  6994 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-30 22:40:27.622  6976  6994 D BluetoothAdapterProperties: Scan Mode:20
08-30 22:40:27.622  6976  6994 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 22:40:27.622  6976  6994 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-30 22:40:27.622  6976  6994 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-30 22:40:27.622  6976  6994 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-30 22:40:27.622  6976  6994 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-30 22:40:27.622  6976  6994 E bt-btif : btif_sock_init: !vhci_init
,08-30 22:40:27.622  6976  6994 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-30 22:40:27.622  6976  6994 D IOP_DB_BT: db_open: db_open : handle 3027681296l, read 13894 bytes onto local cache
08-30 22:40:27.622  6976  6994 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-30 22:40:27.622  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:27.622  6976  6994 D IOP_DB_BT: db_query: result 1
08-30 22:40:27.622  6976  6994 I         : iop_db_open: iop_db_open status 0
08-30 22:40:27.622  6976  6994 D bte_conf: Device ID record 1 : primary
08-30 22:40:27.622  6976  6994 D bte_conf:   vendorId            = 0075
08-30 22:40:27.622  6976  6994 D bte_conf:   vendorIdSource      = 0001
08-30 22:40:27.622  6976  6994 D bte_conf:   product             = 0100
08-30 22:40:27.622  6976  6994 D bte_conf:   version             = 0200
08-30 22:40:27.622  6976  6994 D bte_conf:   clientExecutableURL = 
08-30 22:40:27.622  6976  6994 D bte_conf:   serviceDescription  = 
08-30 22:40:27.622  6976  6994 D bte_conf:   documentationURL    = 
08-30 22:40:27.622  6976  6994 D bte_conf: bte_load_did_conf no section named DID2.
,08-30 22:40:27.622  6976  6994 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-30 22:40:27.622  6976  6991 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-30 22:40:27.622  6976  6991 D BluetoothAdapterProperties: ScanMode =  20
,08-30 22:40:27.622  6976  6991 D BluetoothAdapterProperties: State =  11
,08-30 22:40:27.632  1015  1489 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-30 22:40:27.632  6976  6991 D BluetoothAdapterProperties: Setting state to 12,
08-30 22:40:27.632  6976  6991 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-30 22:40:27.632  6976  7032 E bt_mct  : hci lib postload completed
,08-30 22:40:27.632  6976  6994 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-30 22:40:27.632  6976  6994 D BluetoothAdapterProperties: Scan Mode:21
,08-30 22:40:27.632  6976  6994 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-30 22:40:27.632  1015  1382 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-30 22:40:27.632  1015  1382 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-30 22:40:27.632  1015  1382 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-30 22:40:27.632  1015  1382 D SettingsProvider: selectionArgs: false
08-30 22:40:27.632  1015  1382 D SettingsProvider: selectionArgs: 1002
08-30 22:40:27.632  1015  1382 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-30 22:40:27.632  1015  1382 D SettingsProvider: ret = -1
,08-30 22:40:27.632  6976  6991 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-30 22:40:27.632  6976  6991 D BluetoothAdapterService: updateAdapterState state is 12
,08-30 22:40:27.642  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:27.642  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:27.642  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:27.642  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:27.642  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.642  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.642  1015  1045 D BluetoothPan: Binding service...
,08-30 22:40:27.642  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 22:40:27.642  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.642  6976  6991 D BluetoothAdapterService: Autoconnection is available 
08-30 22:40:27.642  6976  6991 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-30 22:40:27.642  6976  6991 D BluetoothAdapterService: starting service from this receiver
,08-30 22:40:27.642  1430  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 22:40:27.642  1015  2973 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:27.642  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.652  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.652  1015  2973 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.652  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.652  6976  6991 I BluetoothAdapterState: Entering On State from state = 11
08-30 22:40:27.652  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:27.652  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.652  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.652  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.652  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-30 22:40:27.652  1430  1442 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 22:40:27.652  6253  6262 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.652  6253  6262 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:27.652  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 22:40:27.652  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.652  1015  1015 D BluetoothA2dp: Proxy object connected
08-30 22:40:27.652  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:27.652  1291  1300 D BluetoothA2dp: onBluetoothStateChange: up=true
08-30 22:40:27.652  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.662  1291  1300 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-30 22:40:27.662  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:27.682  6976  6976 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-30 22:40:27.712   289   289 E SMD     : DCD OFF
,08-30 22:40:27.722  1015  1503 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-30 22:40:27.722  1015  1503 D BatteryService: level:63, scale:100, status:2, health:2, present:true, voltage: 3922, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-30 22:40:27.732  1015  1503 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-30 22:40:27.732  1015  1503 D BatteryService: stay LED for charging
08-30 22:40:27.732  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-30 22:40:27.732  1015  1015 I MotionRecognitionService: Plugged
,08-30 22:40:27.732  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-30 22:40:27.732  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-30 22:40:27.732  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-30 22:40:27.732  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-30 22:40:27.732  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 63
,08-30 22:40:27.752  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:27.752  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:27.762  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:63 status:2 health:2
,08-30 22:40:27.812  1015  1045 I art     : Explicit concurrent mark sweep GC freed 32765(1919KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.436ms total 155.906ms
08-30 22:40:27.812  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:27.812  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.812  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.812  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.812  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.822  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:40:27.822  1291  1291 D BluetoothA2dp: Proxy object connected
08-30 22:40:27.822  1291  1291 D A2dpProfile: Bluetooth service connected
,08-30 22:40:27.822  1291  1300 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:27.822  1291  1300 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.832  2876  2887 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:27.832  2876  2887 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.832  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-30 22:40:27.832  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-30 22:40:27.832  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.832  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.832  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.832  6425  6439 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:27.832  2876  2876 D BluetoothA2dp: Proxy object connected
08-30 22:40:27.832  6425  6439 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:27.832  1291  6938 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-30 22:40:27.832  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-30 22:40:27.832  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.842  6976  6976 I BluetoothPbapService: Handler(): got msg=1
,08-30 22:40:27.842  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.842  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.842  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.842  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-30 22:40:27.842  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:27.842  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.842  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 22:40:27.842  1460  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.842  1015  1503 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 22:40:27.842  1460  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.842  2876  6463 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.842  2876  6463 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.842  6976  6987 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-30 22:40:27.842  6976  6976 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-30 22:40:27.842  6976  6999 D HeadsetStateMachine: Disconnected process message: 10
,08-30 22:40:27.842  1460  1471 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.842  1291  1291 D BluetoothInputDevice: Proxy object connected
08-30 22:40:27.842  1291  1291 D HidProfile: Bluetooth service connected
,08-30 22:40:27.842  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 22:40:27.842  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.842  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.842  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.842  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.852  1460  1471 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:27.852  1430  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.852  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 22:40:27.852  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.852  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:27.852  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.852  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.852  1430  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:27.852  1291  1300 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.852  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-30 22:40:27.852  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.852  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:27.852  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.852  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.862  6976  7039 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-30 22:40:27.862  1291  1300 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:27.862  1291  1306 D BluetoothPan: Binding service...
,08-30 22:40:27.862  1291  1291 D HeadsetProfile: Bluetooth service connected
,08-30 22:40:27.862  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-30 22:40:27.862  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.862  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.862  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.862  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.862  6976  7035 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-30 22:40:27.862  6976  7035 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.862  1932  1941 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.862  1932  1941 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:27.862  6976  7039 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:27.862  6976  7039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:40:27.862  1291  1300 D Bluetoothsap: onBluetoothStateChange: up=true
08-30 22:40:27.862  1291  1300 D Bluetoothsap: Binding service...
,08-30 22:40:27.862  6976  7039 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-30 22:40:27.862  6976  7039 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:27.862  6976  7039 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 22:40:27.862  6976  7039 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31f9ee21
,08-30 22:40:27.862  1291  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-30 22:40:27.862  1291  1291 D BluetoothPan: BluetoothPAN Proxy object connected
08-30 22:40:27.862  1291  1291 D PanProfile: Bluetooth service connected
08-30 22:40:27.862  6976  7039 D BluetoothSocket: channel: 19
08-30 22:40:27.862  6976  7039 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-30 22:40:27.862  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-30 22:40:27.862  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.862  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.862  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.862  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.872  1291  1300 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-30 22:40:27.872  1441  1457 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.872  1441  1457 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.872  2876  2884 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.872  1291  1291 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-30 22:40:27.872  1015  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:27.872  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-30 22:40:27.872  1291  1291 D SapProfile: Bluetooth service connected
,08-30 22:40:27.872  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.872  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.872  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-30 22:40:27.872  1291  1291 D Bluetoothsap: getConnectedDevices()
,08-30 22:40:27.872  2876  2884 E BluetoothHeadset: BluetoothHeadset service is binded
08-30 22:40:27.872  1430  6941 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.872  1430  6941 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.872  1430  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-30 22:40:27.872  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-30 22:40:27.872  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-30 22:40:27.872  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.872  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.872  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.872  1430  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,08-30 22:40:27.872  1291  1306 D BluetoothPbap: onBluetoothStateChange: up=true
,08-30 22:40:27.882  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-30 22:40:27.882  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.882  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.882  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:27.882  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.882  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-30 22:40:27.882  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-30 22:40:27.882  1291  1300 D BluetoothMap: onBluetoothStateChange: up=true
,08-30 22:40:27.882  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-30 22:40:27.882  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.882  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.882  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-30 22:40:27.882  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-30 22:40:27.882  1173  1206 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-30 22:40:27.882  1173  1206 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-30 22:40:27.882  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-30 22:40:27.882  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-30 22:40:27.882  1291  1291 D BluetoothPbap: Proxy object connected
08-30 22:40:27.882  1291  1291 D PbapServerProfile: Bluetooth service connected
,08-30 22:40:27.882  1291  1291 D BluetoothMap: Proxy object connected
08-30 22:40:27.882  1291  1291 D MapProfile: Bluetooth service connected
08-30 22:40:27.882  1291  1291 D BluetoothMap: getConnectedDevices()
,08-30 22:40:27.882  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:27.882  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-30 22:40:27.882  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-30 22:40:27.892  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-30 22:40:27.892  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-30 22:40:27.892  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:27.892  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:27.892  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:27.892  1173  1173 D BluetoothTile:  getBluetoothState : 12
,08-30 22:40:27.902  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@153f35b3, true
,08-30 22:40:27.902  1769  1769 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-30 22:40:27.902  1173  1700 D BluetoothTile:  handleUpdatestate:false name:null
,08-30 22:40:27.902  1430  1430 D BluetoothHeadset: registerMessageListener
,08-30 22:40:27.902  1015  1489 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:27.902  1015  4358 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-30 22:40:27.902  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-30 22:40:27.912  1015  1382 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:27.912  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.912  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:27.912  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.912  1015  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:27.912  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:27.912  1291  1291 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-30 22:40:27.912  6976  7000 D HeadsetService: registerMessageListener
,08-30 22:40:27.912  6976  7000 D HeadsetService: registerMessageListener
,08-30 22:40:27.912  6976  6999 D HeadsetStateMachine: Disconnected process message: 70
08-30 22:40:27.912  6976  7041 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-30 22:40:27.912  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-30 22:40:27.912  1291  1291 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-30 22:40:27.912  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-30 22:40:27.912  1291  1291 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-30 22:40:27.912  1291  1291 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-30 22:40:27.912  1291  1291 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-30 22:40:27.922  6976  6999 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3c7ea246
,08-30 22:40:27.922  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-30 22:40:27.922  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-30 22:40:27.922  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-30 22:40:27.932  6976  7041 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:27.932  6976  7041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:40:27.932  6976  7041 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-30 22:40:27.932  6976  7041 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:27.932  6976  7041 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-30 22:40:27.932  6976  7041 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1f809c07
08-30 22:40:27.932  6976  7041 D BluetoothSocket: channel: 5
,08-30 22:40:27.932  6976  6999 D HeadsetStateMachine: Disconnected process message: 9
,08-30 22:40:27.932  6976  6999 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-30 22:40:27.932  1291  1291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-30 22:40:27.932  1015  1133 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-30 22:40:27.942  1015  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.942  1015  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:27.942  1015  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:27.942  1015  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-30 22:40:27.942   284   730 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-30 22:40:27.942   284   730 V voice   : voice_set_parameters: enter: A2dpSuspended=false,
08-30 22:40:27.942   284   730 V voice   : voice_set_parameters: exit with code(-2)
08-30 22:40:27.942   284   730 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false,
08-30 22:40:27.942   284   730 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-30 22:40:27.942   284   730 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-30 22:40:27.942   284   730 V audio_hw_primary: adev_set_parameters: exit
08-30 22:40:27.942  6976  6999 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-30 22:40:27.952  1291  1291 D DockEventReceiver: finishStartingService: stopping service
,08-30 22:40:27.952  1291  1291 D BluetoothNotiBroadcastReceiver: onReceive
,08-30 22:40:27.952  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-30 22:40:27.952  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-30 22:40:27.962  6976  6976 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:27.962  6976  6976 D BtConfig.SecureMode: isSecureModeOn:false
,08-30 22:40:27.962  1015  1503 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-30 22:40:27.962  1015  1503 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.962  1015  1503 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:27.962  1015  1503 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:27.962  1015  1503 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-30 22:40:27.982  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-30 22:40:27.982  1015  2973 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-30 22:40:27.982  1015  2973 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-30 22:40:27.992  1015  2973 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:27.992  1015  2973 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:27.992  1015  2973 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:27.992  1015  1488 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-30 22:40:28.002  1932  7047 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-30 22:40:28.002  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-30 22:40:28.002  1015  4358 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-30 22:40:28.002  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:28.002  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:28.002  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:28.022  6976  7051 D BluetoothSocket: bindListen(): myUserId = 0
08-30 22:40:28.022  1015  4358 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-30 22:40:28.022  6976  7051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-30 22:40:28.022  1015  4358 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:28.022  1015  4358 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-30 22:40:28.022  1015  4358 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-30 22:40:28.022  6976  7051 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-30 22:40:28.022  6976  7051 D BluetoothSocket: bindListen(), new LocalSocket 
08-30 22:40:28.022  6976  7051 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-30 22:40:28.022  6976  7051 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36414059
,08-30 22:40:28.022  6976  7051 D BluetoothSocket: channel: 12
,08-30 22:40:28.022  6976  7051 I BtOppRfcommListener: Accept thread started.
,08-30 22:40:28.032  1932  7047 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:28.512  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:28.522  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-30 22:40:28.522  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 22:40:28.522  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31381e0f added. We now have 8 listener(s)
,08-30 22:40:28.522  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:28.522  1015  1028 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 22:40:28.522  1015  1028 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:28.522  1015  1028 D SecContentProvider2: mCursor = null
,08-30 22:40:28.532  1015  1028 D WifiService: setWifiEnabled: false pid=6253, uid=10155
,08-30 22:40:28.532  1015  1028 D SettingsProvider: name = wifi_on
,08-30 22:40:28.532  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:28.532  1015  2973 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-30 22:40:28.532  1015  2973 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-30 22:40:28.532  1015  2973 D SecContentProvider2: mCursor = null
,08-30 22:40:28.532  1015  2973 D WifiService: setWifiEnabled: true pid=6253, uid=10155
,08-30 22:40:28.532  1015  2973 W ActivityManager: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 22:40:28.542  1015  2973 W WifiService: Failed getting userId using ActivityManagerNative
08-30 22:40:28.542  1015  2973 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6253, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-30 22:40:28.542  1015  2973 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-30 22:40:28.542  1015  2973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-30 22:40:28.542  1015  2973 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204),
08-30 22:40:28.542  1015  2973 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-30 22:40:28.542  1015  2973 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-30 22:40:28.542  1015  2973 D SettingsProvider: name = wifi_on
,08-30 22:40:28.542  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-30 22:40:28.922  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-30 22:40:28.922  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:28.922  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:28.922  1015  1043 D Tethering: interfaceAdded wlan0
,08-30 22:40:28.922  1015  1128 E Tethering: No numeric data
,08-30 22:40:28.932  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:40:28.932  1015  1128 D Tethering: clearTetheredNotification()
,08-30 22:40:28.932  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-30 22:40:28.932  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
,08-30 22:40:28.932  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-30 22:40:28.932  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-30 22:40:28.932  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:28.942  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:28.942  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-30 22:40:28.942  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:28.942  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-30 22:40:28.942  1015  1043 D Tethering: interfaceAdded p2p0
,08-30 22:40:28.942  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-30 22:40:28.952   279   967 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-30 22:40:28.952   279   967 D SoftapController: Softap fwReload - Ok
,08-30 22:40:28.952  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:28.952  1015  1122 V NetworkStats: performPollLocked() took 21ms
,08-30 22:40:28.952   279   967 D CommandListener: Setting iface cfg
08-30 22:40:28.952   279   967 D CommandListener: Trying to bring down wlan0
08-30 22:40:28.952  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:28.952  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:28.952   279   967 D CommandListener: Clearing all IP addresses on wlan0
,08-30 22:40:28.962  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant,
,08-30 22:40:28.972  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-30 22:40:28.972  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-30 22:40:28.972  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-30 22:40:28.972  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:28.972  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:28.972  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-30 22:40:28.972  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:28.982  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:28.982  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:28.982  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-30 22:40:28.982  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-30 22:40:28.992  1173  1173 D HotspotTile: onReceive : 2, 0
,08-30 22:40:28.992  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:28.992  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:28.992  1015  1489 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:28.992  1015  1489 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:29.002  1015  1489 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:29.002  1015  1489 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:29.002  1015  1489 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:29.002  3655  3655 I Hs20UtilService: Starting #19
,08-30 22:40:29.002  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:29.002  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-30 22:40:29.002  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:29.002  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:29.002  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:29.012  7065  7065 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-30 22:40:29.012  7065  7065 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-30 22:40:29.012  7065  7065 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-30 22:40:29.032  7065  7065 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-30 22:40:29.032   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7065
08-30 22:40:29.032   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-30 22:40:29.032  7065  7065 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-30 22:40:29.032  7065  7065 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:29.032  7065  7065 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-30 22:40:29.032  7065  7065 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-30 22:40:29.032   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7065
08-30 22:40:29.032   403   403 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-30 22:40:29.162   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-30 22:40:29.172  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-30 22:40:29.242  7065  7065 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-30 22:40:29.242  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 22:40:29.252  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-30 22:40:29.252   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7065,
08-30 22:40:29.252   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 22:40:29.252  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 22:40:29.252  7065  7065 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:29.252  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-30 22:40:29.252  7065  7065 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:29.252  7065  7065 E wpa_supplicant: SIM READ ERROR
08-30 22:40:29.252  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:29.252  7065  7065 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:29.252  7065  7065 E wpa_supplicant: SIM READ ERROR
08-30 22:40:29.252  7065  7065 I wpa_supplicant: Blacklist: Clear (all) 
08-30 22:40:29.252  7065  7065 I wpa_supplicant: wpa_default_ap_write_once
08-30 22:40:29.252  7065  7065 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 22:40:29.252  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:29.252  7065  7065 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-30 22:40:29.252  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:29.252  7065  7065 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:29.252  7065  7065 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-30 22:40:29.262  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 22:40:29.262  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-30 22:40:29.262  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-30 22:40:29.262  1015  1128 D Tethering: InitialState.processMessage what=4
,08-30 22:40:29.262  1015  1128 E Tethering: No numeric data
08-30 22:40:29.262  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-30 22:40:29.262  1015  1128 D Tethering: clearTetheredNotification()
08-30 22:40:29.262  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:29.262  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:29.262  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:29.262  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:29.262  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:29.262  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:29.262  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:29.262  1015  1122 V NetworkStats: performPollLocked() took 3ms
,08-30 22:40:29.272  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:29.272  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:29.382  7065  7065 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-30 22:40:29.772  7065  7065 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-30 22:40:29.772  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-30 22:40:29.782  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-30 22:40:29.792   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7065
08-30 22:40:29.792   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-30 22:40:29.792  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-30 22:40:29.792  7065  7065 I wpa_supplicant: ssSupport state is = 1
,08-30 22:40:29.792  7065  7065 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-30 22:40:29.792  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-30 22:40:29.802  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-30 22:40:29.802   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7065
08-30 22:40:29.802   403   403 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-30 22:40:29.802  7065  7065 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,08-30 22:40:29.812  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 22:40:29.802  7065  7065 I wpa_supplicant: ssSupport state is = 1
08-30 22:40:29.802  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-30 22:40:29.802  7065  7065 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-30 22:40:29.812  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-30 22:40:29.802  7065  7065 E wpa_supplicant: SIM READ ERROR
08-30 22:40:29.802  7065  7065 I wpa_supplicant: wpa_default_ap_write_once,
08-30 22:40:29.802  7065  7065 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-30 22:40:29.802  7065  7065 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-30 22:40:29.812  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:29.812  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:29.812  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:29.812  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-30 22:40:29.852  1015  2735 D SSRM:n  : SIOP:: AP = 320
,08-30 22:40:29.912  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-30 22:40:29.912  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-30 22:40:29.912  7065  7065 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-30 22:40:29.912  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-30 22:40:29.912  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-30 22:40:29.952  7065  7065 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-30 22:40:29.952  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-30 22:40:29.962  7065  7065 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 22:40:29.962  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-30 22:40:29.962  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-30 22:40:29.972  7065  7065 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-30 22:40:29.972  7065  7065 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-30 22:40:29.972  7065  7065 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-30 22:40:29.972  7065  7065 E wpa_supplicant: SIM READ ERROR
08-30 22:40:29.972  7065  7065 I wpa_supplicant: Blacklist: Clear (all) ,
,08-30 22:40:29.982  7065  7065 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-30 22:40:29.982  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 22:40:29.982  7065  7065 I wpa_supplicant: Skip scan - bUseNetwork false
,08-30 22:40:29.992  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-30 22:40:29.992  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:29.992  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:29.992  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:29.992  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:29.992  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:29.992  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:29.992  1173  1700 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-30 22:40:29.992  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:29.992  1173  1173 D HotspotTile: onReceive : 3, 0
08-30 22:40:29.992  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-30 22:40:29.992  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-30 22:40:30.002  1291  1291 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-30 22:40:30.002  1015  1476 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:30.002  1015  1476 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:30.012  1015  1476 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:30.012  1015  1125 E WifiConfigStore: Not a HS20
08-30 22:40:30.012  1015  1476 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:30.012  1015  1476 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:30.012  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-30 22:40:30.012  3655  3655 I Hs20UtilService: Starting #20
,08-30 22:40:30.012  3655  3699 I Hs20UtilService: Message received 5011
,08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:30.012  6253  6253 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:30.012  6253  6253 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:30.022  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-30 22:40:30.022  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-30 22:40:30.022  6525  6525 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-30 22:40:30.022  6525  6525 D SecurityLogAgent: StateMachine : Current State = 1
08-30 22:40:30.022  6525  6525 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-30 22:40:30.022  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-30 22:40:30.032  7065  7065 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-30 22:40:30.032  7065  7065 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 22:40:30.032  7065  7065 I wpa_supplicant: reset timer : RESET_TIMER 0
08-30 22:40:30.032  7065  7065 I wpa_supplicant: P2P: Current p2p state = IDLE
08-30 22:40:30.032  7065  7065 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-30 22:40:30.032  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-30 22:40:30.032  7065  7065 I wpa_supplicant: First Scan Start
08-30 22:40:30.032  7065  7065 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-30 22:40:30.032  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-30 22:40:30.032  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-30 22:40:30.032  1015  1125 I WifiNative-HAL: startHal
08-30 22:40:30.032  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c4a888c
08-30 22:40:30.032  1015  1125 I WifiNative-HAL: Could not start hal
,08-30 22:40:30.032  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 22:40:30.032  6500  6500 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 22:40:30.032  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-30 22:40:30.042  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-30 22:40:30.042   279   967 D CommandListener: Setting iface cfg
08-30 22:40:30.042   279   967 D CommandListener: Trying to bring up p2p0
,08-30 22:40:30.042  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-30 22:40:30.042  1015  1124 D WifiP2pService: P2pEnablingState
08-30 22:40:30.042  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-30 22:40:30.042  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
08-30 22:40:30.042  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:30.042  1015  1124 D WifiP2pService: P2p socket connection successful
08-30 22:40:30.042  1015  1149 I WifiNative-HAL: startHal
08-30 22:40:30.042  1015  1124 D WifiP2pService: P2pEnabledState
08-30 22:40:30.042  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dc2a9bc
08-30 22:40:30.042  1015  1149 I WifiNative-HAL: Could not start hal
08-30 22:40:30.042  1015  1149 E WifiScanningService: could not start HAL
08-30 22:40:30.042  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-30 22:40:30.042  1015  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-30 22:40:30.042  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 22:40:30.042  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 22:40:30.042  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-30 22:40:30.042  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-30 22:40:30.042  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-30 22:40:30.042  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:30.042  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-30 22:40:30.042  1015  1046 D WifiDisplayController: disconnect
08-30 22:40:30.042  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-30 22:40:30.042  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-30 22:40:30.042  1015  1046 D WifiDisplayController: updateConnection
08-30 22:40:30.042  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-30 22:40:30.042  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-30 22:40:30.042  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
08-30 22:40:30.042  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:30.042  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-30 22:40:30.052  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-30 22:40:30.052  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-30 22:40:30.052  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-30 22:40:30.052  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 22:40:30.052  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-30 22:40:30.052  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-30 22:40:30.052  1015  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-30 22:40:30.052  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-30 22:40:30.052  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-30 22:40:30.052  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:30.052  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-30 22:40:30.062  7065  7065 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-30 22:40:30.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-30 22:40:30.062  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-30 22:40:30.062  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-30 22:40:30.062  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:30.062  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-30 22:40:30.062  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:30.062  1015  1125 D SecContentProvider2: mCursor = null
08-30 22:40:30.062  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-30 22:40:30.062  1015  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-30 22:40:30.062  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  secondary type: null
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  wps: 0
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  grpcapab: 0
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  devcapab: 0
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  status: 3
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  wfdInfo: null
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-30 22:40:30.062  1015  1046 D WifiDisplayController:  SConnectInfo : null
,08-30 22:40:30.062  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:30.062  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:30.072  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:30.072  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-30 22:40:30.072  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,08-30 22:40:30.082  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-30 22:40:30.082  1015  1124 D WifiP2pService: InactiveState
,08-30 22:40:30.082  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-30 22:40:30.082  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 22:40:30.082  7065  7065 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-30 22:40:30.082  6485  6485 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-30 22:40:30.082  1015  1124 D WifiP2pService: InactiveState{ what=143376 },
,08-30 22:40:30.092  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-30 22:40:30.552  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:30.552  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:30.562  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-30 22:40:30.562  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-30 22:40:30.562  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1ba06e3c Bundle[{}]
,08-30 22:40:30.562  6253  6307 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 22:40:30.572  6253  6307 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-30 22:40:30.572  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-30 22:40:30.572  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-30 22:40:30.572  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-30 22:40:30.572  6253  6307 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-30 22:40:30.582  6253  6307 I System.out: Running OutgoingSocketThread
,08-30 22:40:30.582  6253  7073 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1172)
,08-30 22:40:30.582  6253  7073 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 35831
,08-30 22:40:30.582  6253  7073 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-30 22:40:30.712   289   289 E SMD     : DCD OFF,
,08-30 22:40:31.142  7065  7065 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
08-30 22:40:31.142  7065  7065 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-30 22:40:31.142  7065  7065 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-30 22:40:31.142  7065  7065 I wpa_supplicant: Trying to associate with  'G700',
08-30 22:40:31.142  7065  7065 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-30 22:40:31.142  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-30 22:40:31.142  1015  7071 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-30 22:40:31.162  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 22:40:31.162  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:31.262  7065  7065 E wpa_supplicant: Cmd 35605 not handled
,08-30 22:40:31.262  7065  7065 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 22:40:31.262  7065  7065 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-30 22:40:31.262  7065  7065 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-30 22:40:31.262  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-30 22:40:31.262  7065  7065 I wpa_supplicant: Associated with F4.99.3E
08-30 22:40:31.262  7065  7065 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 22:40:31.262  7065  7065 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-30 22:40:31.262  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-30 22:40:31.272  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:31.272  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:31.272  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:31.272  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-30 22:40:31.272  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:31.272  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:31.272  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-30 22:40:31.272  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-30 22:40:31.272  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-30 22:40:31.272  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 22:40:31.272  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-30 22:40:31.272  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
,08-30 22:40:31.272  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-30 22:40:31.272  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:31.282  1015  1128 E Tethering: No numeric data
,08-30 22:40:31.282  7065  7065 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-30 22:40:31.282  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-30 22:40:31.282  1015  1128 D Tethering: clearTetheredNotification()
08-30 22:40:31.282  7065  7065 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-30 22:40:31.282  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-30 22:40:31.282  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-30 22:40:31.282  1015  1125 D SecContentProvider2: mCursor = null,
08-30 22:40:31.282  7065  7065 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-30 22:40:31.282  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-30 22:40:31.282  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:31.282  7065  7065 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-30 22:40:31.282  7065  7065 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-30 22:40:31.282  7065  7065 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-30 22:40:31.282  7065  7065 I wpa_supplicant: Blacklist: Clear (temp) 
08-30 22:40:31.282  7065  7065 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-30 22:40:31.292  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-30 22:40:31.292  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-30 22:40:31.292  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-30 22:40:31.292  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-30 22:40:31.292  1173  1173 D HotspotTile: updateTetherState():false, false
,08-30 22:40:31.292  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:31.292  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:31.292  1015  1122 V NetworkStats: performPollLocked() took 11ms
08-30 22:40:31.292  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:31.302  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:31.302  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:31.302  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-30 22:40:31.302  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-30 22:40:31.312  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-30 22:40:31.312  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-30 22:40:31.312  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:31.312  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-30 22:40:31.312  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:31.312  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 22:40:31.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:31.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:31.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:31.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:31.312  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:31.322  1015  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-30 22:40:31.322  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:31.322  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:31.322  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:31.322  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:31.322  3655  3655 I Hs20UtilService: Starting #21
,08-30 22:40:31.322  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:31.322  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-30 22:40:31.332  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:31.332  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-30 22:40:31.332  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-30 22:40:31.332  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:31.332  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-30 22:40:31.332  1291  1291 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-30 22:40:31.332  1291  3067 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-30 22:40:31.342   279   967 D CommandListener: Setting iface cfg,
,08-30 22:40:31.342  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-30 22:40:31.342  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 22:40:31.342  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:31.352  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:31.352  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-30 22:40:31.352  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:31.362  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:31.362  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:31.362  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:31.362  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-30 22:40:31.362  1015  1125 D SecContentProvider2: mCursor = null
,08-30 22:40:31.372  1015  1125 E WifiNative-wlan0: do suspend false
,08-30 22:40:31.372  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-30 22:40:31.372  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 22:40:31.582  6253  6307 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1173)
,08-30 22:40:31.582  6253  6307 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1173)
08-30 22:40:31.582  6253  6307 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1178)
08-30 22:40:31.582  6253  6307 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-30 22:40:31.582  6253  6307 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
08-30 22:40:31.582  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 22:40:31.582  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca78e9c added. We now have 2 listener(s)
,08-30 22:40:31.592  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.592  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.592  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.592  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.592  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297370a5 added. We now have 9 listener(s)
08-30 22:40:31.592  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.592  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 22:40:31.592  7076  7076 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 22:40:31.602  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:31.602  7076  7076 I dhcpcd  : version 5.5.6 starting
,08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:31.602  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:31.602  7076  7076 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-30 22:40:31.612  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:40:31.612  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18628c2b added. We now have 3 listener(s)
,08-30 22:40:31.612  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:31.612  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cecf888 added. We now have 10 listener(s)
08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.612  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:31.612  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-30 22:40:31.612  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:31.612  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.612  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:31.612  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca78e9c removed from the list
08-30 22:40:31.612  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 22:40:31.612  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297370a5 removed from the list
08-30 22:40:31.612  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
,08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.612  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-30 22:40:31.612  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.622  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@297370a5 not in the list
,08-30 22:40:31.622  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cecf888 removed from the list
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.622  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18628c2b removed from the list
08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25cf7221 added. We now have 2 listener(s)
,08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.622  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349fd646 added. We now have 9 listener(s)
08-30 22:40:31.622  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.622  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:40:31.632  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:31.632  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:31.632  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:40:31.632  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:31.632  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:31.632  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349d1534 added. We now have 3 listener(s)
08-30 22:40:31.632  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:31.642  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.642  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 22:40:31.642  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.642  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.642  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:31.642  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d900f5d added. We now have 10 listener(s)
08-30 22:40:31.642  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.642  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
08-30 22:40:31.642  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-30 22:40:31.642  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:31.642  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:31.642  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 22:40:31.642  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 22:40:31.652  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 22:40:31.652  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:40:31.652  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 22:40:31.652  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 22:40:31.652  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 22:40:31.662  6976  7040 D BtGatt.GattService: registerClient() - UUID=85cb447d-c80f-4fcb-a2b1-d8b82ecada7b
,08-30 22:40:31.682  7076  7076 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-30 22:40:31.682  7076  7076 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-30 22:40:31.682  7076  7076 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-30 22:40:31.682  7076  7076 I dhcpcd  : bssid match
08-30 22:40:31.682  7076  7076 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-30 22:40:31.702  6976  6994 D BtGatt.GattService: onClientRegistered() - UUID=85cb447d-c80f-4fcb-a2b1-d8b82ecada7b, clientIf=6,
08-30 22:40:31.702  6253  6262 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 22:40:31.702  6976  6984 D BtGatt.GattService: start scan with filters
,08-30 22:40:31.702  6976  6998 D BtGatt.ScanManager: handling starting scan
,08-30 22:40:31.702  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 22:40:31.702  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 22:40:31.702  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 22:40:31.702  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-30 22:40:31.712  6976  6998 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25286a0c
,08-30 22:40:31.712  6976  6994 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 22:40:31.712  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.712  6976  6998 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:31.712  6976  6998 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 22:40:31.712  6976  6998 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-30 22:40:31.712  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 22:40:31.712  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 22:40:31.712  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:31.712  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 22:40:31.712  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.712  6976  6998 D BtGatt.ScanManager: Starting BLE batch scan
08-30 22:40:31.712  6976  6998 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 22:40:31.712  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:31.722  6976  6994 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 22:40:31.722  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.722  6253  6307 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-30 22:40:31.722  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:31.722  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-30 22:40:31.722  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.722  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-30 22:40:31.722  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-30 22:40:31.722  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:40:31.722  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:31.722  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 22:40:31.722  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:31.722  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:31.722  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 22:40:31.722  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.722  6976  7035 D BtGatt.GattService: stopScan() - queue size =1
,08-30 22:40:31.732  6976  7000 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 22:40:31.732  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 22:40:31.732  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:40:31.732  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-30 22:40:31.732  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:31.742  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:31.742  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:31.742  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:31.742  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:40:31.742  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:31.742  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.742  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.742  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:31.742  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25cf7221 removed from the list
08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.742  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349fd646 removed from the list
08-30 22:40:31.742  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:31.742  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.742  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.742  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.742  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.742  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349fd646 not in the list
08-30 22:40:31.742  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.742  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.742  6976  6998 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 91
,08-30 22:40:31.752  6976  6998 D BtGatt.ScanManager: filter size is 1
08-30 22:40:31.752  6976  6998 D BtGatt.ScanManager: delete FilterIndex - 3
,08-30 22:40:31.752  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.752  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:31.752  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d900f5d removed from the list
08-30 22:40:31.752  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.752  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.752  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.752  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@349d1534 removed from the list
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c34459 added. We now have 2 listener(s)
,08-30 22:40:31.752  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 22:40:31.752  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.752  6976  6998 D BtGatt.ScanManager: stopping BLe Batch
,08-30 22:40:31.752  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.752  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.752  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.752  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25cd681e added. We now have 9 listener(s)
08-30 22:40:31.752  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:31.752  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 22:40:31.762  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.762  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 22:40:31.762  6976  6998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 22:40:31.762  6976  6994 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 22:40:31.762  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.762  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:31.762  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:31.762  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 22:40:31.762  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:31.762  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 22:40:31.772  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b9d6cc added. We now have 3 listener(s)
,08-30 22:40:31.772  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.772  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.772  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.772  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.772  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105acd15 added. We now have 10 listener(s)
08-30 22:40:31.772  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.772  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:31.772  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:31.772  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:40:31.772  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:31.772  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 22:40:31.772  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-30 22:40:31.772  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-30 22:40:31.782  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-30 22:40:31.782  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:40:31.782  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-30 22:40:31.782  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 22:40:31.782  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 22:40:31.782  6976  7035 D BtGatt.GattService: registerClient() - UUID=200c97a2-ca27-4597-8185-bae81c47c591
,08-30 22:40:31.792  7076  7076 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-30 22:40:31.832  6976  6994 D BtGatt.GattService: onClientRegistered() - UUID=200c97a2-ca27-4597-8185-bae81c47c591, clientIf=6
,08-30 22:40:31.832  6253  6262 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 22:40:31.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:31.832  6976  7040 D BtGatt.GattService: start scan with filters
,08-30 22:40:31.832  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:31.832  6976  6998 D BtGatt.ScanManager: handling starting scan
,08-30 22:40:31.832  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-30 22:40:31.832  6976  6994 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-30 22:40:31.832  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.832  6976  6998 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:31.832  6976  6998 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-30 22:40:31.832  6976  6998 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-30 22:40:31.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 22:40:31.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-30 22:40:31.842  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 22:40:31.842  7076  7076 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-30 22:40:31.842  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-30 22:40:31.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:31.842  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 22:40:31.842  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-30 22:40:31.842  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.842  6976  6998 D BtGatt.ScanManager: Starting BLE batch scan
08-30 22:40:31.842  6976  6998 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 22:40:31.852  6976  6994 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-30 22:40:31.852  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.852  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:31.852  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-30 22:40:31.852  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.852  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
08-30 22:40:31.852  6253  6307 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-30 22:40:31.862  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-30 22:40:31.862  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:31.862  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.862  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 22:40:31.862  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16c34459 removed from the list
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.862  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25cd681e removed from the list
08-30 22:40:31.862  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:31.862  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-30 22:40:31.862  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.862  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25cd681e not in the list
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:31.862  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:31.862  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:31.862  6976  6998 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 92
,08-30 22:40:31.862  6976  6984 D BtGatt.GattService: stopScan() - queue size =1
08-30 22:40:31.862  6976  6998 D BtGatt.ScanManager: filter size is 1
08-30 22:40:31.862  6976  6998 D BtGatt.ScanManager: delete FilterIndex - 4
,08-30 22:40:31.862  6976  7040 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 22:40:31.872  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 22:40:31.872  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:31.872  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 22:40:31.872  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-30 22:40:31.872  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:40:31.872  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:40:31.872  6976  6998 D BtGatt.ScanManager: stopping BLe Batch
,08-30 22:40:31.872  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-30 22:40:31.872  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:31.872  6976  6998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.882  6976  6994 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-30 22:40:31.882  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@105acd15 removed from the list
08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:31.882  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b9d6cc removed from the list
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca82591 added. We now have 2 listener(s)
,08-30 22:40:31.882  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-30 22:40:31.882  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:31.882  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.882  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e305cf6 added. We now have 9 listener(s)
08-30 22:40:31.882  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:31.882  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 22:40:31.892  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:31.902  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:31.912  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-30 22:40:31.912  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:31.912  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 22:40:31.912  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-30 22:40:31.912  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d4a3364 added. We now have 3 listener(s)
,08-30 22:40:31.912  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-30 22:40:31.912  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:31.912  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:31.912  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-30 22:40:31.912  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:31.912  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79889cd added. We now have 10 listener(s)
08-30 22:40:31.912  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:31.912  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:31.912  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-30 22:40:31.912  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-30 22:40:31.912  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:31.912  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-30 22:40:31.922  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-30 22:40:31.952  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-30 22:40:31.952  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-30 22:40:31.962  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-30 22:40:31.962  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-30 22:40:31.962  6253  6307 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-30 22:40:31.962  6976  7000 D BtGatt.GattService: registerClient() - UUID=5f33224d-72f0-4237-9cbd-d1cc2059a7d1
,08-30 22:40:32.002  6976  6994 D BtGatt.GattService: onClientRegistered() - UUID=5f33224d-72f0-4237-9cbd-d1cc2059a7d1, clientIf=6
08-30 22:40:32.002  6253  7087 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-30 22:40:32.002  6976  7040 D BtGatt.GattService: start scan with filters
08-30 22:40:32.002  6976  6998 D BtGatt.ScanManager: handling starting scan
08-30 22:40:32.002  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-30 22:40:32.002  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-30 22:40:32.002  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-30 22:40:32.002  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-30 22:40:32.002  6976  6994 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-30 22:40:32.002  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:32.002  6976  6998 D BtGatt.ScanManager: allow scan with filters
08-30 22:40:32.002  6976  6998 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-30 22:40:32.002  6976  6998 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-30 22:40:32.012  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-30 22:40:32.012  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:32.012  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-30 22:40:32.012  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-30 22:40:32.012  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-30 22:40:32.012  6976  6998 D BtGatt.ScanManager: Starting BLE batch scan
08-30 22:40:32.012  6976  6998 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-30 22:40:32.012  6976  6994 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-30 22:40:32.012  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:32.012  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-30 22:40:32.022  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-30 22:40:32.022  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:32.032  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-30 22:40:32.032  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:32.032  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:32.032  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-30 22:40:32.032  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ca82591 removed from the list
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.032  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e305cf6 removed from the list
08-30 22:40:32.032  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:32.032  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-30 22:40:32.032  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.032  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e305cf6 not in the list,
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-30 22:40:32.032  6976  7035 D BtGatt.GattService: stopScan() - queue size =1
,08-30 22:40:32.032  6976  6987 D BtGatt.GattService: unregisterClient() - clientIf=6
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-30 22:40:32.032  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-30 22:40:32.032  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:32.042  6976  6998 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 93
08-30 22:40:32.042  6976  6998 D BtGatt.ScanManager: filter size is 1
08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-30 22:40:32.042  6976  6998 D BtGatt.ScanManager: delete FilterIndex - 5
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:32.042  6976  6994 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-30 22:40:32.042  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:32.042  6976  6998 D BtGatt.ScanManager: stopping BLe Batch
08-30 22:40:32.042  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:32.042  6253  6253 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-30 22:40:32.042  6253  6253 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.042  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@79889cd removed from the list
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:32.042  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:32.042  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:32.042  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d4a3364 removed from the list
08-30 22:40:32.042  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:32.042  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b0f5c9 added. We now have 2 listener(s),
08-30 22:40:32.042  6976  6994 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-30 22:40:32.042  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-30 22:40:32.042  6976  6998 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-30 22:40:32.042  6976  6994 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-30 22:40:32.042  6976  6994 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-30 22:40:32.042  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 22:40:32.052  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:32.052  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:32.052  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cb214ce added. We now have 9 listener(s)
08-30 22:40:32.052  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 22:40:32.052  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-30 22:40:32.052  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 22:40:32.062  6253  6307 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 22:40:32.062  6253  6307 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 22:40:32.062  6253  6307 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 22:40:32.062  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-30 22:40:32.062  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc68afc added. We now have 3 listener(s)
,08-30 22:40:32.062  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:32.072  6253  6253 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ca2585 added. We now have 10 listener(s)
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 22:40:32.072  6253  6307 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:32.072  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14b0f5c9 removed from the list
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cb214ce removed from the list
08-30 22:40:32.072  6253  6307 D io.jxcore.node.ConnectivityMonitor: stop
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-30 22:40:32.072  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.072  6253  6307 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cb214ce not in the list
08-30 22:40:32.072  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20ca2585 removed from the list
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-30 22:40:32.072  6253  6307 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-30 22:40:32.072  6253  6307 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-30 22:40:32.072  6253  6307 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-30 22:40:32.072  6253  6307 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fc68afc removed from the list
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-30 22:40:32.072  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-30 22:40:32.082  6253  6307 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-30 22:40:32.082  6253  7110 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1187, name: My test thread name)
08-30 22:40:32.082  6253  7110 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1187, thread name: My test thread name)
08-30 22:40:32.082  6253  7110 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 22:40:32.082  6253  7111 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1189, name: My test thread name)
08-30 22:40:32.082  6253  7111 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1189, thread name: My test thread name)
08-30 22:40:32.092  6253  7111 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-30 22:40:32.092  6253  6307 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-30 22:40:32.092  6253  6307 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-30 22:40:32.092  6253  6307 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-30 22:40:32.092  6253  6307 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-30 22:40:32.092  6253  6307 D com.test.thalitest.ThaliTestRunner: Total duration: 24277 ms
08-30 22:40:32.092  6253  6307 I jxcore-log: Total number of executed tests:  80
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: Number of passed tests:  80
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: Number of failed tests:  0
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: Number of ignored tests:  0
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: Total duration:  24277
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.092  6253  6307 I jxcore-log: My device name is: samsung-SM-A500FU
08-30 22:40:32.092  6253  6307 I jxcore-log: 
08-30 22:40:32.102  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.102  6253  6307 I jxcore-log: 
08-30 22:40:32.102  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.102  6253  6307 I jxcore-log: 
08-30 22:40:32.102  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.102  6253  6307 I jxcore-log: 
08-30 22:40:32.102  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.102  6253  6307 I jxcore-log: 
08-30 22:40:32.102  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.102  6253  6307 I jxcore-log: 
,08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.112  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.112  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.122  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.122  6253  6307 I jxcore-log: 
08-30 22:40:32.132  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.132  6253  6307 I jxcore-log: 
08-30 22:40:32.132  6253  6307 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 22:40:32.132  6253  6307 I jxcore-log: 
,08-30 22:40:32.192  1015  1125 E WifiNative-wlan0: do suspend true
,08-30 22:40:32.212  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-30 22:40:32.212  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-30 22:40:32.222  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-30 22:40:32.222  1015  1125 E WifiStateMachine: VerifyingLinkState enter
,08-30 22:40:32.222  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-30 22:40:32.222  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:32.222  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.222  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.222  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.222  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.222  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-30 22:40:32.222  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-30 22:40:32.222  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-30 22:40:32.222  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-30 22:40:32.242  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-30 22:40:32.242  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-30 22:40:32.242  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-30 22:40:32.242  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-30 22:40:32.242  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-30 22:40:32.242  6253  6253 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 22:40:32.252  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:32.252  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:32.252  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.252  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.252  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.252  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.262  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-30 22:40:32.262  1015  1382 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:32.262  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:32.262  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:32.262  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:32.262  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-30 22:40:32.262  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-30 22:40:32.262  3655  3655 I Hs20UtilService: Starting #22
,08-30 22:40:32.262  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:32.262  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-30 22:40:32.262  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-30 22:40:32.272  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:32.272  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
08-30 22:40:32.272  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-30 22:40:32.272  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-30 22:40:32.272  1015  1127 D ConnectivityService: LTETest block dns file not exists
,08-30 22:40:32.272  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-30 22:40:32.282  1015  1127 E ConnectivityService: updateNetworkInfo(),
08-30 22:40:32.282  1015  1127 E ConnectivityService: updateNetworkInfo()
08-30 22:40:32.282  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-30 22:40:32.282  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-30 22:40:32.282  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,08-30 22:40:32.282  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:32.282  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-30 22:40:32.282  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-30 22:40:32.282  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-30 22:40:32.282  1015  7074 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-30 22:40:32.282  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-30 22:40:32.292  1015  1127 D ConnectivityService:    accepting network in place of null
,08-30 22:40:32.292  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-30 22:40:32.292  1460  1460 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-30 22:40:32.292  1460  1460 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-30 22:40:32.292  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-30 22:40:32.292  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
,08-30 22:40:32.292  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-30 22:40:32.292  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-30 22:40:32.292  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:32.292  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-30 22:40:32.292   279   963 D EnterpriseController: uids 1000
08-30 22:40:32.292   279   963 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-30 22:40:32.292   279   963 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:32.302  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.302  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-30 22:40:32.302  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-30 22:40:32.302  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-30 22:40:32.302  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:32.302  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 22:40:32.302  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.312  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.312  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-30 22:40:32.312  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504],
08-30 22:40:32.312  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-30 22:40:32.322  1173  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:40:32.322  3802  6316 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-30 22:40:32.322  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-30 22:40:32.322  1015  1128 D Tethering: MasterInitialState.processMessage what=3
,08-30 22:40:32.322  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.322  1015  1122 V NetworkStats: updateIfacesLocked()
08-30 22:40:32.322  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-30 22:40:32.322  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:32.322  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:32.322  1015  1488 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:32.322  1015  1488 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:32.322  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.322  1015  1122 V NetworkStats: performPollLocked() took 4ms
,08-30 22:40:32.332  1015  1488 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:32.332  1015  1488 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:32.332  1015  1488 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:32.332  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.332  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-30 22:40:32.332  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-30 22:40:32.332  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.332  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.332  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.332  3655  3655 I Hs20UtilService: Starting #23
08-30 22:40:32.332  3655  3699 I Hs20UtilService: Message received 5007
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 22:40:32.332  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 22:40:32.342  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:32.342  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-30 22:40:32.342  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.342  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.342  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.342  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.342  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:32.342  1291  1291 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-30 22:40:32.342  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-30 22:40:32.342  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.342  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:32.342  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-30 22:40:32.342  1291  1291 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-30 22:40:32.342  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 22:40:32.352  1015  3002 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-30 22:40:32.352  1015  3002 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-30 22:40:32.352  1015  3002 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:32.352  1015  3002 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:32.352  1015  3002 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-30 22:40:32.352  3655  3655 I Hs20UtilService: Starting #24
08-30 22:40:32.352  3655  3699 I Hs20UtilService: Message received 5007
,08-30 22:40:32.362  1291  1291 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-30 22:40:32.362  1291  1291 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-30 22:40:32.362  1015  1476 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-30 22:40:32.372  1015  1217 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-30 22:40:32.372  1015  1217 D SecContentProvider2: mCursor = null
,08-30 22:40:32.372  1015  4358 D SecContentProvider2: uri = 15 selection = getToastGravity
08-30 22:40:32.372  1015  4358 D SecContentProvider2: mCursor = null
,08-30 22:40:32.372  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-30 22:40:32.372  1015  1027 D SecContentProvider2: mCursor = null
,08-30 22:40:32.372  1015  1503 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-30 22:40:32.372  1015  1503 D SecContentProvider2: mCursor = null
,08-30 22:40:32.372  1015  3002 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-30 22:40:32.382  1015  3002 D SecContentProvider2: mCursor = null
,08-30 22:40:32.382  1015  1133 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-30 22:40:32.382  1015  1133 D SecContentProvider2: mCursor = null
08-30 22:40:32.382  6253  6253 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 22:40:32.392  7112  7112 D AndroidRuntime: 
08-30 22:40:32.392  7112  7112 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 22:40:32.392  7112  7112 D AndroidRuntime: CheckJNI is OFF
,08-30 22:40:32.392  7112  7112 D AndroidRuntime: readGMSProperty: start
08-30 22:40:32.392  7112  7112 D AndroidRuntime: readGMSProperty: already setted!!
08-30 22:40:32.392  7112  7112 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-30 22:40:32.392  7112  7112 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-30 22:40:32.392  7112  7112 D AndroidRuntime: readGMSProperty: end
,08-30 22:40:32.392  7112  7112 D AndroidRuntime: addProductProperty: start
,08-30 22:40:32.402  1015  7074 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-30 22:40:32.402   259   259 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-30 22:40:32.412  1015  4151 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-30 22:40:32.422  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 22:40:32.452  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 30 Aug 2016 20:40:32 GMT], X-Android-Received-Millis=[1472589632459], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472589632433]}
08-30 22:40:32.452  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-30 22:40:32.452  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-30 22:40:32.452  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-30 22:40:32.452  1015  7074 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-30 22:40:32.452  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-30 22:40:32.452  1173  1694 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:40:32.452  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-30 22:40:32.452  3802  6316 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-30 22:40:32.452  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-30 22:40:32.462  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-30 22:40:32.462  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-30 22:40:32.462  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-30 22:40:32.532  7112  7112 E AffinityControl: AffinityControl: registerfunction enter
,08-30 22:40:32.542  6253  6253 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-30 22:40:32.552  7112  7112 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-30 22:40:32.572  1015  4152 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-30 22:40:32.572  1015  4152 D PackageManager: START PACKAGE DELETE: observer{740729028}
08-30 22:40:32.572  1015  4152 D PackageManager: pkg{<packageName>}
08-30 22:40:32.572  1015  4152 D PackageManager: user{0}
08-30 22:40:32.572  1015  4152 D PackageManager: caller{2000}
08-30 22:40:32.572  1015  4152 D PackageManager: flags{2}
08-30 22:40:32.572  1015  4152 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-30 22:40:32.572  1015  4152 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-30 22:40:32.572  1015  4152 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-30 22:40:32.572  1015  4152 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-30 22:40:32.572  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-30 22:40:32.572  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-30 22:40:32.572  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-30 22:40:32.572  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-30 22:40:32.572  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-30 22:40:32.572  1015  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-30 22:40:32.582  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
08-30 22:40:32.582  1015  1041 I ActivityManager: Killing 6253:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-30 22:40:32.582  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{39fd8112 u0 com.test.thalitest/.MainActivity t128},
,08-30 22:40:32.592  1015  1041 W ActivityManager: mDVFSHelper.acquire()
,08-30 22:40:32.692  1015  2973 I WindowState: WIN DEATH: Window{223af072 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 22:40:32.692   259   455 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-30 22:40:32.702   259   451 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-30 22:40:32.702  1015  2973 D InputDispatcher: Focus left window: 6253
,08-30 22:40:32.722  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-30 22:40:32.722  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 22:40:32.722  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-30 22:40:32.722  1015  1055 I ActivityManager:   Force finishing activity ActivityRecord{39fd8112 u0 com.test.thalitest/.MainActivity t128 f}
,08-30 22:40:32.732  1015  1055 W ActivityManager: Duplicate finish request for ActivityRecord{39fd8112 u0 com.test.thalitest/.MainActivity t128 f}
,08-30 22:40:32.742  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-30 22:40:32.752  3160  3160 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-30 22:40:32.752  1015  1041 D InputDispatcher: Focused application released
,08-30 22:40:32.762  5753  5753 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 701us total 25.596ms
,08-30 22:40:32.762  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 22:40:32.772  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 22:40:32.782  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-30 22:40:32.782  3160  3160 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,08-30 22:40:32.792  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-30 22:40:32.792  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 22:40:32.802  1769  1769 E SamsungIME: mOCRHelper is null
,08-30 22:40:32.802  1932  2112 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 22:40:32.812  3802  3802 I art     : Explicit concurrent mark sweep GC freed 22973(1399KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.523ms total 78.817ms
,08-30 22:40:32.812  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:32.832  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-30 22:40:32.832  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:32.832  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-30 22:40:32.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-30 22:40:32.832  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-30 22:40:32.842  1015  1122 V NetworkStats: performPollLocked() took 15ms
,08-30 22:40:32.842  3160  3160 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-30 22:40:32.852  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-30 22:40:32.852  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-30 22:40:32.862  3160  3160 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-30 22:40:32.862  3705  3705 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 30 22:40:32 GMT+02:00 2016
,08-30 22:40:32.882  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-30 22:40:32.882  6577  6577 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-30 22:40:32.892  1015  1382 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-30 22:40:32.892  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-30 22:40:32.892  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:32.892  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:32.892  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-30 22:40:32.912  3705  3705 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-30 22:40:32.912  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-30 22:40:32.912  1015  1382 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-30 22:40:32.912  1015  1382 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-30 22:40:32.912  1015  1382 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-30 22:40:32.912  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:32.912  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:32.912  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:32.912  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:32.922  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-30 22:40:32.932  7130  7130 E Zygote  : MountEmulatedStorage()
,08-30 22:40:32.932  7130  7130 E Zygote  : v2
08-30 22:40:32.932  7130  7130 I libpersona: KNOX_SDCARD checking this for 10094
08-30 22:40:32.932  7130  7130 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:32.932  7130  7130 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 22:40:32.932  1015  1382 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7130 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-30 22:40:32.942  3705  3705 I KLMS-2.5.183: : KLMSIntentService(): onCreate(),
,08-30 22:40:32.942  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
08-30 22:40:32.942  7130  7130 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:32.942  7130  7130 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:32.962  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-30 22:40:32.962  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-30 22:40:32.962  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-30 22:40:32.962  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-30 22:40:32.972  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-30 22:40:32.972  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-30 22:40:32.972  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-30 22:40:32.982  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-30 22:40:32.982  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-30 22:40:32.982  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 22:40:32.982  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-30 22:40:32.982  3705  3705 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 22:40:32.982  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-30 22:40:32.982  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-30 22:40:33.002  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-30 22:40:33.002  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-30 22:40:33.002  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:33.002  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-30 22:40:33.002  1015  1028 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
08-30 22:40:33.002  1015  1028 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-30 22:40:33.002  7130  7130 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.002  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-30 22:40:33.002  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
08-30 22:40:33.002  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-30 22:40:33.012  1015  2735 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-30 22:40:33.002  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-30 22:40:33.012  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-30 22:40:33.002  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-30 22:40:33.002  7130  7130 D ActivityThread: Added TimaKeyStore provider
08-30 22:40:33.012  3705  3705 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,08-30 22:40:33.012  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-30 22:40:33.012  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-30 22:40:33.012  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-30 22:40:33.012  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-30 22:40:33.012  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-30 22:40:33.012  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-30 22:40:33.022  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,08-30 22:40:33.022  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-30 22:40:33.022  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.022  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.022  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.022  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:33.032  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-30 22:40:33.032  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-30 22:40:33.042  3160  3160 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
08-30 22:40:33.042  3160  3160 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
08-30 22:40:33.042  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-30 22:40:33.042  3160  3160 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] ,
08-30 22:40:33.042  3160  3160 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-30 22:40:33.042  1015  1055 I art     : Explicit concurrent mark sweep GC freed 71853(5MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/43MB, paused 9.186ms total 294.189ms
,08-30 22:40:33.052  1015  1025 I art     : WaitForGcToComplete blocked for 233.280ms for cause HeapTrim
,08-30 22:40:33.052  7145  7145 E Zygote  : MountEmulatedStorage()
,08-30 22:40:33.052  7145  7145 E Zygote  : v2
08-30 22:40:33.052  7145  7145 I libpersona: KNOX_SDCARD checking this for 10044
08-30 22:40:33.052  7145  7145 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.052  7145  7145 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:33.052  7145  7145 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-30 22:40:33.062  7145  7145 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-30 22:40:33.062  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 22:40:33.062  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest,
08-30 22:40:33.062  1015  1041 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7145 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-30 22:40:33.072  1015  4151 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 22:40:33.072  1015  4151 D SecContentProvider2: mCursor = null
,08-30 22:40:33.072  7145  7145 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.082  7145  7145 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:33.082  1015  1055 D PackageManager: delete codoeFile: 
08-30 22:40:33.082  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-30 22:40:33.092  1015  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
08-30 22:40:33.092  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-30 22:40:33.092  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.092  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.092  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.092  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.092  1015  1055 D PackageManager: result of delete: 1{740729028}
,08-30 22:40:33.112  7161  7161 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.112  7161  7161 E Zygote  : v2
08-30 22:40:33.112  7161  7161 I libpersona: KNOX_SDCARD checking this for 10149
08-30 22:40:33.112  7161  7161 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.112  7161  7161 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:33.112  7161  7161 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:33.112  1015  1041 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7161 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:40:33.112  7161  7161 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:33.122  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.122  1015  1382 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-30 22:40:33.122  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
08-30 22:40:33.122  1015  1382 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-30 22:40:33.122  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
08-30 22:40:33.122  1015  1382 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-30 22:40:33.132  3160  3160 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
08-30 22:40:33.132  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-30 22:40:33.132  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-30 22:40:33.132  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-30 22:40:33.142  1173  1173 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-30 22:40:33.142  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.142  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
08-30 22:40:33.142  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
,08-30 22:40:33.142  1173  1173 D PanelView: There is/are notification(s) 
08-30 22:40:33.142  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-30 22:40:33.142   259   259 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
08-30 22:40:33.142  7112  7112 D AndroidRuntime: Shutting down VM
,08-30 22:40:33.142  4750  7160 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-30 22:40:33.152  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-30 22:40:33.152  1173  1173 D PersonaManager: isKioskContainerExistOnDevice
,08-30 22:40:33.152  1173  1173 D PanelView: There is/are notification(s) 
08-30 22:40:33.152  1173  1173 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-30 22:40:33.162  1015  1489 D InputDispatcher: Focus entered window: 3160
,08-30 22:40:33.162  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-30 22:40:33.162  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-30 22:40:33.162  3160  3160 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-30 22:40:33.162  7161  7161 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.162  7161  7161 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:33.172  3160  3160 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-30 22:40:33.172  3160  3160 V ActivityThread: updateVisibility : ActivityRecord{98f4750 token=android.os.BinderProxy@266ca9e7 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-30 22:40:33.182  7145  7145 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-30 22:40:33.182  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-30 22:40:33.182  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 22:40:33.182  7145  7145 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 22:40:33.182  7145  7145 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:40:33.192  7130  7130 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-30 22:40:33.192  7145  7145 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 22:40:33.192  7145  7145 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 22:40:33.192  7145  7145 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 22:40:33.192  7145  7145 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 22:40:33.192  7130  7130 D elm:15183: ELMEngine.ELMEngine( context ).
,08-30 22:40:33.192  7130  7130 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-30 22:40:33.202  1015  1382 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-30 22:40:33.202  1015  1382 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-30 22:40:33.202  1015  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:33.202  1015  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:33.202  1015  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-30 22:40:33.202  1015  1133 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-30 22:40:33.202  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-30 22:40:33.202  1015  1055 D PackageManager: userId{-1}
08-30 22:40:33.202  1015  1055 D PackageManager: andCode{true}
,08-30 22:40:33.202  3705  7129 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-30 22:40:33.212  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-30 22:40:33.212  7130  7130 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-30 22:40:33.212  3705  7129 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-30 22:40:33.222  4750  4750 I art     : Explicit concurrent mark sweep GC freed 735(52KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 880us total 43.755ms
,08-30 22:40:33.222  1015  1133 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6253 uid 10155
,08-30 22:40:33.222  1173  1173 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-30 22:40:33.222  1015  7179 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-30 22:40:33.232  1173  1173 D PanelView: There is/are notification(s) 
,08-30 22:40:33.232  3160  3160 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@266ca9e7 time:151744
,08-30 22:40:33.242  1769  1769 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-30 22:40:33.242  3428  3428 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-30 22:40:33.242  3428  3428 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-30 22:40:33.242  3428  3428 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-30 22:40:33.242  3428  3428 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-30 22:40:33.242  3428  3428 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-30 22:40:33.242  3428  3428 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 22:40:33.242  3428  3428 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 22:40:33.242  3428  3428 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-30 22:40:33.242  3428  3428 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-30 22:40:33.242  3705  3705 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-30 22:40:33.252  6688  6697 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,08-30 22:40:33.252  6688  6697 D BadgeProvider: sendNotify, [notify] : null
08-30 22:40:33.252  7130  7130 D elm:15183: ElmAgentService : onCreate()
08-30 22:40:33.252  6688  6697 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-30 22:40:33.252  6688  6697 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-30 22:40:33.252  6688  6697 D BadgeProvider: update, [UpdateCount] : 1
,08-30 22:40:33.262  7130  7177 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-30 22:40:33.262  7130  7177 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-30 22:40:33.262  7130  7177 D elm:15183: MDMBridge.getInstance()
08-30 22:40:33.262  7130  7177 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
08-30 22:40:33.262  7161  7161 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-30 22:40:33.262  7161  7161 D ThemeInfoUtil: isCurrentFestival = false
,08-30 22:40:33.262  1015  4151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-30 22:40:33.262  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.262  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.262  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.262  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:33.272  7130  7177 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-30 22:40:33.272  6560  6560 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-30 22:40:33.272  6560  6560 I PCWCLIENTTRACE_PushUtil: sales region : global
08-30 22:40:33.272  6560  6560 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-30 22:40:33.272  6560  6560 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-30 22:40:33.282  7183  7183 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.282  7183  7183 E Zygote  : v2
08-30 22:40:33.282  7183  7183 I libpersona: KNOX_SDCARD checking this for 1000
08-30 22:40:33.282  7183  7183 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.282  7183  7183 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:33.282  1015  4151 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7183 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-30 22:40:33.282  7183  7183 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:33.292  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{dfac599 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:151802
08-30 22:40:33.292  1015  1046 W ActivityManager: mDVFSHelper.release()
08-30 22:40:33.292  7130  7130 D elm:15183: ElmAgentService : onDestroy().
,08-30 22:40:33.292  7183  7183 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:33.292  1015  4151 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-30 22:40:33.292  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.292  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.292  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.292  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:33.302  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-30 22:40:33.302  1015  2973 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-30 22:40:33.302  1015  2973 D SecContentProvider2: mCursor = null
,08-30 22:40:33.302  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.302  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.312  7183  7183 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.312  7198  7198 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.312  7198  7198 E Zygote  : v2
,08-30 22:40:33.312  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
08-30 22:40:33.312  7198  7198 I libpersona: KNOX_SDCARD checking this for 10152
08-30 22:40:33.312  7198  7198 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.312  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-30 22:40:33.322  7183  7183 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:33.322  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-30 22:40:33.322  1015  4151 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7198 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
08-30 22:40:33.322  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:33.332  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.332  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 22:40:33.332  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:40:33.332  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:40:33.342  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.342  1015  1217 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-30 22:40:33.342  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.342  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.342  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.342  1015  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:33.352  7112  7112 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-30 22:40:33.362  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.372  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-30 22:40:33.372  7214  7214 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.372  7214  7214 E Zygote  : v2,
08-30 22:40:33.372  7214  7214 I libpersona: KNOX_SDCARD checking this for 10032
08-30 22:40:33.372  7214  7214 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.372  7214  7214 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:33.372  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.372  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-30 22:40:33.382  7214  7214 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:33.382  7214  7214 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:33.382  1015  1217 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7214 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-30 22:40:33.382  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:33.382  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 22:40:33.382  7198  7198 D ActivityThread: Added TimaKeyStore provider
08-30 22:40:33.392  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 22:40:33.392  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 22:40:33.392  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-30 22:40:33.392  1015  1217 I ActivityManager: Killing 6192:com.google.android.gms:car/u0a12 (adj 15): empty #31
08-30 22:40:33.392  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-30 22:40:33.402  7183  7183 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-30 22:40:33.402  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-30 22:40:33.402  1015  4151 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-30 22:40:33.402  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-30 22:40:33.402  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
,08-30 22:40:33.402  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-30 22:40:33.402  7214  7214 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.402  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
08-30 22:40:33.402  7214  7214 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:33.412  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-30 22:40:33.412  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-30 22:40:33.412  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-30 22:40:33.412  1015  1133 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-30 22:40:33.412  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.422  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.422  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.422  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-30 22:40:33.442  7232  7232 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.442  1015  1133 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7232 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-30 22:40:33.442  7232  7232 E Zygote  : v2
08-30 22:40:33.442  7232  7232 I libpersona: KNOX_SDCARD checking this for 1000
08-30 22:40:33.442  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-30 22:40:33.442  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.442  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:33.442  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-30 22:40:33.462  1015  1489 I ActivityManager: Killing 5676:com.android.vending/u0a28 (adj 15): empty #31
,08-30 22:40:33.462  7198  7198 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-30 22:40:33.472  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-30 22:40:33.472  7232  7232 D ActivityThread: Added TimaKeyStore provider
,08-30 22:40:33.472  7214  7243 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-30 22:40:33.472  1015  4151 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-30 22:40:33.472  1015  4151 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-30 22:40:33.472  1015  4151 W ActivityManager: userId = 0, bbcId = -10000
08-30 22:40:33.472  1015  4151 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-30 22:40:33.472  1015  4151 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-30 22:40:33.492  1015  1476 D PersonaManager: isKioskContainerExistOnDevice
,08-30 22:40:33.502  7232  7232 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:40:33.502  1015  4152 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 22:40:33.512  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.512  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.512  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.512  1015  4152 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 22:40:33.512  7214  7243 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-30 22:40:33.522  7214  7243 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-30 22:40:33.522  7214  7243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 22:40:33.522  7214  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:40:33.522  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:33.522  7214  7243 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-30 22:40:33.522  7250  7250 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.522  7250  7250 E Zygote  : v2
08-30 22:40:33.522  7250  7250 I libpersona: KNOX_SDCARD checking this for 10035
08-30 22:40:33.522  7250  7250 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.532  7232  7232 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-30 22:40:33.532  7250  7250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:33.532  7250  7250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-30 22:40:33.532  7250  7250 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-30 22:40:33.532  1015  4152 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7250 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-30 22:40:33.532  1015  4152 I ActivityManager: Killing 6330:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
08-30 22:40:33.532  7214  7243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 22:40:33.532  7214  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:40:33.532  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:40:33.542  1015  4151 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-30 22:40:33.542  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.542  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.542  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.542  1015  4151 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.542  1015  2973 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-30 22:40:33.542  1015  2973 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-30 22:40:33.542  7214  7243 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-30 22:40:33.542  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:33.542  7214  7243 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 22:40:33.562  7214  7243 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 22:40:33.572  7250  7250 D TimaKeyStoreProvider: TimaSignature is unavailable
08-30 22:40:33.572  7250  7250 D ActivityThread: Added TimaKeyStore provider
08-30 22:40:33.572  7266  7266 E Zygote  : MountEmulatedStorage()
08-30 22:40:33.572  7266  7266 I libpersona: KNOX_SDCARD checking this for 10156
08-30 22:40:33.572  7266  7266 E Zygote  : v2
08-30 22:40:33.572  7266  7266 I libpersona: KNOX_SDCARD not a persona
,08-30 22:40:33.572  7266  7266 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-30 22:40:33.572  7266  7266 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-30 22:40:33.572  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-30 22:40:33.572  7214  7243 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-30 22:40:33.572  7214  7243 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-30 22:40:33.582  7266  7266 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-30 22:40:33.582  1015  4151 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7266 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,08-30 22:40:33.592  1015  1503 I ActivityManager: Killing 6622:com.android.chrome/u0a81 (adj 15): empty #31
,08-30 22:40:33.592  7214  7243 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-30 22:40:33.592  7214  7243 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-30 22:40:33.592  7214  7243 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-30 22:40:33.592  1015  1382 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-30 22:40:33.592  7214  7243 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-30 22:40:33.592  7214  7243 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-30 22:40:33.592  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.592  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.592  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-30 22:40:33.592  1015  1382 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
