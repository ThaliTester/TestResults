#### Test 79763830cfa9ed9_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-26 15:42:34.315   314   314 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 15:42:34.315   314   314 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 15:42:34.635  6214  6214 D AndroidRuntime: 
08-26 15:42:34.635  6214  6214 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 15:42:34.635  6214  6214 D AndroidRuntime: CheckJNI is OFF
08-26 15:42:34.635  6214  6214 D AndroidRuntime: readGMSProperty: start
08-26 15:42:34.635  6214  6214 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:42:34.635  6214  6214 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:42:34.635  6214  6214 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 15:42:34.635  6214  6214 D AndroidRuntime: readGMSProperty: end
08-26 15:42:34.645  6214  6214 D AndroidRuntime: addProductProperty: start
08-26 15:42:34.785  6214  6214 E AffinityControl: AffinityControl: registerfunction enter
08-26 15:42:34.815  6214  6214 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 15:42:34.825  1014  1490 E PersonaManagerService: inState():  stateMachine is null !!
08-26 15:42:34.825  1014  1490 I PersonaManagerService: PersonaId don't exist
08-26 15:42:34.825  1014  1490 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 15:42:34.825  1014  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-26 15:42:34.845  1014  1490 W ActivityManager: mDVFSHelper.acquire()
08-26 15:42:34.845  1014  1490 D FocusedStackFrame: Set to : 0
08-26 15:42:34.855  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.855  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.855  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.855  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:34.855  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 15:42:34.855  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 15:42:34.865  6225  6225 E Zygote  : MountEmulatedStorage()
08-26 15:42:34.865  6225  6225 E Zygote  : v2
08-26 15:42:34.865  6225  6225 I libpersona: KNOX_SDCARD checking this for 10155
08-26 15:42:34.865  6225  6225 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:34.875  1014  1490 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6225 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:34.875  1014  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 15:42:34.875  1014  1490 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:34.875  1014  1490 D InputDispatcher: Focused application set to: xxxx
08-26 15:42:34.875  1014  1490 D InputDispatcher: Focus left window: 1475
08-26 15:42:34.875  6214  6214 D AndroidRuntime: Shutting down VM
08-26 15:42:34.875  6225  6225 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:42:34.875  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:34.875  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 15:42:34.875  6225  6225 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 15:42:34.875   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 15:42:34.885  6225  6225 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 15:42:34.885  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:34.885  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:42:34.905  6225  6225 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:34.905  6225  6225 D ActivityThread: Added TimaKeyStore provider
08-26 15:42:34.905  1014  1543 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 15:42:34.915  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 15:42:34.925  1014  1014 V ActivityManager: Display changed displayId=0
08-26 15:42:34.945  1014  1543 D PersonaManager: isKioskContainerExistOnDevice
08-26 15:42:34.955  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 15:42:34.975   257   443 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-26 15:42:34.975   257  1545 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-26 15:42:34.975  1475  1475 D Launcher: onTrimMemory. Level: 20
08-26 15:42:34.975  1475  1475 V ActivityThread: updateVisibility : ActivityRecord{2784fdc5 token=android.os.BinderProxy@4db4016 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 15:42:35.055  6225  6225 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-26 15:42:35.065  6225  6225 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9525-9527)
08-26 15:42:35.065  6225  6225 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:35.085  6214  6214 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 15:42:35.095  6225  6225 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e7dc967}
08-26 15:42:35.095  6225  6225 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:35.095  6225  6225 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 15:42:35.125  6225  6225 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 15:42:35.125  6225  6225 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:35.135  6225  6225 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 15:42:35.155  6225  6225 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-26 15:42:35.155  6225  6225 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-26 15:42:35.155  6225  6225 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-26 15:42:35.155  6225  6225 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:35.155  6225  6225 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:35.155  6225  6225 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:35.155  6225  6225 I Adreno-EGL: Local Branch: 
08-26 15:42:35.155  6225  6225 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:35.155  6225  6225 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:35.155  6225  6225 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-26 15:42:35.275  6225  6251 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-26 15:42:35.315   288   288 E SMD     : DCD OFF
08-26 15:42:35.325  6225  6225 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:35.335  6225  6225 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 15:42:35.345  6225  6225 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 15:42:35.345  6225  6225 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-26 15:42:35.355  6225  6225 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-26 15:42:35.355  6225  6225 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:35.355  6225  6225 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:42:35.405  6225  6264 D OpenGLRenderer: Render dirty regions requested: true
08-26 15:42:35.405  1014  1250 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 15:42:35.405  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 15:42:35.405  1014  1250 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:42:35.405  1014  1250 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 15:42:35.405  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:42:35.425  6225  6225 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 15:42:35.425  6225  6225 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 15:42:35.425   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-26 15:42:35.435  1014  1491 D InputDispatcher: Focus entered window: 6225
08-26 15:42:35.435  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:35.435  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 15:42:35.435  6225  6225 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 15:42:35.435  6225  6264 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 15:42:35.445  6225  6264 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-26 15:42:35.445  6225  6264 D OpenGLRenderer: Enabling debug mode 0
08-26 15:42:35.465  6225  6225 V ActivityThread: updateVisibility : ActivityRecord{47dbae token=android.os.BinderProxy@115f15b0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 15:42:35.465  1014  1343 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 15:42:35.465  1173  1173 D PanelView: There is/are notification(s) 
08-26 15:42:35.475  1014  6266 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-26 15:42:35.485  1771  1771 I SamsungIME: getCurrentCandidateView
08-26 15:42:35.505  6225  6225 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-26 15:42:35.505  6225  6225 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@115f15b0 time:109960
08-26 15:42:35.505  1014  1044 I ActivityManager: Displayed Component not be shown by security: +557ms (total +653ms)
08-26 15:42:35.505  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{397e10db u0 com.test.thalitest/.MainActivity t127} time:109963
08-26 15:42:35.505  1014  1044 W ActivityManager: mDVFSHelper.release()
08-26 15:42:35.505   257   443 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
08-26 15:42:35.505   257   441 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
08-26 15:42:35.585  1771  1771 D SamsungIME: Dismiss ExpandCandiate
08-26 15:42:35.615  6225  6225 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6225
08-26 15:42:35.725  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
08-26 15:42:35.765  1771  1771 I SamsungIME: getDebugLevel  : 0x4f4c
08-26 15:42:35.765  6225  6225 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-26 15:42:35.775  1771  1771 I SamsungIME: KeybaordView init() : load resources
08-26 15:42:35.805  1771  1771 I SamsungIME: getCurrentKeyboard
08-26 15:42:35.805  1771  1771 I SamsungIME: getTextKeyboard
08-26 15:42:35.815  1771  1771 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-26 15:42:35.865  6225  6269 D jxcore_app_log: JniHelper::setJavaVM(0xb8a21328), pthread_self() = -1191680280
,08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 15:42:35.875  6225  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11b88c5e added. We now have 1 listener(s)
,08-26 15:42:35.875  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-26 15:42:35.875  6225  6269 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 15:42:35.875  6225  6269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:35.875  6225  6269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 15:42:35.885  6225  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f7a6e55 added. We now have 1 listener(s)
08-26 15:42:35.885  6225  6269 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:42:35.895  6225  6269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:35.905  6225  6269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-26 15:42:35.905  6225  6269 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:35.905  6225  6269 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:35.905  6225  6269 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 15:42:35.905  6225  6269 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:35.915  6225  6269 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:42:35.915  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:35.915  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:35.945  6225  6225 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 15:42:36.335  1771  6272 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 15:42:36.475  6225  6277 W jxcore-log: Initializing JXcore engine
08-26 15:42:36.475  6225  6277 W jxcore-log: JXcore engine is ready
,08-26 15:42:36.525  1882  1882 E audit   : type=1400 msg=audit(1472218956.525:205): avc:  denied  { ioctl } for  pid=6277 comm="Thread-1083" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 15:42:36.525  1882  1882 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-26 15:42:36.525  1882  1882 E audit   : type=1300 msg=audit(1472218956.525:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e7c08f8 items=0 ppid=304 ppcomm=main pid=6277 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1083" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 15:42:36.525  1882  1882 E audit   : type=1320 msg=audit(1472218956.525:205): 
,08-26 15:42:36.535  6225  6277 W jxcore-log: Starting JXcore engine
,08-26 15:42:36.645  6225  6277 W jxcore-log: Platform android
08-26 15:42:36.645  6225  6277 W jxcore-log: 
08-26 15:42:36.645  6225  6277 W jxcore-log: Process ARCH arm
08-26 15:42:36.645  6225  6277 W jxcore-log: 
,08-26 15:42:36.845  6225  6277 I jxcore-log: JXcore Cordova bridge is ready!
08-26 15:42:36.845  6225  6277 I jxcore-log: 
,08-26 15:42:36.845  6225  6277 W jxcore-log: JXcore engine is started
,08-26 15:42:36.855  6225  6269 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 15:42:36.855  6225  6225 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:42:38.315   288   288 E SMD     : DCD OFF
,08-26 15:42:38.565  5430  5430 D FactoryTest: Not factory mode
,08-26 15:42:38.565  5430  5430 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 15:42:38.575  5430  5430 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 15:42:38.575  5430  5430 D MTPRx   : still no open session command from host, so toast
,08-26 15:42:38.575  5430  5430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 15:42:38.575  5430  5430 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-26 15:42:38.575  5430  5430 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:113033
08-26 15:42:38.575  1014  1339 E PersonaManagerService: inState():  stateMachine is null !!
08-26 15:42:38.575  1014  1339 I PersonaManagerService: PersonaId don't exist
,08-26 15:42:38.575  1014  1339 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 15:42:38.575  1014  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:38.575  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:38.585  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:38.585  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 15:42:38.585  1014  1339 W ActivityManager: mDVFSHelper.acquire(),
,08-26 15:42:38.595  1014  1339 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:38.605  1014  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:42:38.605  1014  1339 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-26 15:42:38.605  1014  1339 D InputDispatcher: Focused application set to: xxxx
,08-26 15:42:38.605  1014  1339 D InputDispatcher: Focus left window: 6225
08-26 15:42:38.605  5430  5430 E MTPRx   : started activity for popup
,08-26 15:42:38.615  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:42:38.615  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:38.635  5430  5430 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:38.655  5430  5430 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 15:42:38.655  1014  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 15:42:38.655  1014  1544 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 15:42:38.655  1014  1544 D InputDispatcher: Focused application set to: xxxx
,08-26 15:42:38.655  1014  1544 D InputDispatcher: Focus entered window: 6225
,08-26 15:42:38.655  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 15:42:38.665  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:42:38.665  1014  1490 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 15:42:38.665  1014  1490 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1bb060fa attribute=null, token = android.os.BinderProxy@e09114a
,08-26 15:42:38.705  5430  5430 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-26 15:42:38.715  5430  5430 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-26 15:42:38.715  5430  5430 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 15:42:38.735  6225  6225 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:42:38.735  6225  6225 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 15:42:38.735  6225  6225 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:42:38.735  6225  6225 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 15:42:38.735  1014  1473 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 15:42:38.735  1014  1473 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 15:42:38.735  1014  1473 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 15:42:38.735  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 15:42:38.735  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 15:42:38.755  6225  6225 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:42:38.755  6225  6225 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 15:42:38.755  6225  6225 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@115f15b0 time:113215
,08-26 15:42:38.755  6225  6225 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2ef5da57 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@316225f, 16908290=android.view.AbsSavedState$1@316225f}, android:focusedViewId=100}]}]
08-26 15:42:38.755  6225  6225 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 15:42:38.755  6225  6225 V ActivityThread: updateVisibility : ActivityRecord{47dbae token=android.os.BinderProxy@115f15b0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 15:42:38.755  6225  6225 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 15:42:38.755  6225  6225 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 15:42:38.765  1014  1339 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:42:39.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:40.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:41.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:41.315   288   288 E SMD     : DCD OFF
,08-26 15:42:41.585  1014  1039 W ActivityManager: mDVFSHelper.release()
,08-26 15:42:41.605  1014  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:42:41.605  1014  1491 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4135, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-26 15:42:41.605  1014  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-26 15:42:41.605  1014  1491 D BatteryService: stay LED for charging
08-26 15:42:41.605  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:42:41.615  1014  1014 I MotionRecognitionService: Plugged
,08-26 15:42:41.615  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:41.615  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:42:41.615  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:42:41.615  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:42:41.615  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-26 15:42:41.625  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:42:41.625  2656  2726 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:42:41.645  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:42:41.645  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:42:41.645  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:42:41.885  1014  2774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 15:42:42.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:42.505  1014  2729 D SSRM:n  : SIOP:: AP = 340
,08-26 15:42:43.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:42:44.315   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:42:44.315   288   288 E SMD     : DCD OFF,
,08-26 15:42:44.905  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-26 15:42:45.545  1014  1092 V AlarmManager: waitForAlarm result :4,
,08-26 15:42:45.545  1014  1092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 15:42:45.565  1903  1903 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 15:42:45.595  1014  3278 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:45.595  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 15:42:45.595  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:45.595  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:45.595  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:45.655  3836  3836 D ConnectivityManager: CallingUid : 10012, CallingPid : 3836
,08-26 15:42:45.655  1014  1543 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:42:45.655  1014  1125 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-26 15:42:45.655  1014  1125 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 15:42:45.665  1014  1125 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-26 15:42:45.665  3836  6286 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:42:45.715  3836  6287 W DriveInitializer: Background init thread started
,08-26 15:42:45.735   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 15:42:45.735   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:45.735  3836  6287 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 15:42:45.785  1014  3278 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:45.785  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 15:42:45.785  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:45.785  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:45.785  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:45.815  1014  1491 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-26 15:42:45.815  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 15:42:45.825  1014  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:45.825  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 15:42:45.825  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.825  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:45.825  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:45.835  3836  6287 W DriveInitializer: Background init thread ended
,08-26 15:42:45.845  3836  6295 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-26 15:42:45.845  3836  6295 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 15:42:45.865  1903  1903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:42:45.905  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:45.905  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:45.905  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.005  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:46.005  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 15:42:46.005  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.005  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.005  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.025  1014  1092 V AlarmManager: waitForAlarm result :4
,08-26 15:42:46.045  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:46.045  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 15:42:46.045  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:46.045  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:46.045  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.095  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.095  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.095  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.095  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.105  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.105  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.105  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.105  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.185  1014  1343 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.185  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.185  1014  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.185  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-26 15:42:46.185  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:46.185  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:46.185  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:46.185  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:46.205  6300  6300 E Zygote  : MountEmulatedStorage()
08-26 15:42:46.205  6300  6300 E Zygote  : v2
08-26 15:42:46.205  6300  6300 I libpersona: KNOX_SDCARD checking this for 10012
,08-26 15:42:46.205  6300  6300 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:46.205  6300  6300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:42:46.205  6300  6300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:46.205  6300  6300 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:46.215  1014  1343 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6300 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 15:42:46.225  6300  6300 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:46.225  6300  6300 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:46.255  6300  6300 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 15:42:46.255  6300  6300 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:42:46.295  6300  6300 I MultiDex: VM with version 2.1.0 has multidex support
08-26 15:42:46.295  6300  6300 I MultiDex: install
08-26 15:42:46.295  6300  6300 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 15:42:46.325  6300  6300 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 15:42:46.395  6300  6300 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 15:42:46.395  6300  6300 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@8672c10: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl,
08-26 15:42:46.395  6300  6300 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 15:42:46.415  6300  6300 D ChimeraCfgMgr: Reading stored module config
,08-26 15:42:46.425  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 15:42:46.435  1014  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.435  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.435  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.435  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.445  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.445  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.445  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:46.445  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.485  1903  1903 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=477a2874-2e10-4819-97cf-3d9ac770014d
,08-26 15:42:46.525  6300  6300 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 15:42:46.525  6300  6300 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 15:42:46.555  6300  6317 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 15:42:46.685  1014  1339 I art     : Explicit concurrent mark sweep GC freed 45969(2MB) AllocSpace objects, 21(336KB) LOS objects, 33% free, 28MB/42MB, paused 2.462ms total 150.177ms
08-26 15:42:46.685  1014  1339 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 15:42:46.685  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 15:42:46.685  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:46.685  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.685  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-26 15:42:46.685  1903  1903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:42:46.695  1903  1903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 15:42:46.715  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:46.715  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:46.725  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:46.725  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:46.775   283   680 D WVCdm   : Instantiating CDM.
,08-26 15:42:46.785   283   708 I WVCdm   : CdmEngine::OpenSession
08-26 15:42:46.785   283   708 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 15:42:46.785  1656  2132 I art     : Explicit concurrent mark sweep GC freed 1373(46KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 708us total 22.766ms
,08-26 15:42:46.805   283   708 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 15:42:46.825   283   708 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-26 15:42:46.825   283   708 D DrmWidevineDash: Service_Initialize: starts!
08-26 15:42:46.825   283   708 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-26 15:42:46.825   283   708 D QSEECOMAPI: : App is not loaded in QSEE
08-26 15:42:46.825   283   708 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-26 15:42:46.825   283   708 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 15:42:46.825   283   708 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 15:42:46.825   283   708 D QSEECOMAPI: : App is not loaded in QSEE
08-26 15:42:46.825   283   708 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-26 15:42:46.825   283   708 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 15:42:46.825   283   708 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 15:42:46.825   283   708 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 15:42:46.835  1903  2101 W GCoreFlp: No location to return for getLastLocation()
,08-26 15:42:46.855   283   708 D QSEECOMAPI: : Loaded image: APP id = 11
,08-26 15:42:46.855   283   708 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-26 15:42:46.865   283   708 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-26 15:42:46.865   283   708 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-26 15:42:46.865   283   708 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16fa000
08-26 15:42:46.865   283   708 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16fa000
,08-26 15:42:46.865   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:46.865   424   433 D DrmLibTime: got the req here! ret=0
08-26 15:42:46.865   424   433 D DrmLibTime: command id, time_cmd_id = 770
08-26 15:42:46.865   424   433 D DrmLibTime: time_getutcsec starts!
08-26 15:42:46.865   424   433 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-26 15:42:46.865   424   433 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-26 15:42:46.865   424   433 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-26 15:42:46.865   424   433 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-26 15:42:46.875   424   433 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-26 15:42:46.875   424   433 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-26 15:42:46.875   424   433 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-26 15:42:46.875   424   433 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-26 15:42:46.875   318   564 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-26 15:42:46.875   318  6325 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-26 15:42:46.875   318  6325 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-26 15:42:46.875   318  6325 D QC-time-services: offset is: 0 for base: 0
08-26 15:42:46.875   424   433 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-26 15:42:46.875   424   433 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-26 15:42:46.875   424   433 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472218966
08-26 15:42:46.875   424   433 D DrmLibTime: time_getutcsec returns 0, sec = 1472218966; nsec = 0
08-26 15:42:46.875   424   433 D DrmLibTime: time_getutcsec finished! 
08-26 15:42:46.875   424   433 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-26 15:42:46.875   424   433 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-26 15:42:46.875   318   564 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-26 15:42:46.875   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-26 15:42:46.875   283   708 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-26 15:42:46.875   283   708 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-26 15:42:46.875   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.875   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.875   283   708 D DrmWidevineDash: hlos api version =  9
08-26 15:42:46.875   283   708 D DrmWidevineDash: tz api version =  9
08-26 15:42:46.875   283   708 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-26 15:42:46.875   283   708 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-26 15:42:46.875   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:46.905  6300  6311 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 15:42:46.905  6300  6311 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:46.905  6300  6311 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 15:42:46.905  6300  6311 I System.out: (HTTPLog)-Thread-1064-516675965: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 15:42:46.905  6300  6311 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:46.905   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-26 15:42:46.905   283   708 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb184e960
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-26 15:42:46.905   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:46.905   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb7d78438, dataLength=8
08-26 15:42:46.905   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.905   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.905   283   708 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-26 15:42:46.905   278   974 D EnterpriseController: uids 10012
08-26 15:42:46.905   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
,08-26 15:42:46.905   278   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 15:42:46.915   283   708 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7d49b78, wrapped_rsa_key_length=1280,
08-26 15:42:46.915   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.915   283   708 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.915   283   708 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-26 15:42:46.915   283   708 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 15:42:46.915   283   680 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-26 15:42:46.915   283   680 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 15:42:46.915   283   680 I WVCdm   : CdmEngine::GenerateKeyRequest
08-26 15:42:46.915   283   680 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7d88030, idLength=0xb194e730
08-26 15:42:46.915   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb194e746, maximum = 0xb194e747
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_APIVersion: starts!,
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: hlos api version =  9
08-26 15:42:46.935   283   680 D DrmWidevineDash: tz api version =  9
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb194e7b4
,08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-26 15:42:46.935   283   680 D WVCdm   : PrepareKeyRequest: nonce=3988623244
08-26 15:42:46.935   283   680 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7d49670
08-26 15:42:46.935   283   680 D DrmWidevineDash: message_length=1599, signature=0xb7d49cb8, signature_length=0xb194e714
08-26 15:42:46.935   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
,08-26 15:42:46.945  1903  2135 I art     : Explicit concurrent mark sweep GC freed 56035(3MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 14MB/23MB, paused 1.575ms total 81.146ms
,08-26 15:42:46.945  1903  2101 I art     : WaitForGcToComplete blocked for 81.515ms for cause Explicit
,08-26 15:42:46.955  6300  6311 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:46.965  6300  6311 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6300, getuid(): 10012
,08-26 15:42:46.975  1903  2109 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:42:46.985  1903  2135 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 15:42:46.985  3836  6296 D UdcContextInitService: registered all accounts: true
,08-26 15:42:47.015  1903  2101 I art     : Explicit concurrent mark sweep GC freed 5626(297KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 13MB/23MB, paused 3.128ms total 78.210ms
,08-26 15:42:47.055  1014  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:47.055  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:47.055  1014  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:47.055  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:47.075  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:47.075  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:47.075  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:47.075  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:47.085  1014  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:47.085  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:47.085  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:47.085  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:47.095   283   680 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 15:42:47.095   283   680 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-26 15:42:47.095   283   283 I WVCdm   : CdmEngine::CloseSession
,08-26 15:42:47.095   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-26 15:42:47.095   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:47.095   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-26 15:42:47.095   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-26 15:42:47.095   283   283 I WVCdm   : L3 Terminate.
08-26 15:42:47.095   283   283 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-26 15:42:47.095   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 15:42:47.095   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-26 15:42:47.095   283   283 D DrmWidevineDash: Service_Uninitialize: starts!
08-26 15:42:47.095   283   283 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-26 15:42:47.105   283   283 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-26 15:42:47.105   283   283 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-26 15:42:47.105   283   283 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-26 15:42:47.195  1014  1490 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:42:47.195  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 15:42:47.195  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:47.195  1014  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:47.195  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:47.275  6300  6311 I qtaguid : Untagging socket 30
,08-26 15:42:47.315   288   288 E SMD     : DCD OFF
,08-26 15:42:47.595  6332  6332 I dex2oat : ----------------------------------------------------,
08-26 15:42:47.595  6332  6332 I dex2oat : <SS>: S T A R T I N G . . .
08-26 15:42:47.595  6332  6332 I dex2oat : <SS>: Zip is absent. Canceled.
08-26 15:42:47.595  6332  6332 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 15:42:47.625  6332  6332 I dex2oat : dex2oat took 28.985ms (threads: 4)
,08-26 15:42:47.635  6300  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:47.635  6300  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:47.635  6300  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:47.635  6300  6311 I Adreno-EGL: Local Branch: 
08-26 15:42:47.635  6300  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:47.635  6300  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:47.635  6300  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:47.715  6300  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:47.715  6300  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:47.715  6300  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:47.715  6300  6311 I Adreno-EGL: Local Branch: 
08-26 15:42:47.715  6300  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:47.715  6300  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:47.715  6300  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:47.765  6300  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:47.765  6300  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:47.765  6300  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:47.765  6300  6311 I Adreno-EGL: Local Branch: 
08-26 15:42:47.765  6300  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:47.765  6300  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:47.765  6300  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:48.245  1014  3278 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 15:42:48.245  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.245  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.245  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.245  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.255  1903  6298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:48.255   278   974 D EnterpriseController: uids 10012
08-26 15:42:48.255   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 15:42:48.255   278   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 15:42:48.255  1903  6298 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:48.265  1903  6298 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1903, getuid(): 10012
,08-26 15:42:48.305  1903  6298 I qtaguid : Tagging socket 68 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1903, getuid(): 10012
,08-26 15:42:48.465  1903  2135 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:42:48.465  1903  2135 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 15:42:48.475  1903  2135 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 15:42:47.126+0200, stopTime=2016-08-26 15:42:48.478+0200, duration=1352ms
,08-26 15:42:48.485  1903  6341 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:48.485   278   974 D EnterpriseController: uids 10012
08-26 15:42:48.485   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 15:42:48.485   278   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 15:42:48.485  1903  6341 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 15:42:48.485  1903  6341 I qtaguid : Tagging socket 69 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1903, getuid(): 10012
,08-26 15:42:48.535  1903  6341 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1903, getuid(): 10012
,08-26 15:42:48.535  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.785  1903  6341 I qtaguid : Untagging socket 69
,08-26 15:42:48.815  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:48.815  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-26 15:42:48.815  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:48.815  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.815  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.845  1903  2135 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 15:42:48.895  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:48.895  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.895  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.895  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.925  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:48.925  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.925  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.925  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.975  1014  3278 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:48.975  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.975  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:48.975  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:48.975  1903  6349 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:42:48.975  1903  6347 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:48.975  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:48.975  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:48.975  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:48.985  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.005  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.005  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.005  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.005  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.005  1903  6349 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:42:49.005  1903  6347 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:49.005  1014  1490 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.005  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:49.005  1014  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.005  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.035  1014  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:49.035  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:49.035  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:49.035  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:49.035  1903  6349 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 15:42:49.035  1903  6347 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 15:42:49.035  1903  6347 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-26 15:42:49.055  1903  6347 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 15:42:49.105  1014  1250 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:49.145  1903  6347 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:49.145   278   974 D EnterpriseController: uids 10012
08-26 15:42:49.145   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 15:42:49.145   278   974 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 15:42:49.145  1903  6347 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:42:49.145  1903  6347 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1903, getuid(): 10012
,08-26 15:42:49.185  1903  6347 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1903, getuid(): 10012
,08-26 15:42:49.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:49.405  1014  3278 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:49.415  1903  6347 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:49.415  1903  6347 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1903, getuid(): 10012
,08-26 15:42:49.535  1014  1250 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:49.545  1903  6347 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:49.545  1903  6347 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1903, getuid(): 10012
,08-26 15:42:49.675  1014  1544 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 15:42:49.675  1903  6347 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:49.685  1903  6347 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1903, getuid(): 10012
,08-26 15:42:49.725  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-26 15:42:49.725  6225  6277 I jxcore-log: 
,08-26 15:42:49.725  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-26 15:42:49.725  6225  6277 I jxcore-log: 
,08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:49.725  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:49.735  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:49.735  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:42:49.735  6225  6277 I jxcore-log: 
08-26 15:42:49.735  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:42:49.735  6225  6277 I jxcore-log: 
,08-26 15:42:50.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:50.315   288   288 E SMD     : DCD OFF,
,08-26 15:42:50.395  6225  6277 D executeNativeTests: Running unit tests,
,08-26 15:42:50.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:42:50.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc added. We now have 2 listener(s)
,08-26 15:42:50.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:42:50.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:50.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:42:50.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:50.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 added. We now have 2 listener(s)
08-26 15:42:50.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:50.475  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:42:50.475  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:50.485  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:50.485  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:50.485  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:50.485  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.485  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 15:42:50.485  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:50.485  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 15:42:50.485  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.495  6225  6277 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 15:42:50.495  6225  6277 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:50.495  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:50.495  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:50.495  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:50.495  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:50.495  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.495  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:42:50.495  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc removed from the list
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.495  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 removed from the list
08-26 15:42:50.495  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.495  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.495  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.495  6225  6277 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 15:42:50.495  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.495  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.495  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.495  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.495  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.495  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.495  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.495  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.495  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.495  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.495  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.505  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:50.505  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.505  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.505  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.505  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.505  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.505  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.505  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.505  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.505  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.505  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.505  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.505  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.505  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.505  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.505  6225  6277 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:50.515  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:50.515  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:50.515  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.515  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:50.515  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:50.515  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:50.515  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:50.515  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:50.515  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:50.515  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:50.525  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:50.525  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:42:50.525  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:50.535  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:42:50.535  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:50.535  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:50.535  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:50.535  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:50.545  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:42:50.565  2656  2670 D BtGatt.GattService: registerClient() - UUID=22246bc8-3edf-4722-96b4-82e30d336981
,08-26 15:42:50.605  1903  6344 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:50.605  1903  6344 I qtaguid : Tagging socket 69 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1903, getuid(): 10012
,08-26 15:42:50.605  2656  2722 D BtGatt.GattService: onClientRegistered() - UUID=22246bc8-3edf-4722-96b4-82e30d336981, clientIf=6
,08-26 15:42:50.605  6225  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:50.615  2656  2939 D BtGatt.GattService: start scan with filters
,08-26 15:42:50.615  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:42:50.615  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:50.615  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:50.615  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:50.615  2656  2725 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:50.615  2656  2725 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:50.615  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:50.615  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:50.615  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:50.625  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:50.625  6225  6277 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:50.625  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:50.625  6225  6277 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:50.625  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.625  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:50.625  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.625  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:50.625  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:50.625  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:50.625  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:50.625  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:50.625  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:50.625  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:50.635  2656  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:50.635  2656  2667 D BtGatt.GattService: stopScan() - queue size =1
08-26 15:42:50.635  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.635  2656  2725 D BtGatt.ScanManager: allow scan with filters
,08-26 15:42:50.635  2656  2670 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 15:42:50.635  2656  2725 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:42:50.635  2656  2725 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 15:42:50.635  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:50.635  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:50.635  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:50.635  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 15:42:50.635  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:50.635  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:42:50.635  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.635  2656  2725 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 15:42:50.635  2656  2725 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:50.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:50.645  2656  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 15:42:50.645  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.645  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:50.645  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:50.645  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:50.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-26 15:42:50.645  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:50.645  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.645  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:42:50.645  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.645  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.645  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.645  6225  6277 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 15:42:50.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:50.655  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:50.655  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:50.655  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:50.655  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:50.655  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:50.655  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:50.655  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:50.655  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:50.655  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.665  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:50.665  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.665  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:50.665  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:50.665  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:50.665  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:42:50.665  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:50.675  2656  2939 D BtGatt.GattService: registerClient() - UUID=3121b9ea-e8a1-4534-b432-26e76636624c
,08-26 15:42:50.695  2656  2725 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 36,
,08-26 15:42:50.705  2656  2725 D BtGatt.ScanManager: filter size is 1
,08-26 15:42:50.705  2656  2725 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 15:42:50.705  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 15:42:50.705  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.705  2656  2725 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:50.705  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:42:50.705  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.705  2656  2725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:50.715  2656  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:42:50.715  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.715  2656  2722 D BtGatt.GattService: onClientRegistered() - UUID=3121b9ea-e8a1-4534-b432-26e76636624c, clientIf=6
,08-26 15:42:50.715  6225  6237 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:50.715  2656  2667 D BtGatt.GattService: start scan with filters
,08-26 15:42:50.715  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:50.715  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:42:50.715  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:50.715  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:50.715  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:50.715  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:50.715  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:42:50.715  2656  2725 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:50.725  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:50.725  2656  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:50.725  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.725  2656  2725 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:50.725  2656  2725 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:42:50.725  2656  2725 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 15:42:50.725  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:42:50.725  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.725  2656  2725 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:50.725  2656  2725 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:50.725  2656  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:42:50.735  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.735  6225  6277 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 15:42:50.735  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:42:50.735  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.745  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.745  6225  6277 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:50.745  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.745  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:50.745  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:50.745  2656  2670 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:50.745  2656  2939 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:50.745  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:50.745  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:50.755  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:50.755  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:50.755  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.755  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:50.755  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.755  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.755  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.755  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.755  2656  2725 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 37
,08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.755  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.755  2656  2725 D BtGatt.ScanManager: filter size is 1
08-26 15:42:50.755  2656  2725 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 15:42:50.755  6225  6277 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 15:42:50.755  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:50.755  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.755  2656  2725 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:50.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:50.755  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:50.755  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:42:50.755  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.765  2656  2725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:50.765  2656  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:42:50.765  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:50.765  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:50.765  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:50.765  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:50.765  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:50.765  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:50.765  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:42:50.765  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.765  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.765  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:50.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:42:50.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:42:50.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:42:50.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:42:50.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:42:50.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:42:50.785  2656  2670 D BtGatt.GattService: registerClient() - UUID=fdfae80d-b623-436e-befc-aaea2e88b95b
,08-26 15:42:50.825  2656  2722 D BtGatt.GattService: onClientRegistered() - UUID=fdfae80d-b623-436e-befc-aaea2e88b95b, clientIf=6
,08-26 15:42:50.825  6225  6237 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:42:50.825  2656  2939 D BtGatt.GattService: start scan with filters
,08-26 15:42:50.825  1903  6344 I qtaguid : Untagging socket 69
08-26 15:42:50.825  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:50.825  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:50.825  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:50.825  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:42:50.835  2656  2725 D BtGatt.ScanManager: handling starting scan
,08-26 15:42:50.835  1903  2135 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-26 15:42:50.835  2656  2722 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:42:50.835  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.835  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:50.845  2656  2725 D BtGatt.ScanManager: allow scan with filters
08-26 15:42:50.845  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:50.845  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:50.845  2656  2725 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:42:50.845  2656  2725 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 15:42:50.845  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:42:50.845  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.845  2656  2725 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:50.845  2656  2725 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:42:50.845  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:50.845  2656  2722 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:42:50.845  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.855  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-26 15:42:50.855  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:42:50.855  6225  6277 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:50.855  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.855  6225  6277 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:42:50.855  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.855  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:50.855  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.855  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:50.855  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:50.855  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:50.855  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:50.855  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:50.855  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:50.855  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:42:50.865  2656  2667 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:42:50.865  2656  2670 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:50.875  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:50.875  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 15:42:50.875  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:42:50.875  2656  2725 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 38
,08-26 15:42:50.875  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:50.875  2656  2725 D BtGatt.ScanManager: filter size is 1
,08-26 15:42:50.875  2656  2725 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 15:42:50.875  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:50.885  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.885  6225  6277 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:50.885  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.885  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.885  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.885  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.885  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:50.885  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.885  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.885  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.885  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.885  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.885  2656  2722 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:42:50.885  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.885  2656  2725 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:42:50.885  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
08-26 15:42:50.885  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:50.885  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:42:50.885  2656  2722 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:42:50.885  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.885  2656  2725 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:42:50.885  2656  2722 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:42:50.885  2656  2722 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:42:50.885  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.885  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.895  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.895  6225  6277 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 15:42:50.895  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:50.895  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:50.895  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.895  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.895  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.895  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.895  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.895  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.895  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.895  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.895  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.895  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:50.895  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.905  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:50.905  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.905  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.905  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.905  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.905  6225  6277 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-26 15:42:50.905  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.905  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.905  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.905  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.905  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.905  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.905  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.905  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.915  6225  6277 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 15:42:50.915  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.915  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.915  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.915  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 15:42:50.915  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:50.915  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:50.915  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:50.915  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.915  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 15:42:50.915  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.915  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:42:50.915  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.915  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.915  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 15:42:50.915  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310],
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 15:42:50.925  6225  6277 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-26 15:42:50.925  6225  6277 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:50.925  6225  6277 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 15:42:50.925  6225  6277 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 15:42:50.925  6225  6277 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 15:42:50.925  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.925  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.925  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.925  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.925  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.925  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 15:42:50.925  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.925  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.925  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.925  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.925  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.925  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.925  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.925  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.935  6225  6277 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.935  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.935  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.935  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.935  6225  6359 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1147
,08-26 15:42:50.935  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.935  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.935  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.935  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.935  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 15:42:50.935  6225  6358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1147)
08-26 15:42:50.935  6225  6358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1147)
08-26 15:42:50.935  6225  6277 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-26 15:42:50.935  6225  6277 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:50.935  6225  6277 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:50.935  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:50.935  6225  6277 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 15:42:50.935  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.935  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 15:42:50.945  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
,08-26 15:42:50.945  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.945  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.945  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.945  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.945  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.945  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.945  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.945  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.945  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 15:42:50.955  6225  6225 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 15:42:50.955  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:42:50.955  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.955  6225  6225 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:50.955  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:50.955  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:50.955  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:50.955  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.955  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.955  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.955  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.955  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.955  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:50.955  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.955  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.955  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.955  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.955  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.955  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.955  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.965  6225  6360 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:42:50.965  6225  6360 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:42:50.965  6225  6277 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 15:42:50.965  6225  6277 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:50.965  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:50.965  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.965  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.965  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.965  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.965  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.965  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
,08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.965  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.965  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.965  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.965  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:50.965  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.965  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.965  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:50.965  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.965  6225  6360 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-26 15:42:50.965  6225  6360 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:42:50.965  6225  6360 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:42:50.965  6225  6360 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f143c3f
08-26 15:42:50.965  6225  6360 D BluetoothSocket: channel: 6
08-26 15:42:50.965  6225  6360 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@db3090c, channel: 6, state: LISTENING
,08-26 15:42:50.965  6225  6360 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@db3090c, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f143c3f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d44b255mSocket: android.net.LocalSocket@3754046a impl:android.net.LocalSocketImpl@3c1a5d5b fd:FileDescriptor[107]
08-26 15:42:50.965  6225  6360 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3754046a impl:android.net.LocalSocketImpl@3c1a5d5b fd:FileDescriptor[107]
08-26 15:42:50.965  6225  6360 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 15:42:50.965  6225  6360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 15:42:50.965  6225  6360 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:50.975  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.975  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6225 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:50.975  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:50.975  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1433b0dc not in the list
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:50.975  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:50.975  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:50.975  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d85e5 not in the list
08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:50.975  6225  6277 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel,: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:50.975  6225  6277 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:50.975  6225  6277 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 15:42:50.975  6225  6277 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 15:42:50.985  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:50.985  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f0da9f8 added. We now have 2 listener(s)
08-26 15:42:50.985  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:50.985  6225  6277 D BluetoothAdapter: enable()
,08-26 15:42:50.985  6225  6277 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 15:42:50.985  1014  1490 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:50.985  1014  1490 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:50.985  1014  1490 D SecContentProvider2: mCursor = null
08-26 15:42:50.985  1014  1490 D WifiService: setWifiEnabled: true pid=6225, uid=10155
08-26 15:42:50.985  1014  1490 W ActivityManager: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:50.985  1014  1490 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:50.985  1014  1490 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:50.985  1014  1490 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 15:42:50.985  1014  1490 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:50.985  1014  1490 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:50.985  1014  1490 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:50.985  1014  1490 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 15:42:50.985  1014  1490 D SettingsProvider: name = wifi_on
,08-26 15:42:50.985  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:50.985  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@206b1ed1 added. We now have 3 listener(s)
08-26 15:42:50.985  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:50.995  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:50.995  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17a5fd36 added. We now have 4 listener(s)
08-26 15:42:50.995  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:50.995  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:50.995  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@32977437 added. We now have 5 listener(s)
08-26 15:42:50.995  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:50.995  1014  1250 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 15:42:50.995  1014  1250 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:50.995  1014  1250 D SecContentProvider2: mCursor = null
,08-26 15:42:50.995  1014  1250 D WifiService: setWifiEnabled: false pid=6225, uid=10155
,08-26 15:42:50.995  1014  1250 D SettingsProvider: name = wifi_on
,08-26 15:42:51.005  1014  1123 E WifiStateMachine: WifiStateMachine: Leaving Connected state,
08-26 15:42:51.005  2094  2094 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:51.005  2094  2094 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 15:42:51.005  2094  2094 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 15:42:51.005  6225  6277 D BluetoothAdapter: disable()
08-26 15:42:51.005  2094  2094 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 15:42:51.005  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:51.005  1014  1026 D SettingsProvider: name = bluetooth_on,
,08-26 15:42:51.015  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:51.025  2656  2719 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 15:42:51.025  2656  2719 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:51.025  2656  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:42:51.025  2656  2719 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:51.025  2656  2719 D BluetoothAdapterService: updateAdapterState state is 13
08-26 15:42:51.025  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.025  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.025  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.025  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:51.025  1014  1123 E WifiNative-wlan0: do suspend true
,08-26 15:42:51.025  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.025  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.025  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.025  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.025  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.025  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:51.025  2656  2656 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 15:42:51.025  2656  2719 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:51.025  2656  2719 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-26 15:42:51.025  2656  2719 D BluetoothAdapterService: terminating service from this receiver
08-26 15:42:51.025  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1fccda41, channel: 19, state: LISTENING
,08-26 15:42:51.025  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1fccda41, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a2eb8d3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3feebe6mSocket: android.net.LocalSocket@394eb527 impl:android.net.LocalSocketImpl@24df33d4 fd:FileDescriptor[74]
08-26 15:42:51.025  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@394eb527 impl:android.net.LocalSocketImpl@24df33d4 fd:FileDescriptor[74]
,08-26 15:42:51.035  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.035  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.035  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.035  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.035  2656  2719 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 15:42:51.035  1357  1357 D BluetoothPbap: Proxy object disconnected
08-26 15:42:51.035  2656  2719 D BluetoothAdapterProperties: mDiscovering is false
,08-26 15:42:51.035  1357  1357 D PbapServerProfile: Bluetooth service disconnected
,08-26 15:42:51.035  1014  1026 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 15:42:51.035  2656  2719 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 15:42:51.035  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.035  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.045  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.045  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.045  2656  2722 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:42:51.045  2656  2722 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:42:51.045  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.045  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.055  2656  2719 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 15:42:51.055  2656  2719 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 15:42:51.055  2656  2719 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 15:42:51.055  2656  2719 E bt-btif : cmd socket is not created
08-26 15:42:51.055  2656  2719 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:42:51.055  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:51.055  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.055  2656  2795 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 15:42:51.055  2656  2795 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 15:42:51.055  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.055  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.055  2656  2795 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 15:42:51.055  2656  4981 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 15:42:51.065  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.075  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.075  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-26 15:42:51.075  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:42:51.085  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:51.085  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.085  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-26 15:42:51.085  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.085  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cbde072, channel: 5, state: LISTENING
08-26 15:42:51.085  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cbde072, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18cec90e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31677cc3mSocket: android.net.LocalSocket@12e5b940 impl:android.net.LocalSocketImpl@11c19079 fd:FileDescriptor[76]
08-26 15:42:51.085  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@12e5b940 impl:android.net.LocalSocketImpl@11c19079 fd:FileDescriptor[76]
,08-26 15:42:51.085  2656  2656 I BtOppRfcommListener: stopping Accept Thread
08-26 15:42:51.085  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@591be, channel: 12, state: LISTENING
08-26 15:42:51.085  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@591be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b9c6d28, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2bbb221fmSocket: android.net.LocalSocket@260d296c impl:android.net.LocalSocketImpl@2bc1bb35 fd:FileDescriptor[79]
08-26 15:42:51.085  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@260d296c impl:android.net.LocalSocketImpl@2bc1bb35 fd:FileDescriptor[79]
,08-26 15:42:51.085  2656  4981 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 15:42:51.085  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:42:51.085  1014  1343 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:42:51.095  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:42:51.095  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:42:51.095  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:42:51.095  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:42:51.095  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.095  1771  1771 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:42:51.095  1014  3278 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:51.095  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.095  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.095  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.095  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.095  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:51.095  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:51.105  1014  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:42:51.105  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.105  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.105  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.105  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:51.105  2656  2656 V BluetoothOppManager: cleanUp...
,08-26 15:42:51.115  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:51.115  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:51.125  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.125  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 15:42:51.125  1014  1133 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 15:42:51.125  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.125  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:51.125  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.125  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.145  6366  6366 E Zygote  : MountEmulatedStorage()
08-26 15:42:51.145  6366  6366 I libpersona: KNOX_SDCARD checking this for 10003
,08-26 15:42:51.145  6366  6366 E Zygote  : v2
08-26 15:42:51.145  6366  6366 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:51.145  1014  1133 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6366 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-26 15:42:51.145  6366  6366 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:42:51.145  6366  6366 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:51.145  6366  6366 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:51.185  6366  6366 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:51.185  6366  6366 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:51.215  6366  6366 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 15:42:51.255  6366  6366 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 15:42:51.255  6366  6366 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 15:42:51.255  6366  6366 D UserAnalysis: Create SecureDbHelper
,08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:51.255  2656  2795 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
08-26 15:42:51.255  2656  2795 W bt-btif : ag scb idx 1 not allocated
08-26 15:42:51.255  2656  2795 W bt-btif : ag scb idx 2 not allocated
08-26 15:42:51.255  2656  2795 E bt-btif : BTA AG is already disabled, ignoring ...
,08-26 15:42:51.255  2656  2867 I bt_userial_mct: exiting userial_read_thread
08-26 15:42:51.255  2656  2867 D bt_userial_mct: Leaving userial_evt_read_thread(),
08-26 15:42:51.255  2656  2722 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 15:42:51.255  2656  2797 I bt_vendor: hw_epilog_process,
08-26 15:42:51.255  2656  2722 D bt_userial_mct: userial_close
08-26 15:42:51.255  2656  2722 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 15:42:51.265  6366  6366 D IntelligenceServiceApplication: onCreate()
,08-26 15:42:51.265  1014  1250 I ActivityManager: Killing 5054:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-26 15:42:51.275  6366  6366 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 15:42:51.275  1014  1343 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 15:42:51.285  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.285  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:51.285  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.285  1014  1343 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.295  6385  6385 E Zygote  : MountEmulatedStorage()
08-26 15:42:51.295  6385  6385 E Zygote  : v2
08-26 15:42:51.295  6385  6385 I libpersona: KNOX_SDCARD checking this for 10107
08-26 15:42:51.295  6385  6385 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:51.295  6385  6385 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:51.295  1014  1343 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6385 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 15:42:51.295  6385  6385 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:51.295  6385  6385 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:42:51.295  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 15:42:51.305  6366  6366 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 15:42:51.315  6366  6366 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 15:42:51.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:51.325  6385  6385 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:51.325  6385  6385 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:51.455  6225  6225 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:42:51.485  2656  2722 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 15:42:51.485  2656  2722 I bt_vendor: bluetooth satus is on
08-26 15:42:51.485  2656  2722 I bt_vendor: bt-vendor : resetting BT status
08-26 15:42:51.485  2656  2722 I bt_vendor: Starting hciattach daemon
08-26 15:42:51.485  2656  2722 I bt_vendor: try to set false
,08-26 15:42:51.485  2656  2722 I bt_vendor: Starting hciattach daemon
,08-26 15:42:51.485  2656  2722 I bt_vendor: try to set false
,08-26 15:42:51.485  2656  2722 I bt_vendor: cleanup
,08-26 15:42:51.485  2656  2795 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-26 15:42:51.485  2656  2722 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:42:51.495  2656  2722 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 15:42:51.495  2656  2719 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 15:42:51.495  2656  2719 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:42:51.495  2656  2719 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 15:42:51.495  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 15:42:51.495  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:42:51.495  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 15:42:51.495  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:51.495  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.495  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.495  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.495  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.495  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:42:51.495  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:42:51.495  2656  2656 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:42:51.495  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService,
,08-26 15:42:51.505  2656  2656 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:42:51.505  2656  2656 D BtGatt.GattService: stop()
08-26 15:42:51.505  2656  2656 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 15:42:51.505  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.505  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.505  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.505  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.505  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.505  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.505  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:51.505  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:51.505  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:42:51.505  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.505  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.515  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:51.515  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.515  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.515  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:42:51.515  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:42:51.515  2656  2656 D HeadsetService: Received stop request...Stopping profile...
,08-26 15:42:51.515  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:42:51.525  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.525  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 15:42:51.535  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.535  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.535  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.535  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.535  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.535  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:42:51.535  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:42:51.535  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-26 15:42:51.535  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,08-26 15:42:51.545  1014  3081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:51.545  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.545  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.545  1014  3081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.545  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.545  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 15:42:51.545  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 15:42:51.545  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:42:51.545  1014  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:42:51.545  1014  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.555  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:51.555  1014  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:51.555  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.555  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.555  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:51.555  2656  2719 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:51.555  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.555  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.555  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:51.555  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:51.555  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:42:51.565  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:42:51.565  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 15:42:51.565  2656  2719 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:42:51.565  1014  1339 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:42:51.565  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:42:51.565  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.565  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.565  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:42:51.565  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:51.565  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:51.575  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:42:51.575  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:42:51.575  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-26 15:42:51.575  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:42:51.575  2656  2719 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:42:51.575  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.575  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.575  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.575  2656  2719 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:42:51.575  2656  2719 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:42:51.575  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 15:42:51.575  2656  2656 D A2dpService: Received stop request...Stopping profile...
,08-26 15:42:51.575  2656  2730 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:42:51.585  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.585  1014  1014 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:51.585  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 15:42:51.585  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:42:51.585  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:51.585  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:51.585  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:51.585  1357  1357 D A2dpProfile: Bluetooth service disconnected
,08-26 15:42:51.585  2863  2863 D BluetoothA2dp: Proxy object disconnected
,08-26 15:42:51.585  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 15:42:51.585  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:42:51.585  2656  2656 D HidService: Received stop request...Stopping profile...
,08-26 15:42:51.585  2656  2656 D HidService: Stopping Bluetooth HidService
08-26 15:42:51.585  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:42:51.585  2656  2656 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:42:51.585  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 15:42:51.595  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.595  2656  2656 D HealthService: Received stop request...Stopping profile...
,08-26 15:42:51.595  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.595  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:51.595  2656  2656 D PanService: Received stop request...Stopping profile...
08-26 15:42:51.595  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.595  1357  1357 D HidProfile: Bluetooth service disconnected
,08-26 15:42:51.595  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:51.595  2656  2656 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:42:51.595  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:51.595  1357  1357 D PanProfile: Bluetooth service disconnected
,08-26 15:42:51.605  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:42:51.615  2656  2656 D SapService: Received stop request...Stopping profile...
,08-26 15:42:51.615  2656  2656 D SapService: Stopping Bluetooth SapService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:42:51.615  1357  1357 D BluetoothMap: Proxy object disconnected
08-26 15:42:51.615  1357  1357 D MapProfile: Bluetooth service disconnected
,08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:42:51.615  2656  2656 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 15:42:51.615  2656  2731 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 15:42:51.615  2656  2656 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:42:51.615  2656  2656 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.615  1357  1357 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.615  1357  1357 D SapProfile: Bluetooth service disconnected
08-26 15:42:51.615  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:51.615  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 15:42:51.615  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:51.615  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:42:51.615  2656  2656 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-26 15:42:51.615  2656  2656 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 15:42:51.615  2656  2656 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:42:51.615  2656  2656 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:42:51.625  2656  2719 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 15:42:51.625  2656  2719 D BluetoothAdapterProperties: Setting state to 10
08-26 15:42:51.625  2656  2719 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 15:42:51.625  2656  2719 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:42:51.625  2656  2719 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 15:42:51.625  2656  2719 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:42:51.625  1357  1369 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.625  1357  1369 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.625  2656  2719 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:42:51.625  2656  2719 I BluetoothAdapterState: Entering OffState
,08-26 15:42:51.625  1357  1368 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 15:42:51.625  1357  1368 D Bluetoothsap: Unbinding service...
,08-26 15:42:51.625  1357  1369 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:42:51.625  1438  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:42:51.625  1438  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:51.635  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.635  1429  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:51.635  1453  1474 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.635  1453  1474 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:42:51.635  1357  1368 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=257 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=250 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=202 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=201 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=200 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=197 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.googl,e.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=195 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.k.c(PG:583)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  6385  6385 D StrictMode: StrictMode policy violation; ~duration=164 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:42:51.635  6385  6385 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:42:51.635  1014  1026 I ActivityManager: Killing 5492:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-26 15:42:51.635  2863  2915 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.635  2863  2915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.635  1173  1184 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.635  1173  1184 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.635  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:51.645  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.645  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.645  1903  4368 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.645  1903  4368 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.645  6225  6235 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.655  6225  6235 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.655  6225  6235 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 15:42:51.655  6225  6235 D BluetoothLeAdvertiser: Exit stop advertising
08-26 15:42:51.655  6225  6235 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 15:42:51.655  6225  6235 D BluetoothLeScanner: Exiting stopAllScan
08-26 15:42:51.655  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 15:42:51.655  2656  2667 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:42:51.655  2656  2667 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:42:51.655  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:51.655  2656  2939 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:51.655  2863  2881 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:51.655  1357  1369 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:42:51.655  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:51.665  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-26 15:42:51.665  1014  1339 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 15:42:51.665  1014  1339 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4113, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-26 15:42:51.665  1014  1339 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-26 15:42:51.665  1014  1339 D BatteryService: stay LED for charging
08-26 15:42:51.665  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 15:42:51.665  1014  1014 I MotionRecognitionService: Plugged
08-26 15:42:51.665  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:42:51.675  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 15:42:51.675  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 15:42:51.675  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 15:42:51.675  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 15:42:51.675  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
08-26 15:42:51.685  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.685  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:42:51.685  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-26 15:42:51.695  1771  1771 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 15:42:51.695  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.695  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-26 15:42:51.695  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-26 15:42:51.695  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-26 15:42:51.695  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.695  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:42:51.695  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1173  1173 D BluetoothTile:  getBluetoothState : 10
08-26 15:42:51.695  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  6385  6403 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 15:42:51.695  1014  3081 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:42:51.695  1173  1719 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1173  1719 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 15:42:51.695  1903  2118 D BluetoothAdapter: 52051256: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1903  2118 D BluetoothAdapter: 52051256: getState() :  mService = null. Returning STATE_OFF
08-26 15:42:51.695  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:42:51.695  1014  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:51.695  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 15:42:51.705  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.705  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.705  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:42:51.705  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.705  2656  2722 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 15:42:51.705  2656  2656 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:42:51.705  2656  2656 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 15:42:51.705  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:51.705  2656  2656 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 15:42:51.705  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 15:42:51.705  1014  3278 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 15:42:51.705  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 15:42:51.705  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.705  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.705  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:42:51.715  2656  2656 I art     : System.exit called, status: 0
08-26 15:42:51.715  2656  2656 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:42:51.715  1014  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 15:42:51.715  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.715  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.715  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.725  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:51.725  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:42:51.735  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:51.735  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:42:51.735  1014  3081 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:42:51.745  1014  3081 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 15:42:51.745  1014  3081 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 15:42:51.745  1014  3081 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-26 15:42:51.745  1014  3081 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:51.745  1014  3081 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 15:42:51.745  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.745  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:51.745  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.745  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.765  6417  6417 E Zygote  : MountEmulatedStorage()
08-26 15:42:51.765  6417  6417 E Zygote  : v2
08-26 15:42:51.765  6417  6417 I libpersona: KNOX_SDCARD checking this for 1002
08-26 15:42:51.765  6417  6417 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:51.765  6417  6417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:42:51.765  1014  3081 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6417 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-26 15:42:51.765  6417  6417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:51.775  6417  6417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:51.785  6417  6417 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:51.785  6417  6417 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:51.805  6417  6417 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 15:42:51.805  6417  6417 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:51.825  1014  1122 D WifiP2pService: InactiveState{ what=143375 }
,08-26 15:42:51.825  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:42:51.825  6417  6417 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 15:42:51.825  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:51.825  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:42:51.825  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:51.825  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:51.825  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:51.825  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:51.835   278   978 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:51.845  1903  4394 V NativeCrypto: Read error: ssl=0xb8f22250: I/O error during system call, Connection timed out,
08-26 15:42:51.845  1903  4394 V NativeCrypto: SSL shutdown failed: ssl=0xb8f22250: I/O error during system call, Broken pipe
08-26 15:42:51.855  1903  4394 E GCM     : Wifi connection closed with errorCode 20
08-26 15:42:51.855  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:51.855  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:51.855  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:42:51.855  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-26 15:42:51.855  1014  1123 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 15:42:51.855  1014  3278 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-26 15:42:51.855  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:51.855  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.855  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 15:42:51.855  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:51.855  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 15:42:51.865  1014  2225 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:42:51.865  1014  1122 D WifiP2pService: InactiveState{ what=131204 }
08-26 15:42:51.865  1014  1122 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 15:42:51.865  1014  2225 I qtaguid : Tagging socket 350 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,08-26 15:42:51.865  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:51.875  1014  2225 I qtaguid : Untagging socket 350
,08-26 15:42:51.875  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 15:42:51.875  1014  2225 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 15:42:51.875  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 15:42:51.875  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:51.875  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:51.875  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:51.875  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:51.875  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:51.875  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:51.875  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-26 15:42:51.875  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:51.875  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:51.885  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 15:42:51.885  1014  1122 D WifiP2pService: P2pDisablingState
08-26 15:42:51.885  1014  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 15:42:51.885  1014  1122 D WifiP2pService: p2p socket connection lost
08-26 15:42:51.885  1014  1123 E WifiNative-wlan0: do suspend true
08-26 15:42:51.885  1014  1122 D WifiP2pService: P2pDisabledState
,08-26 15:42:51.885  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-26 15:42:51.885  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,08-26 15:42:51.885  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:42:51.885  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:51.885  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:42:51.885  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:51.885  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-26 15:42:51.885  1014  1044 D WifiDisplayController: disconnect
08-26 15:42:51.885  1014  1044 D WifiDisplayController: updateConnection
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding GattService
08-26 15:42:51.885  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 15:42:51.885  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding A2dpService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding HidService
,08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding HealthService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding PanService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding SapService
,08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding SapClientService
08-26 15:42:51.895  6417  6417 D BtSettings.ProfileConfig: Adding HidDevService
08-26 15:42:51.895  6417  6417 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
08-26 15:42:51.895  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:51.895  1014  1491 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:51.895  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:51.895  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 15:42:51.895  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.895  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.895  1014  1027 D SettingsProvider: selectionArgs: false
08-26 15:42:51.895  1014  1027 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.895  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.895  1014  1027 D SettingsProvider: ret = -1
,08-26 15:42:51.895  1014  1544 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 15:42:51.895  1014  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.895  1014  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.895  1014  1544 D SettingsProvider: selectionArgs: false
08-26 15:42:51.895  1014  1544 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.895  1014  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.895  1014  1544 D SettingsProvider: ret = -1
,08-26 15:42:51.895  1014  3081 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 15:42:51.895  1014  3081 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.895  1014  3081 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.895  1014  3081 D SettingsProvider: selectionArgs: false
08-26 15:42:51.895  1014  3081 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.895  1014  3081 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  3081 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1250 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService,
08-26 15:42:51.905  1014  1250 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1250 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1250 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1250 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1250 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1250 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1543 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 15:42:51.905  1014  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1543 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1543 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 15:42:51.905  1014  1543 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1339 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 15:42:51.905  1014  1339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:42:51.905  1014  1339 D SettingsProvider: selectionArgs: false
,08-26 15:42:51.905  1014  1339 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1339 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1339 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1343 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-26 15:42:51.905  1014  1343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1343 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1343 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1343 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1343 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1026 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-26 15:42:51.905  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1026 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1026 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1026 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:42:51.905  1014  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-26 15:42:51.905  1014  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1473 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1473 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1473 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  3278 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:42:51.905  1014  3278 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  3278 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  3278 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  3278 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  3278 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  3278 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 15:42:51.905  1014  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:42:51.905  1014  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1490 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1490 D SettingsProvider: selectionArgs: 1002
08-26 15:42:51.905  1014  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1490 D SettingsProvider: ret = -1
08-26 15:42:51.905  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 15:42:51.905  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:42:51.905  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:42:51.905  1014  1491 D SettingsProvider: selectionArgs: false
08-26 15:42:51.905  1014  1491 D SettingsProvider: selectionArgs: 1002
,08-26 15:42:51.905  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:42:51.905  1014  1491 D SettingsProvider: ret = -1
,08-26 15:42:51.915  1014  1133 I ActivityManager: Killing 5579:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-26 15:42:51.915  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:42:51.925  1014  1339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:42:51.925  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.925  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-26 15:42:51.925  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.925  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.925  1903  6438 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:42:51.925  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:42:51.935  1014  1343 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:51.935  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.935  1014  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.935  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.945  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:51.945  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:51.945  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.945  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:51.945  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:51.945  3706  3706 I Hs20UtilService: Starting #8
,08-26 15:42:51.945  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:51.945  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:51.945  3706  3727 I Hs20UtilService: Message received 5007
,08-26 15:42:51.955  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:51.955  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-26 15:42:51.955  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:51.955  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:51.955  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:51.955  1014  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:51.965  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:51.965  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:51.965  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:51.965  1903  6438 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 15:42:51.965  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:42:51.965  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:51.975  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:51.975  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-26 15:42:51.975  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:51.975  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:51.975  1014  3081 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 15:42:51.975  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.975  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:51.975  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:42:51.975  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:51.975  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:51.985  1014  3081 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6439 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:51.985  6439  6439 E Zygote  : MountEmulatedStorage()
08-26 15:42:51.985  6439  6439 I libpersona: KNOX_SDCARD checking this for 10068
08-26 15:42:51.985  6439  6439 E Zygote  : v2
08-26 15:42:51.985  6439  6439 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:51.985  6439  6439 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:42:51.995  6439  6439 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:42:51.995  6439  6439 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:52.015  6439  6439 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.015  6439  6439 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.025  6439  6439 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 15:42:52.035  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:52.045  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 15:42:52.075  6439  6439 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:52.075  1014  1133 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 15:42:52.075  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.075  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.075  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.075  1014  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.095  6454  6454 E Zygote  : MountEmulatedStorage(),
08-26 15:42:52.095  6454  6454 E Zygote  : v2
,08-26 15:42:52.095  6454  6454 I libpersona: KNOX_SDCARD checking this for 10069
,08-26 15:42:52.095  6454  6454 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:52.095  6454  6454 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:42:52.095  1014  1133 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6454 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:52.105  6454  6454 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:52.105  6454  6454 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 15:42:52.125  6454  6454 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.125  6454  6454 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.145  6454  6454 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:52.155  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.155  1014  3081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.155  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 15:42:52.155  1014  3081 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 15:42:52.155  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.155  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.155  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.155  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.165  6469  6469 E Zygote  : MountEmulatedStorage()
08-26 15:42:52.165  1014  3081 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6469 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 15:42:52.165  6469  6469 E Zygote  : v2
08-26 15:42:52.165  6469  6469 I libpersona: KNOX_SDCARD checking this for 10104
08-26 15:42:52.165  6469  6469 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:52.175  1014  3081 I ActivityManager: Killing 5781:com.sec.pcw.device/1000 (adj 15): empty #31
,08-26 15:42:52.175  6469  6469 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:52.175  6469  6469 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:52.175  6469  6469 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:52.195  6469  6469 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.195  6469  6469 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.215  6469  6469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 15:42:52.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:52.375  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,08-26 15:42:52.405  6469  6493 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 15:42:52.405  6469  6493 I Babel   : MmsConfig.loadMmsSettings
08-26 15:42:52.405  6469  6493 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-26 15:42:52.405  6469  6493 I Babel   : MmsConfig.loadFromDatabase
,08-26 15:42:52.415  6469  6493 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 15:42:52.415  6469  6493 I Babel   : MmsConfig.loadFromResources
,08-26 15:42:52.415  6469  6493 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 15:42:52.415  6469  6493 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-26 15:42:52.425  1014  3081 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 15:42:52.425  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.425  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.425  1014  3081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:52.425  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:52.425  6469  6469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:52.455  6469  6469 I Babel_StickerModule: App launched.
,08-26 15:42:52.475   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 0
08-26 15:42:52.475   283   283 W QCamera2Factory: getCameraInfo: X
,08-26 15:42:52.475   283   708 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-26 15:42:52.475   283   708 W QCamera2Factory: getCameraInfo: X
,08-26 15:42:52.495  6469  6469 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:52.495  6469  6469 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:52.495  6469  6469 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 15:42:52.505  6469  6469 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 15:42:52.515  6469  6469 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 15:42:52.515  6469  6469 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:52.525  1014  2729 D SSRM:n  : SIOP:: AP = 360
,08-26 15:42:52.525  6469  6469 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 15:42:52.525  6469  6469 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 15:42:52.535  6469  6469 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 15:42:52.535  6469  6469 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 15:42:52.535  6469  6469 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 15:42:52.535  6469  6469 W VideoCapabilities: Unsupported mime video/mp43
,08-26 15:42:52.535  6469  6469 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 15:42:52.545  6469  6469 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 15:42:52.565  6469  6469 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 15:42:52.585  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-26 15:42:52.585  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-26 15:42:52.585  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.585  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:52.585  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 15:42:52.595  1014  1339 I ActivityManager: Killing 5511:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-26 15:42:52.685  1014  1122 D WifiP2pService: P2pDisabledState{ what=143375 },
,08-26 15:42:52.685  1014  1122 D WifiP2pService: DefaultState{ what=143375 },
,08-26 15:42:52.695  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:52.695  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:52.695  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.695  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.695  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.695  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-26 15:42:52.725   278   974 D EnterpriseController: uids 1000,
08-26 15:42:52.725   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 15:42:52.725   278   974 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-26 15:42:52.725  1173  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 15:42:52.725  1014  1125 E NetdConnector: NDC Command {53 network destroy 502} took too long (871ms)
08-26 15:42:52.725  1014  1122 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.725  1014  1125 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 15:42:52.725  1014  1125 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-26 15:42:52.725  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.725  1014  1125 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:52.725  3836  6286 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 15:42:52.725  1014  1125 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-26 15:42:52.725  1453  1453 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 15:42:52.725  1014  1125 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 15:42:52.725  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 15:42:52.725   278   978 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:52.735  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 15:42:52.735  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,08-26 15:42:52.735  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 15:42:52.735  1014  1120 V NetworkStats: updateIfacesLocked()
08-26 15:42:52.735  1014  2225 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:52.735  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:52.735  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:42:52.735  1014  1128 D Tethering: MasterInitialState.processMessage what=3
08-26 15:42:52.735  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.735  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:52.735  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:52.735  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:42:52.735  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:42:52.735  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:42:52.735  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-26 15:42:52.735  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 15:42:52.735  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:42:52.745  2094  2094 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:52.745  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-26 15:42:52.745  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.745  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.745  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.745  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.745  1014  1121 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 15:42:52.745  1014  1120 V NetworkStats: performPollLocked() took 10ms
,08-26 15:42:52.745  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 15:42:52.745  1014  1125 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 15:42:52.745  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 15:42:52.745  1014  1125 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 15:42:52.745  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:52.745  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:52.745  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.745  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.745  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.765  1014  1123 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:52.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:52.765  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:52.765  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:52.765  1014  1123 D SecContentProvider2: mCursor = null
08-26 15:42:52.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.765  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:52.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 15:42:52.765  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:52.765  1173  1173 D HotspotTile: onReceive : 0, 0
,08-26 15:42:52.765  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:52.765  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.765  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.765  1014  1339 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:52.765  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.765  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:52.765  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:52.775  1014  1339 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:52.775  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.775  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:52.775  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.775  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.775  3706  3706 I Hs20UtilService: Starting #9
08-26 15:42:52.775  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.775  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.775  3706  3727 I Hs20UtilService: Message received 5007
08-26 15:42:52.775  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:52.775  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:52.775  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:42:52.775  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:42:52.775  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:52.775  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:52.785  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:52.785  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:52.785  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:52.795  1014  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:52.795  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:52.795  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.795  1014  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.795  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:52.795  3706  3706 I Hs20UtilService: Starting #10
08-26 15:42:52.795  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:52.795  1014  1339 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-26 15:42:52.795  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.795  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.795  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:52.795  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:52.815  6499  6499 E Zygote  : MountEmulatedStorage(),
,08-26 15:42:52.815  6499  6499 E Zygote  : v2
08-26 15:42:52.815  6499  6499 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:52.815  6499  6499 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:42:52.815  6499  6499 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:52.815  1014  1339 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6499 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 15:42:52.815  6499  6499 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:52.825  6499  6499 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:52.855  6499  6499 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:52.855  6499  6499 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:52.865  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.865  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.875  2094  2094 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:52.875  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.875  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.875  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.875  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.875  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.875  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.885  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.885  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.885  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.885  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.885  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.885  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.895  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 15:42:52.895  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.895  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.895  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.895  1453  1453 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 15:42:52.895  1453  1453 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 15:42:52.915  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-26 15:42:52.915  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:52.915  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 15:42:52.915  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:52.915  1014  3081 I ActivityManager: Killing 4147:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-26 15:42:52.925  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.925  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.925  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.925  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.925  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.925  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.935  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.935  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.935  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.935  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.945  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.945  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.945  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.945  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.955  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.955  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.955  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.955  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.965  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.965  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.965  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:52.965  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:52.965  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 15:42:53.005  2094  2094 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 15:42:53.005  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:53.005  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:53.005  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:53.025  2094  2094 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-26 15:42:53.025  2094  2094 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 15:42:53.025  2094  2094 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 15:42:53.025  2094  2094 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
,08-26 15:42:53.025  2094  2094 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 15:42:53.035  1014  1123 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-26 15:42:53.035  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:53.035  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:53.035  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:53.035  1014  1128 D Tethering: InitialState.processMessage what=4
,08-26 15:42:53.035  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:53.035  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:53.035  1014  1128 E Tethering: No numeric data
,08-26 15:42:53.035  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:53.045  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:53.045  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:53.045  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:53.045  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 15:42:53.045  1014  1128 D Tethering: clearTetheredNotification()
,08-26 15:42:53.045  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:53.045  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:53.045  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 15:42:53.045  1173  1173 D HotspotTile: updateTetherState():false, false
,08-26 15:42:53.055  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:53.055  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:53.055  1014  1120 V NetworkStats: performPollLocked() took 11ms
,08-26 15:42:53.055  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:53.065  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:53.065  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:53.085   267   267 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6feb7c8
08-26 15:42:53.085   267   267 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 15:42:53.085   267   267 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 15:42:53.085   267   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1224820600)
,08-26 15:42:53.135   267   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-26 15:42:53.135   267   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 15:42:53.135   267   362 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1224820600) wakelock released: 1, error no: 0,
08-26 15:42:53.135   267   362 I rmt_storage: 
,08-26 15:42:53.135   267   267 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb6feb7c8
,08-26 15:42:53.235  1014  1027 I ActivityManager: Killing 5105:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-26 15:42:53.235  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:53.235  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-26 15:42:53.245  3121  3121 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-26 15:42:53.255  2094  2094 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:53.265  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:53.265  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:53.265  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 15:42:53.265  3121  3121 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
08-26 15:42:53.265  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.275  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:42:53.275  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.275  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.285  6530  6530 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.285  6530  6530 E Zygote  : v2
08-26 15:42:53.285  6530  6530 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:53.285  6530  6530 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.295  6530  6530 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.295  6530  6530 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:42:53.295  6530  6530 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 15:42:53.295  1014  1039 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 15:42:53.315  6530  6530 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.315  6530  6530 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.315   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:42:53.325   304   304 I art     : Explicit concurrent mark sweep GC freed 8730(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 870us total 27.100ms
,08-26 15:42:53.325   288   288 E SMD     : DCD OFF
08-26 15:42:53.325  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:53.325  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:53.325  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:42:53.325  2094  2094 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 15:42:53.335  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 15:42:53.335  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 15:42:53.335  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:42:53.335  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:53.335  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:53.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:53.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:53.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:53.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:53.345  6469  6469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:53.345  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:53.345  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 15:42:53.345  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:53.345   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 648us total 19.325ms
08-26 15:42:53.345  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:53.345  1173  1173 D HotspotTile: onReceive : 1, 0
,08-26 15:42:53.345  1903  2118 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:53.355  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:53.355  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:53.355  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:53.355  6530  6530 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-26 15:42:53.355  6530  6530 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 15:42:53.355  6530  6530 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 15:42:53.365   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 18.322ms
,08-26 15:42:53.375  6530  6530 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-26 15:42:53.375  6530  6530 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 15:42:53.375  6530  6530 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:42:53.375  6530  6530 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:53.375  6530  6545 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 15:42:53.375  1014  3081 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-26 15:42:53.375  1014  3081 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 15:42:53.375  1014  3081 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-26 15:42:53.375  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.375  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.375  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.375  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.395  6547  6547 E Zygote  : MountEmulatedStorage()
,08-26 15:42:53.395  6547  6547 E Zygote  : v2
08-26 15:42:53.395  6547  6547 I libpersona: KNOX_SDCARD checking this for 10111
08-26 15:42:53.395  6547  6547 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.395  6547  6547 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.395  6547  6547 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.395  1014  3081 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6547 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.395  1014  3081 I ActivityManager: Killing 5798:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-26 15:42:53.395  6547  6547 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 15:42:53.395  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 15:42:53.405  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.405  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.405  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.405  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.415  6558  6558 E Zygote  : MountEmulatedStorage()
08-26 15:42:53.415  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6558 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:53.415  6558  6558 E Zygote  : v2
08-26 15:42:53.415  6558  6558 I libpersona: KNOX_SDCARD checking this for 10009
08-26 15:42:53.415  6558  6558 I libpersona: KNOX_SDCARD not a persona,
08-26 15:42:53.415  6558  6558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.425  1726  1726 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:53.425  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 15:42:53.425  6558  6558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.425  6558  6558 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 15:42:53.425  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.425  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.425  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.425  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.435  6547  6547 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.435  6547  6547 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.445  6573  6573 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.445  6573  6573 E Zygote  : v2
08-26 15:42:53.445  6573  6573 I libpersona: KNOX_SDCARD checking this for 10145
08-26 15:42:53.445  6573  6573 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:42:53.445  6573  6573 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.445  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6573 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 15:42:53.455  6573  6573 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.455  6573  6573 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.455  1726  1726 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-26 15:42:53.455  1726  1726 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-26 15:42:53.455  1726  1726 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-26 15:42:53.455  1726  1726 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:53.465  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:53.475  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.475  6558  6558 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.475  1726  1726 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 15:42:53.475  1726  1726 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-26 15:42:53.485  1295  1754 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,08-26 15:42:53.495  1014  1339 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 15:42:53.495  6573  6573 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:53.495  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.495  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.495  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.495  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.495  6573  6573 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.515  6592  6592 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.515  6592  6592 E Zygote  : v2
08-26 15:42:53.515  6592  6592 I libpersona: KNOX_SDCARD checking this for 10081
08-26 15:42:53.515  6592  6592 I libpersona: KNOX_SDCARD not a persona,
,08-26 15:42:53.515  6592  6592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-26 15:42:53.515  1014  1339 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6592 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.515  6592  6592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.525  6592  6592 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.525  1726  1726 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-26 15:42:53.545  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.545  6592  6592 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.555  6573  6573 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-26 15:42:53.555  6573  6573 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:42:53.555  6573  6573 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 15:42:53.555  6573  6573 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:42:53.555  6573  6573 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:42:53.585  6547  6547 I MusicStore: Database version: 108
,08-26 15:42:53.585  1014  1343 I ActivityManager: Killing 5833:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-26 15:42:53.595  3729  3729 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:42:53 GMT+02:00 2016
,08-26 15:42:53.595  1014  3278 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 15:42:53.595  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:42:53.595  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.595  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:53.595  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:42:53.605  3729  3729 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.,
,08-26 15:42:53.615  1014  1490 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 15:42:53.615  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.615  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.615  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.615  1014  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.625  1014  1339 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.635  6614  6614 E Zygote  : MountEmulatedStorage()
,08-26 15:42:53.635  3729  3729 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-26 15:42:53.635  6614  6614 E Zygote  : v2
08-26 15:42:53.635  6614  6614 I libpersona: KNOX_SDCARD checking this for 10034
08-26 15:42:53.635  6614  6614 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.635  6614  6614 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.635  6614  6614 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 15:42:53.635  1014  1490 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6614 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-26 15:42:53.635  3729  3729 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-26 15:42:53.645  6614  6614 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:42:53.645  3729  3729 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 15:42:53.645  3729  6612 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 15:42:53.645  3729  6612 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 15:42:53.645  1014  1544 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.655  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 15:42:53.655  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 15:42:53.655  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.655  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:53.655  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:53.655  3729  6612 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 15:42:53.665  3729  6612 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-26 15:42:53.665  6614  6614 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.665  6614  6614 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.675  3729  3729 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-26 15:42:53.715  6614  6614 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 15:42:53.715  1014  1543 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
08-26 15:42:53.715  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.715  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.715  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.715  1014  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.725  6633  6633 E Zygote  : MountEmulatedStorage(),
08-26 15:42:53.725  6633  6633 E Zygote  : v2
08-26 15:42:53.725  6633  6633 I libpersona: KNOX_SDCARD checking this for 10113
08-26 15:42:53.725  6633  6633 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.725  6633  6633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.725  1014  1543 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6633 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.735  6633  6633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:42:53.735  6633  6633 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.735  1014  1543 I ActivityManager: Killing 5547:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-26 15:42:53.755  1014  1133 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.755  1014  1339 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast,
08-26 15:42:53.755  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.755  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.755  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.755  1014  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.765  3229  6647 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-26 15:42:53.765  6633  6633 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.765  6633  6633 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.765  3229  6647 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 15:42:53.765  3229  6647 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 15:42:53.765  6652  6652 E Zygote  : MountEmulatedStorage()
,08-26 15:42:53.765  6652  6652 E Zygote  : v2
08-26 15:42:53.765  6652  6652 I libpersona: KNOX_SDCARD checking this for 10035
08-26 15:42:53.765  6652  6652 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:53.765  6652  6652 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.775  3229  6647 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 15:42:53.775  3229  6647 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-26 15:42:53.775  1014  1339 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6652 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.775  6652  6652 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.775  6652  6652 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.785  1014  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.805  6652  6652 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:53.805  6652  6652 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:53.825  6547  6547 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 15:42:53.825  6547  6547 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 15:42:53.865  6547  6547 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 15:42:53.865  1014  1543 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.875  5929  5954 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 15:42:53.875  1014  1544 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.875  6652  6669 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-26 15:42:53.875  6652  6669 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 15:42:53.885  6652  6669 D SPPClientService: PushLog.txt file is not deleted.
,08-26 15:42:53.885  6652  6669 D SPPClientService: PushLog.txt file is not deleted.
08-26 15:42:53.885  6652  6669 D SPPClientService: ============PushLog. stop!
,08-26 15:42:53.895  6652  6652 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 15:42:53.895  1014  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.905  5987  5987 I SA      : [DM] init START
,08-26 15:42:53.905  1014  1026 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 15:42:53.905  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-26 15:42:53.905  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:53.915  1014  1490 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 15:42:53.915  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 15:42:53.915  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 15:42:53.915  5929  5954 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 15:42:53.915  5987  5987 I SA      : [DM] This device is not a Vodafone
08-26 15:42:53.915  5929  5954 D BadgeProvider: sendNotify, [notify] : null
08-26 15:42:53.915  5929  5954 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 15:42:53.915  5929  5954 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 15:42:53.915  5929  5954 D BadgeProvider: update, [UpdateCount] : 1
,08-26 15:42:53.915  1475  1475 D Launcher.Model: reloadBadges entered.
,08-26 15:42:53.925  1014  1041 D Tethering: interfaceRemoved wlan0
08-26 15:42:53.925  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 15:42:53.925  6547  6547 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 15:42:53.925  6547  6547 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2b4a6f4b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 15:42:53.925  6547  6547 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-26 15:42:53.925  6547  6547 D AndroidMusic: GMSCore installation verified
,08-26 15:42:53.925  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:53.925  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:53.925  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:53.925  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:53.935  1014  1250 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-26 15:42:53.935  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.935  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.935  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:53.935  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:53.955  6675  6675 E Zygote  : MountEmulatedStorage(),
,08-26 15:42:53.955  6675  6675 E Zygote  : v2
08-26 15:42:53.955  6675  6675 I libpersona: KNOX_SDCARD checking this for 10159
08-26 15:42:53.955  6675  6675 I libpersona: KNOX_SDCARD not a persona
08-26 15:42:53.955  1014  1250 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6675 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:42:53.955  6675  6675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:53.955  6675  6675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:53.965  6675  6675 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 15:42:53.965  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:53.965  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-26 15:42:53.965  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:53.965  5987  5987 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-26 15:42:53.965  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:53.965  5987  5987 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 15:42:53.965  5987  5987 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 15:42:53.965  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-26 15:42:53.965  5987  5987 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-26 15:42:53.975  5987  5987 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-26 15:42:53.975  5987  5987 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 15:42:53.985  6547  6547 I ConfigStore: Config Database version: 1
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
08-26 15:42:53.985  5987  5987 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-26 15:42:53.995  5987  5987 I SA      : [SCU] isHaveSA() - false
08-26 15:42:53.995  5987  5987 I SA      : support phone number id : false
08-26 15:42:53.995  5987  5987 I SA      : [DM] Supports Ref Jpn : true
,08-26 15:42:53.995  6652  6673 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
08-26 15:42:53.995  5987  5987 I SA      : [DM] init END
08-26 15:42:53.995  5987  5987 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-26 15:42:53.995  5987  5987 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 15:42:53.995  5987  5987 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 15:42:53.995  5987  5987 I SA      : [SLFUCHKMGR] constructor called
,08-26 15:42:54.005  6675  6675 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.015  6675  6675 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.025  5987  5987 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 15:42:54.025  5987  5987 I SA      : [OR] == isSIMCardReady false ==
,08-26 15:42:54.025  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:54.025  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:42:54.025  1014  1027 D SecContentProvider2: mCursor = null
,08-26 15:42:54.035  1014  1027 D WifiService: setWifiEnabled: true pid=6225, uid=10155
,08-26 15:42:54.035  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:54.035  5987  5987 I SA      : [SCU] == networkStateCheck == false
08-26 15:42:54.035  5987  5987 I SA      : [OR] onReceive END
,08-26 15:42:54.035  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:42:54.035  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:42:54.035  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 15:42:54.035  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:42:54.035  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:42:54.035  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:42:54.035  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:42:54.045  1014  1027 D SettingsProvider: name = wifi_on
,08-26 15:42:54.045  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.055  1014  1041 D Tethering: interfaceRemoved p2p0
08-26 15:42:54.055  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:54.065  1014  1343 I ActivityManager: Killing 5850:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-26 15:42:54.075  1014  1250 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:42:54.075  1014  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.075  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.075  1014  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.075  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:42:54.085  3836  3836 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 15:42:54.095  3836  4554 I iu.UploadsManager: num queued entries: 0
,08-26 15:42:54.095  3836  4554 I iu.UploadsManager: num updated entries: 0
,08-26 15:42:54.095  3836  4554 I iu.SyncManager: NEXT; no task
,08-26 15:42:54.115  1014  1133 I art     : Explicit concurrent mark sweep GC freed 55201(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.992ms total 179.566ms
,08-26 15:42:54.135  1014  3081 I ActivityManager: Killing 5764:com.android.mms/u0a46 (adj 15): empty #31
,08-26 15:42:54.145  1014  1473 I ActivityManager: Killing 5936:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-26 15:42:54.185   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 15:42:54.185   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.185  6547  6547 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 15:42:54.185   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 15:42:54.185   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.185  6547  6547 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 15:42:54.185   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 15:42:54.185   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.195  6547  6547 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 15:42:54.195  1014  3081 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-26 15:42:54.195  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.195  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.195  1014  3081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.195  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.215  1014  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 15:42:54.215  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-26 15:42:54.215  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.215  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.215  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.225  1014  1026 D CountryDetector: No listener is left
,08-26 15:42:54.225  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.225  1014  3081 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 15:42:54.225  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.225   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:54.225   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.235  6633  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 15:42:54.235  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.235   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:54.235   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.235  6633  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:54.245  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:54.245  1014  1339 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:54.255   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 15:42:54.255   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.255  6633  6705 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 15:42:54.255  1014  1343 I AudioService: getStreamVolume 3 index 0
,08-26 15:42:54.255   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 15:42:54.255   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 15:42:54.255  6633  6705 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 15:42:54.255  6547  6547 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-26 15:42:54.265  6547  6547 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-26 15:42:54.285  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 15:42:54.285  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 15:42:54.285  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.285  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.285  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.285  1014  1490 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:54.285  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.285  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:54.285  1014  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.285  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.295  1014  1544 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:54.295  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.295  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.295  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.295  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.295  1014  3081 I ActivityManager: Killing 5811:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,08-26 15:42:54.305  1014  1133 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:54.315  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 15:42:54.315  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.315   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
08-26 15:42:54.315  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.315  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.315  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.335  6709  6709 E Zygote  : MountEmulatedStorage()
08-26 15:42:54.335  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6709 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:42:54.335  6709  6709 E Zygote  : v2
08-26 15:42:54.335  6709  6709 I libpersona: KNOX_SDCARD checking this for 10002
08-26 15:42:54.335  6709  6709 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:42:54.335  6709  6709 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:54.335  6709  6709 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:42:54.335  6709  6709 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.355  6709  6709 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.365  6709  6709 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.365  1014  1343 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-26 15:42:54.365  1014  1343 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 15:42:54.365  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.365  1014  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.365  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-26 15:42:54.375  6547  6547 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-26 15:42:54.375  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:54.375  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 15:42:54.375  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.375  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.375  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:54.405  1014  1133 I ActivityManager: Killing 5970:com.wsomacp/u0a25 (adj 15): empty #31
,08-26 15:42:54.405  1014  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:54.415  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:54.415  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:54.415  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 15:42:54.425  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 15:42:54.435  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.435  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.435  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.435  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.435  6633  6633 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-26 15:42:54.445  6741  6741 E Zygote  : MountEmulatedStorage(),
08-26 15:42:54.445  6741  6741 E Zygote  : v2
08-26 15:42:54.445  6741  6741 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:42:54.445  6741  6741 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:54.445  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:54.445  1014  1027 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
08-26 15:42:54.445  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:42:54.445  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.455  6633  6633 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8918-8919)
,08-26 15:42:54.465  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 15:42:54.465  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:42:54.465  6741  6741 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.465  6633  6633 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12e5b940}
,08-26 15:42:54.465  6633  6633 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 15:42:54.465  6633  6633 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:54.495  6633  6633 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 15:42:54.495  6633  6633 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:42:54.495  6633  6633 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 15:42:54.505  6741  6741 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 15:42:54.515  6633  6633 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-26 15:42:54.515  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-26 15:42:54.515  6633  6633 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-26 15:42:54.525  6633  6633 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 15:42:54.525  6633  6633 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 15:42:54.525  6633  6633 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 15:42:54.525  6633  6633 I Adreno-EGL: Local Branch: 
08-26 15:42:54.525  6633  6633 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 15:42:54.525  6633  6633 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 15:42:54.525  6633  6633 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 15:42:54.575  6633  6769 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 15:42:54.585  6633  6633 I NSApplication: Starting up...
,08-26 15:42:54.595  1014  3278 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 15:42:54.595  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.595  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.595  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.595  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 15:42:54.615  6774  6774 E Zygote  : MountEmulatedStorage(),
08-26 15:42:54.615  6774  6774 E Zygote  : v2
08-26 15:42:54.615  6774  6774 I libpersona: KNOX_SDCARD checking this for 10120
08-26 15:42:54.615  6774  6774 I libpersona: KNOX_SDCARD not a persona,
08-26 15:42:54.615  1014  3278 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6774 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-26 15:42:54.615  6774  6774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:54.615  1014  3278 I ActivityManager: Killing 5747:com.samsung.android.sm/1000 (adj 15): empty #31
08-26 15:42:54.615  1014  3278 I ActivityManager: Killing 6009:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
,08-26 15:42:54.615  6774  6774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 15:42:54.615  6774  6774 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 15:42:54.625  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 15:42:54.635   304   304 I art     : Explicit concurrent mark sweep GC freed 8713(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 641us total 22.845ms
,08-26 15:42:54.635  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 15:42:54.645  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.645  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 15:42:54.645  6741  6741 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 15:42:54.645  6741  6741 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 15:42:54.645  6774  6774 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:54.655  6774  6774 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:54.655  1014  1133 I ActivityManager: Killing 5866:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-26 15:42:54.655   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.293ms
,08-26 15:42:54.675   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 739us total 17.608ms
,08-26 15:42:54.675  6774  6774 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:54.725  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 15:42:54.725  1014  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 15:42:54.975  1014  1473 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 15:42:54.975  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.975  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.975  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:42:54.975  1014  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:42:54.995  6801  6801 E Zygote  : MountEmulatedStorage()
08-26 15:42:54.995  6801  6801 E Zygote  : v2
08-26 15:42:54.995  6801  6801 I libpersona: KNOX_SDCARD checking this for 10125
08-26 15:42:54.995  6801  6801 I libpersona: KNOX_SDCARD not a persona
,08-26 15:42:54.995  6801  6801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:42:55.005  6801  6801 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:42:55.005  1014  1473 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6801 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-26 15:42:55.015  1014  1473 I ActivityManager: Killing 6083:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-26 15:42:55.015  6801  6801 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:42:55.045  6801  6801 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:42:55.045  6801  6801 D ActivityThread: Added TimaKeyStore provider
,08-26 15:42:55.055  6801  6801 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 15:42:55.055  6801  6801 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 15:42:55.055  6801  6801 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:42:55.075  6801  6801 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:55.075  6801  6801 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 15:42:55.085  6801  6801 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 15:42:55.085  1014  1339 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 15:42:55.085  1014  1339 I ActivityManager: Killing 6105:com.samsung.helphub/1000 (adj 15): empty #31
,08-26 15:42:55.085  1014  1041 D Tethering: interfaceAdded wlan0
,08-26 15:42:55.095  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:42:55.095  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:55.095  1014  1128 E Tethering: No numeric data
,08-26 15:42:55.105  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 15:42:55.105  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:55.105  1014  1128 D Tethering: clearTetheredNotification()
08-26 15:42:55.105  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:55.105  1014  1128 D Tethering: InitialState.processMessage what=4
08-26 15:42:55.105  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:55.105  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:55.105  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:55.105  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:55.105  1014  1128 E Tethering: No numeric data
,08-26 15:42:55.115  3706  3706 I Hs20UtilService: Starting #11
,08-26 15:42:55.115  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.115  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:55.115  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-26 15:42:55.115  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.115  1014  1041 D Tethering: interfaceAdded p2p0
08-26 15:42:55.115  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
,08-26 15:42:55.115  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
08-26 15:42:55.125  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:55.125   278   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 15:42:55.125  1173  1173 D HotspotTile: updateTetherState():false, false
08-26 15:42:55.125   278   978 D SoftapController: Softap fwReload - Ok
08-26 15:42:55.125  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:42:55.125  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:42:55.125  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:42:55.125  1014  1128 D Tethering: clearTetheredNotification()
08-26 15:42:55.125  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:55.125   278   978 D CommandListener: Setting iface cfg
08-26 15:42:55.125  1014  1120 V NetworkStats: performPollLocked() took 8ms
08-26 15:42:55.125  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.125   278   978 D CommandListener: Trying to bring down wlan0
08-26 15:42:55.125   278   978 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:55.125  1014  1123 E WifiHW  : supplicant_name : p2p_supplicant
08-26 15:42:55.135  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:42:55.135  1173  1173 D HotspotTile: updateTetherState():false, false
,08-26 15:42:55.135  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.135  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:42:55.135  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.135  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.135  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:55.135  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:55.135  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:55.135  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 15:42:55.135  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:42:55.135  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:42:55.145  1014  1120 V NetworkStats: performPollLocked() took 7ms
,08-26 15:42:55.145  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.145  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:42:55.145  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:42:55.185  6817  6817 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 15:42:55.185  6817  6817 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:42:55.185  6817  6817 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:42:55.195  6817  6817 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-26 15:42:55.195   336   336 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6817
08-26 15:42:55.195   336   336 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 15:42:55.195  6817  6817 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 15:42:55.195  6817  6817 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:55.195  6817  6817 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:42:55.195  6817  6817 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 15:42:55.195   336   336 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6817
08-26 15:42:55.195   336   336 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 15:42:55.235  1014  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-26 15:42:55.235  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:55.235  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:55.235  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.235  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.235  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.235  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:55.235  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:55.235  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 15:42:55.235  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:55.235  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:55.235  1173  1173 D HotspotTile: onReceive : 2, 0
,08-26 15:42:55.245  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:55.245  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:55.245  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:55.245  1014  1250 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:42:55.245  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:55.245  1014  1250 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:42:55.245  1014  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:55.245  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:55.255  3706  3706 I Hs20UtilService: Starting #12
08-26 15:42:55.255  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:55.255  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:55.255  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:55.255  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:55.255  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:55.355   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-26 15:42:55.365  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-26 15:42:55.435  6817  6817 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 15:42:55.435  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 15:42:55.435  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 15:42:55.445   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6817
,08-26 15:42:55.445   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 15:42:55.445  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:42:55.445  6817  6817 I wpa_supplicant: ssSupport state is = 1,
08-26 15:42:55.445  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.445  6817  6817 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.445  6817  6817 E wpa_supplicant: SIM READ ERROR
,08-26 15:42:55.445  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.445  6817  6817 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.445  6817  6817 E wpa_supplicant: SIM READ ERROR,
08-26 15:42:55.445  6817  6817 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:55.445  6817  6817 I wpa_supplicant: wpa_default_ap_write_once,
08-26 15:42:55.445  6817  6817 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:55.445  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.445  6817  6817 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-26 15:42:55.445  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.445  6817  6817 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 15:42:55.445  6817  6817 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 15:42:55.455  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 15:42:55.455  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:42:55.455  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:55.535  6817  6817 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 15:42:55.695  6817  6817 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 15:42:55.705  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 15:42:55.715  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 15:42:55.715   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6817
08-26 15:42:55.715   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 15:42:55.715  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:42:55.715  6817  6817 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:55.715  6817  6817 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:42:55.715  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 15:42:55.725  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 15:42:55.725   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6817
08-26 15:42:55.725   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 15:42:55.725  6817  6817 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 15:42:55.725  6817  6817 I wpa_supplicant: ssSupport state is = 1
08-26 15:42:55.725  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:42:55.725  6817  6817 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.725  6817  6817 E wpa_supplicant: SIM READ ERROR
08-26 15:42:55.725  6817  6817 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:42:55.725  6817  6817 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:42:55.725  6817  6817 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
08-26 15:42:55.725  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.725  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:55.725  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:55.735  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 15:42:55.735  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:42:55.735  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:55.805  6817  6817 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-26 15:42:55.805  6817  6817 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:42:55.935  6817  6817 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 15:42:55.935  6817  6817 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 15:42:55.935  6817  6817 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:55.945  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-26 15:42:55.945  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:55.945  6817  6817 I wpa_supplicant: HOTSPOT20_ENABLE called
,08-26 15:42:55.945  6817  6817 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:42:55.945  6817  6817 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:42:55.945  6817  6817 E wpa_supplicant: SIM READ ERROR
08-26 15:42:55.945  6817  6817 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:55.975  6817  6817 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 15:42:55.985  6817  6817 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:42:55.985  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-26 15:42:55.985  1014  1123 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:42:55.995  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:55.995  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:42:55.995  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.995  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.995  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:55.995  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:55.995  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:55.995  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 15:42:55.995  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:55.995  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-26 15:42:55.995  1173  1173 D HotspotTile: onReceive : 3, 0
,08-26 15:42:55.995  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-26 15:42:56.005  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:56.005  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.005  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:56.005  1014  1123 E WifiConfigStore: Not a HS20
,08-26 15:42:56.005  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:56.005  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:56.005  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.005  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:56.015  1014  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 15:42:56.015  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 15:42:56.015  1014  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:56.015  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:56.015  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-26 15:42:56.015  6817  6817 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:42:56.015  6817  6817 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 15:42:56.015  6817  6817 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:42:56.015  6817  6817 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:42:56.015  6817  6817 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-26 15:42:56.015  6817  6817 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,08-26 15:42:56.015  6817  6817 I wpa_supplicant: First Scan Start,
08-26 15:42:56.015  6817  6817 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 15:42:56.015  1014  1473 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:42:56.015  1014  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:56.015  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:42:56.025  1014  1123 D WifiNative-wlan0: Setting external_sim to 1
,08-26 15:42:56.025  3706  3706 I Hs20UtilService: Starting #13
08-26 15:42:56.025  6469  6469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:42:56.025  1014  1123 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:42:56.025  1014  1123 I WifiNative-HAL: startHal
,08-26 15:42:56.025  1014  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9ca4d88c
08-26 15:42:56.025  1014  1123 I WifiNative-HAL: Could not start hal
,08-26 15:42:56.025  1014  1123 E WifiNative-wlan0: do suspend true
,08-26 15:42:56.025  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:56.025  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 15:42:56.025  1014  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 15:42:56.035  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 15:42:56.035  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:56.035  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.035  1014  1148 I WifiNative-HAL: startHal
08-26 15:42:56.035  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dbff9bc
08-26 15:42:56.035  1014  1148 I WifiNative-HAL: Could not start hal
08-26 15:42:56.035  1014  1148 E WifiScanningService: could not start HAL
08-26 15:42:56.035   278   978 D CommandListener: Setting iface cfg
08-26 15:42:56.035   278   978 D CommandListener: Trying to bring up p2p0
,08-26 15:42:56.035  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:56.035  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:42:56.035  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:56.035  1014  1123 E WifiNative-wlan0: invaild command id : 215
08-26 15:42:56.035  1014  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:42:56.035  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:56.035  1014  1122 D WifiP2pService: P2pEnablingState
08-26 15:42:56.035  1014  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:42:56.035  1014  1014 D RttService: SCAN_AVAILABLE : 3
,08-26 15:42:56.035  1014  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:56.035  1014  1122 D WifiP2pService: P2p socket connection successful
08-26 15:42:56.035  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 15:42:56.035  1014  1122 D WifiP2pService: P2pEnabledState
,08-26 15:42:56.035  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:56.035  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:56.035  6817  6817 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:42:56.035  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 15:42:56.035  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 15:42:56.035  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:56.035  1014  1044 D WifiDisplayController: disconnect
08-26 15:42:56.035  1014  1044 D WifiDisplayController: updateConnection
08-26 15:42:56.035  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:56.035  6817  6817 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:42:56.035  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:56.045  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:42:56.045  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:56.045  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:56.045  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:56.045  6817  6817 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-26 15:42:56.045  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 15:42:56.045  1014  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:42:56.045  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:56.045  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207],
,08-26 15:42:56.045  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:42:56.045  1014  1123 E WifiNative-wlan0: invaild command id : 215
08-26 15:42:56.045  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:56.045  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:42:56.055  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 15:42:56.055  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-26 15:42:56.055  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:42:56.055  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:42:56.055  1014  1122 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-26 15:42:56.055  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  secondary type: null
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  wps: 0
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  grpcapab: 0
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  devcapab: 0
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  status: 3
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  wfdInfo: null
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-26 15:42:56.055  1014  1044 D WifiDisplayController:  SConnectInfo : null
08-26 15:42:56.055  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:42:56.055  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:56.065  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:56.065  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:56.065  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:56.065  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:56.065  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:56.065  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:56.065  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:56.065  6439  6439 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:56.075  6454  6454 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:56.085  1014  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 15:42:56.085  1014  1122 D WifiP2pService: InactiveState
,08-26 15:42:56.085  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
08-26 15:42:56.085  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:56.085  6817  6817 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:42:56.085  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-26 15:42:56.085  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:42:56.095  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.095  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:42:56.095  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:56.325   288   288 E SMD     : DCD OFF,
,08-26 15:42:56.975  1014  1343 I ActivityManager: Killing 6140:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,08-26 15:42:57.055  1014  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:42:57.055  1014  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 15:42:57.055  1014  1026 D SecContentProvider2: mCursor = null
,08-26 15:42:57.065  1014  1026 D WifiService: setWifiEnabled: false pid=6225, uid=10155
,08-26 15:42:57.065  1014  1026 D SettingsProvider: name = wifi_on
,08-26 15:42:57.085  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1,
08-26 15:42:57.085  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:42:57.085  1014  1122 D WifiP2pService: InactiveState{ what=131204 }
08-26 15:42:57.085  1014  1122 D WifiP2pService: P2pEnabledState{ what=131204 },
,08-26 15:42:57.085  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 15:42:57.095  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:42:57.095  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-26 15:42:57.095  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:42:57.095  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 15:42:57.095  1014  1122 D WifiP2pService: P2pDisablingState
08-26 15:42:57.095  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-26 15:42:57.095  1014  1122 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 15:42:57.095  1014  1122 D WifiP2pService: p2p socket connection lost
08-26 15:42:57.105   278   978 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:57.095  1014  1122 D WifiP2pService: P2pDisabledState
08-26 15:42:57.105  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 15:42:57.105  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:42:57.105  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:42:57.105  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 15:42:57.105  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:42:57.105  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 15:42:57.105  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:57.105  1014  1044 D WifiDisplayController: disconnect
08-26 15:42:57.105  1014  1044 D WifiDisplayController: updateConnection
08-26 15:42:57.105  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:42:57.105  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:57.105  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:57.115  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:57.115  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:42:57.115  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:42:57.115  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:57.115  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:57.115  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 15:42:57.115  6817  6817 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-26 15:42:57.115  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:57.125  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:57.125  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:42:57.125  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.125  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.125  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.125  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.125  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-26 15:42:57.125  1014  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 15:42:57.135  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 15:42:57.135  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 15:42:57.135  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:42:57.135  6439  6439 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:57.135  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:42:57.135  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:42:57.135  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.135  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.135  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.135  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:42:57.135  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:57.135  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 15:42:57.135  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:57.135  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 15:42:57.135  1173  1173 D HotspotTile: onReceive : 0, 0
,08-26 15:42:57.145  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:57.145  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.145  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:57.145  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:57.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:57.145  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:57.145  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:57.145  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:57.155  6454  6454 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:57.155  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 15:42:57.165  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:57.165  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:57.165  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:42:57.165  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:57.165  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:57.165  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:57.165  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:57.165  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 15:42:57.165  6439  6439 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:42:57.175  6454  6454 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:42:57.175  1014  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:57.175  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.175  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:57.175  1014  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:57.175  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.185  3706  3706 I Hs20UtilService: Starting #14
08-26 15:42:57.185  3706  3727 I Hs20UtilService: Message received 5007
,08-26 15:42:57.185  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:42:57.185  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:42:57.185  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:42:57.185  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:42:57.185  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:42:57.185  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:42:57.185  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:42:57.195  1014  1133 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:57.195  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.195  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.195  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:42:57.195  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.205  3706  3706 I Hs20UtilService: Starting #15
,08-26 15:42:57.205  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:57.205  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 15:42:57.205  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 15:42:57.205  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:57.205  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:57.255  6817  6817 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:42:57.325  6817  6817 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 15:42:57.325  6817  6817 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
08-26 15:42:57.325  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:42:57.325  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-26 15:42:57.325  6817  6817 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 15:42:57.325  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:42:57.655  6817  6817 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 15:42:57.735  6817  6817 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
08-26 15:42:57.735  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:42:57.735  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:42:57.745  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:42:57.745  6469  6469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:57.745  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 15:42:57.745  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:42:57.745  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:42:57.755  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:42:57.755  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 15:42:57.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.755  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:42:57.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 15:42:57.765  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:42:57.765  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-26 15:42:57.765  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:42:57.765  1903  2118 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:57.765  1173  1173 D HotspotTile: onReceive : 1, 0
,08-26 15:42:57.765  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:42:57.765  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 15:42:57.775  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:57.775  1014  3278 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:42:57.775  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:42:57.775  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:57.775  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:42:57.775  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:42:57.785  3706  3706 I Hs20UtilService: Starting #16,
08-26 15:42:57.785  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:42:57.785  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:42:57.785  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:42:57.785  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:42:57.785  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:42:58.455  1014  1041 D Tethering: interfaceRemoved wlan0
,08-26 15:42:58.455  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 15:42:58.615  1014  1041 D Tethering: interfaceRemoved p2p0
,08-26 15:42:58.615  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 15:42:59.235  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-26 15:42:59.235  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-26 15:42:59.235  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.235  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:59.235  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 15:42:59.245  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.245  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.245  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.245  6633  6703 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 15:42:59.265  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-26 15:42:59.265  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-26 15:42:59.265  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.265  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:59.265  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.285  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.285  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.285  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.295  1014  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:59.295  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-26 15:42:59.295  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:59.295  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.295  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.295  1014  1133 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:59.295  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-26 15:42:59.295  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:59.295  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:42:59.295  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.305  1014  1490 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:59.305  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 15:42:59.305  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.305  1014  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.305  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.315  1014  1339 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-26 15:42:59.315  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-26 15:42:59.325  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:59.325  1014  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.325  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.325   288   288 E SMD     : DCD OFF
,08-26 15:42:59.345  1014  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:42:59.345  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:42:59.345  1014  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.345  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-26 15:42:59.355  1903  1903 D WearableService: callingUid 10012, callindPid: 1903
,08-26 15:42:59.365  1014  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 15:42:59.365  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 15:42:59.365  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:42:59.365  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:42:59.365  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 15:42:59.395  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 15:42:59.405  6547  6547 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-26 15:42:59.405  6547  6832 I MusicLeanback: Conditions not met for autocaching.
08-26 15:42:59.405  6547  6832 I MusicLeanback: Stop autocaching.
,08-26 15:42:59.405  6547  6837 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-26 15:42:59.995  1014  1092 V AlarmManager: waitForAlarm result :8
,08-26 15:43:00.075  6225  6277 D BluetoothAdapter: enable()
,08-26 15:43:00.075  1014  1543 W ActivityManager: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:43:00.085  1014  1543 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 15:43:00.085  1014  1543 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:00.085  1014  1543 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 15:43:00.085  1014  1543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-26 15:43:00.085  1014  1543 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
,08-26 15:43:00.085  1014  1543 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-26 15:43:00.085  1014  1543 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:43:00.085  1014  1543 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:00.085  1014  1543 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:00.085  1014  1543 D SettingsProvider: name = bluetooth_on
,08-26 15:43:00.095  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-26 15:43:00.095  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:00.095  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-26 15:43:00.095  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 15:43:00.135  6417  6417 D BluetoothAdapterState: make
,08-26 15:43:00.135  6417  6417 I bluedroid: init
,08-26 15:43:00.145  6417  6839 I BluetoothAdapterState: Entering OffState
,08-26 15:43:00.145  6417  6417 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:43:00.145  6417  6417 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 15:43:00.145  6417  6417 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:43:00.145  6417  6417 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 15:43:00.155  6417  6417 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 15:43:00.155  6417  6417 I bluedroid: get_profile_interface socket
,08-26 15:43:00.155  6417  6417 I bluedroid: get_profile_interface map_client
,08-26 15:43:00.155  6417  6417 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 15:43:00.165  6417  6842 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 15:43:00.165  6417  6842 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 15:43:00.165  6417  6842 E BluetoothServiceJni: populateRssiValuesNative
,08-26 15:43:00.165  6417  6842 I bluedroid: getModelRssiValues
08-26 15:43:00.165  6417  6842 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:43:00.165  6417  6842 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:00.165  6417  6417 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:00.165  1014  1473 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:00.175  6417  6842 D BluetoothAdapterProperties: Name is: A5-1
08-26 15:43:00.175  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.175  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.175  1014  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.175  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.175  1014  1014 D SettingsProvider: name = bluetooth_name
,08-26 15:43:00.175  6417  6426 I bluedroid: config_hci_snoop_log
,08-26 15:43:00.175  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-26 15:43:00.175  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
08-26 15:43:00.175  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:43:00.175  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
08-26 15:43:00.175  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:43:00.185  6417  6417 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 15:43:00.185  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:00.185  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:00.195  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:43:00.195  6417  6839 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:43:00.195  6417  6839 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:00.195  6417  6839 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:00.195  6417  6839 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:00.195  6417  6839 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:43:00.195  6417  6839 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:00.195  6417  6839 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 15:43:00.195  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:43:00.205  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:00.205  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:43:00.215  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:00.215  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:00.215  1173  1173 D BluetoothTile:  getBluetoothState : 11
,08-26 15:43:00.215  6417  6839 D BluetoothSecureManager: getInstant: null
08-26 15:43:00.215  6417  6839 D BluetoothSecureManager: calling getMethod for getService
08-26 15:43:00.215  6417  6839 D BluetoothSecureManager: calling getService
,08-26 15:43:00.215  6417  6839 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1d08a17b
,08-26 15:43:00.215  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:00.215  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:00.215  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:00.215  1771  1771 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 15:43:00.215  1014  1133 D BluetoothSecureManagerService: isSecureModeEnabled
,08-26 15:43:00.215  1014  1133 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 15:43:00.225  6417  6839 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:43:00.225  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:43:00.225  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 15:43:00.225  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:00.225  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:00.225  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.225  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 15:43:00.225  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:00.225  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:00.225  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:00.225  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.225  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:00.225  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:00.225  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 15:43:00.225  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:00.225  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.225  1014  1133 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:43:00.235  1014  1339 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:00.235  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:00.235  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:00.235  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:00.235  6417  6839 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 15:43:00.235  6417  6839 D BluetoothBondStateMachine: make
,08-26 15:43:00.235  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:00.245  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 15:43:00.245  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:43:00.245  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 15:43:00.245  6417  6844 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:43:00.245  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:00.245  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 15:43:00.245  1014  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:00.245  1014  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.245  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.245  1014  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.245  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.245  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:00.255  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:00.255  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:00.255  6417  6417 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:00.255  6417  6417 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:43:00.255  6417  6417 D BtGatt.GattService: start()
08-26 15:43:00.255  6417  6417 D BtGatt.GattService: start()
08-26 15:43:00.255  6417  6417 I bluedroid: get_profile_interface gatt
,08-26 15:43:00.255  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
08-26 15:43:00.255  6417  6417 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:43:00.255  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:00.255  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.255  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:00.255  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.255  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.265  6417  6417 D BtGatt.GattService: mStartError = false
08-26 15:43:00.265  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.265  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 15:43:00.265  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:00.265  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:00.265  6417  6417 D HeadsetService: Received start request. Starting profile...
08-26 15:43:00.265  6417  6417 D HeadsetService: start()
,08-26 15:43:00.265  1014  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:00.265  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.265  6417  6417 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 15:43:00.265  6417  6417 D HeadsetStateMachine: make
,08-26 15:43:00.275  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.275  1014  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.275  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.275  6417  6417 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:43:00.275  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-26 15:43:00.275  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:00.275  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:00.285  1014  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:00.285  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.285  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.285  1014  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.285  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.285  1014  1491 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 15:43:00.285  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-26 15:43:00.285  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 15:43:00.285  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:00.285  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.285  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.285  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:00.285  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:00.285  1014  1339 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:00.285  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.285  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:00.285  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.285  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.295  1014  1543 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 15:43:00.295  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.295  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 15:43:00.295  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.295  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:00.295  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:00.295  6417  6417 I bluedroid: get_profile_interface handsfree
08-26 15:43:00.295  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:00.295  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:00.295  1014  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:00.295  1014  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.295  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:00.295  1014  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:00.305  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.305  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:43:00.305  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:00.305  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:00.305  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:00.305  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.315  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:00.315  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:00.315  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:00.315  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 15:43:00.315  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:00.315  6417  6839 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 15:43:00.315  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:00.315  6417  6417 I DualScoManager: Instantiating Dual Sco Manager
08-26 15:43:00.315  6417  6417 I DualScoManager: Set HeadsetServiceHelper
08-26 15:43:00.315  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:00.315  6417  6417 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:43:00.325  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:00.325  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:00.325  1014  3081 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 15:43:00.325  1014  3081 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:00.325  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:00.325  1014  3081 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:00.325  1014  3081 D SettingsProvider: selectionArgs: false
08-26 15:43:00.325  1014  3081 D SettingsProvider: selectionArgs: 1002
08-26 15:43:00.325  1014  3081 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:00.325  1014  3081 D SettingsProvider: ret = -1
,08-26 15:43:00.325  6417  6847 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:00.325  6417  6417 D HeadsetService: mStartError = false
08-26 15:43:00.325  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.325  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:00.325  6417  6847 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:00.325  6417  6847 D HeadsetStateMachine: map size, before remove : 0
,08-26 15:43:00.325  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:00.325  6417  6847 D HeadsetStateMachine: map size, after remove: 0
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:00.325  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:00.325  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 15:43:00.325  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:43:00.325  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 15:43:00.335  6417  6839 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:43:00.335  6417  6417 D A2dpService: Received start request. Starting profile...
,08-26 15:43:00.335  6417  6417 D A2dpService: start()
,08-26 15:43:00.335  6417  6417 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 15:43:00.335  6417  6417 I bluedroid: get_profile_interface avrcp
,08-26 15:43:00.345  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:00.345  6417  6417 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:00.345  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:43:00.365  6417  6417 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:43:00.365  6417  6851 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 15:43:00.365  6417  6417 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 15:43:00.365  6417  6417 D A2dpStateMachine: make
,08-26 15:43:00.365  6417  6417 I bluedroid: get_profile_interface a2dp
,08-26 15:43:00.365  6417  6853 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 15:43:00.365  6417  6417 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 15:43:00.365  6417  6417 D A2dpService: mStartError = false
08-26 15:43:00.365  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.365  6417  6852 D A2dpStateMachine: Enter Disconnected: -2
,08-26 15:43:00.375  6417  6417 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 15:43:00.375  6417  6417 D HidService: Received start request. Starting profile...
08-26 15:43:00.375  6417  6417 D HidService: start()
08-26 15:43:00.375  6417  6417 I bluedroid: get_profile_interface hidhost
08-26 15:43:00.375  6417  6417 D HidService: setHidService(): set to: null
08-26 15:43:00.375  6417  6417 D HidService: mStartError = false
08-26 15:43:00.375  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.375  6417  6417 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 15:43:00.375  1429  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 15:43:00.375  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 15:43:00.375  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:43:00.375  1429  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:43:00.385  6417  6417 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 15:43:00.385  6417  6417 D HealthService: Received start request. Starting profile...
08-26 15:43:00.385  6417  6417 D HealthService: start()
,08-26 15:43:00.385  6417  6851 D BluetoothMediaBrowser: no now playing list
08-26 15:43:00.385  6417  6851 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 15:43:00.385  6417  6417 I bluedroid: get_profile_interface health
,08-26 15:43:00.385  6417  6417 D HealthService: mStartError = false,
08-26 15:43:00.385  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
08-26 15:43:00.385  6417  6417 D HeadsetStateMachine: Proxy object connected
08-26 15:43:00.385  6417  6417 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0,
08-26 15:43:00.385  6417  6417 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 15:43:00.385  6417  6847 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:43:00.385  6417  6417 D PanService: Received start request. Starting profile...
,08-26 15:43:00.385  6417  6417 D PanService: start()
08-26 15:43:00.385  6417  6417 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 15:43:00.385  6417  6417 I bluedroid: get_profile_interface pan
,08-26 15:43:00.395  6417  6417 D PanService: mStartError = false
,08-26 15:43:00.395  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.395  6417  6417 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 15:43:00.395  6417  6847 D HeadsetStateMachine: Disconnected process message: 18
,08-26 15:43:00.395  6417  6417 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-26 15:43:00.395  6417  6417 D BluetoothMapService: Received start request. Starting profile...
,08-26 15:43:00.395  6417  6417 D BluetoothMapService: start()
,08-26 15:43:00.395  6417  6417 D BluetoothMapService: mStartError = false
,08-26 15:43:00.395  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:00.405  6417  6417 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 15:43:00.405  6417  6417 D SapService: Received start request. Starting profile...
08-26 15:43:00.405  6417  6417 D SapService: start()
08-26 15:43:00.405  6417  6417 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:43:00.405  6417  6417 I bluedroid: get_profile_interface sap
08-26 15:43:00.405  6417  6417 D SapService: mStartError = false
08-26 15:43:00.405  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
08-26 15:43:00.405  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 15:43:00.405  6417  6417 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:43:00.405  6417  6417 D BluetoothA2dp: Proxy object connected
08-26 15:43:00.405  6417  6417 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 15:43:00.405  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 15:43:00.405  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 15:43:00.405  6417  6847 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:43:00.405  6417  6847 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
08-26 15:43:00.405  6417  6847 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:43:00.405  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 15:43:00.405  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:43:00.435  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 15:43:00.435  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:43:00.445  6417  6839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 15:43:00.445  6417  6839 I bluedroid: enable
,08-26 15:43:00.445  6417  6839 I bt_hci_bdroid: init
,08-26 15:43:00.445  6417  6857 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 15:43:00.445  6417  6839 I bt_vendor: bt-vendor : init
,08-26 15:43:00.445  6417  6839 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 15:43:00.445  6417  6839 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:43:00.445  6417  6839 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,08-26 15:43:00.445  6417  6839 D bt_userial_mct: userial_init
,08-26 15:43:00.445  6417  6839 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 15:43:00.445  6417  6839 I bt_vendor: Starting hciattach daemon
08-26 15:43:00.445  6417  6839 I bt_vendor: try to set false
,08-26 15:43:00.455  6417  6839 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 15:43:00.455  6417  6839 I bt_vendor: Starting hciattach daemon
08-26 15:43:00.455  6417  6839 I bt_vendor: try to set true
,08-26 15:43:00.475  6861  6861 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 15:43:00.525  6867  6867 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 15:43:00.535  6868  6868 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:43:00.555  6870  6870 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:43:00.565  6871  6871 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 15:43:00.575  6872  6872 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:43:00.585  6873  6873 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 15:43:00.825  6876  6876 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-26 15:43:00.835  6877  6877 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:43:00.865  6417  6839 I bt_vendor: bluetooth satus is on,
08-26 15:43:00.865  6417  6859 D bt_userial_mct: userial_open(port:0)
08-26 15:43:00.865  6417  6859 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 15:43:00.865  6417  6859 I bt_vendor: Done intiailizing UART,
,08-26 15:43:00.865  6417  6859 I bt_vendor: Done intiailizing UART,
08-26 15:43:00.865  6417  6859 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 15:43:00.865  6417  6859 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 15:43:00.875  6417  6879 D bt_userial_mct: Entering userial_read_thread()
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_SAP
,08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:43:00.875  6417  6857 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 15:43:00.885  6417  6857 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 15:43:00.885  6417  6857 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 15:43:00.885  6417  6857 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 15:43:00.975  6417  6857 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 15:43:00.985  6417  6857 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f6c6e9 
,08-26 15:43:00.985  6417  6857 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f6c6e9 
,08-26 15:43:00.995  6417  6842 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 15:43:01.005  6417  6842 E bt-btif : Calling BTA_HhEnable
,08-26 15:43:01.005  6417  6842 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 15:43:01.005  6417  6842 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 15:43:01.005  6417  6842 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:43:01.005  6417  6842 I bluedroid: getModelRssiValues
,08-26 15:43:01.005  6417  6842 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:43:01.005  6417  6842 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:01.005  1014  1014 D SettingsProvider: name = bluetooth_name
,08-26 15:43:01.015  6417  6842 D BluetoothAdapterProperties: Name is: A5-1
,08-26 15:43:01.015  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.015  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.025  6417  6842 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:43:01.025  6417  6842 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:01.025  6417  6842 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:01.025  6417  6842 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-26 15:43:01.025  6417  6842 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 15:43:01.025  6417  6842 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 15:43:01.025  6417  6842 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 15:43:01.025  6417  6842 E bt-btif : btif_sock_init: !vhci_init
08-26 15:43:01.025  6417  6842 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 15:43:01.035  6417  6842 D IOP_DB_BT: db_open: db_open : handle 3028627472l, read 13894 bytes onto local cache
,08-26 15:43:01.035  6417  6842 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 15:43:01.035  6417  6842 D IOP_DB_BT: db_query: result 1,
08-26 15:43:01.035  6417  6842 I         : iop_db_open: iop_db_open status 0
08-26 15:43:01.035  6417  6842 D bte_conf: Device ID record 1 : primary
08-26 15:43:01.035  6417  6842 D bte_conf:   vendorId            = 0075
,08-26 15:43:01.035  6417  6842 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:01.035  6417  6842 D bte_conf:   product             = 0100
08-26 15:43:01.035  6417  6842 D bte_conf:   version             = 0200
08-26 15:43:01.035  6417  6842 D bte_conf:   clientExecutableURL = 
08-26 15:43:01.035  6417  6842 D bte_conf:   serviceDescription  = 
08-26 15:43:01.035  6417  6842 D bte_conf:   documentationURL    = 
08-26 15:43:01.035  6417  6842 D bte_conf: bte_load_did_conf no section named DID2.
08-26 15:43:01.035  6417  6879 E bt_mct  : hci lib postload completed
08-26 15:43:01.035  6417  6842 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:43:01.035  6417  6839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 15:43:01.035  6417  6839 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:01.035  6417  6839 D BluetoothAdapterProperties: State =  11
,08-26 15:43:01.035  1014  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:43:01.035  6417  6839 D BluetoothAdapterProperties: Setting state to 12
,08-26 15:43:01.035  6417  6839 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 15:43:01.045  6417  6842 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:01.045  6417  6842 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:01.045  6417  6842 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:01.045  1014  1544 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 15:43:01.045  1014  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:01.045  1014  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:01.045  1014  1544 D SettingsProvider: selectionArgs: false
08-26 15:43:01.045  1014  1544 D SettingsProvider: selectionArgs: 1002
08-26 15:43:01.045  1014  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:01.045  1014  1544 D SettingsProvider: ret = -1
08-26 15:43:01.045  6417  6839 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:01.045  6417  6839 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:43:01.045  1014  3278 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.045  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.055  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.055  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.055  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.065  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.065  6417  6839 D BluetoothAdapterService: Autoconnection is available 
08-26 15:43:01.065  1357  1368 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.065  1357  1368 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:01.065  6417  6839 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:43:01.065  6417  6839 D BluetoothAdapterService: starting service from this receiver
08-26 15:43:01.065  1357  1369 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:43:01.065  1357  1369 D Bluetoothsap: Binding service...
,08-26 15:43:01.065  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:01.065  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 15:43:01.075  1357  1369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 15:43:01.075  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.075  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:01.075  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.075  6417  6839 I BluetoothAdapterState: Entering On State from state = 11
,08-26 15:43:01.075  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:01.075  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 15:43:01.085  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.085  6417  6417 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 15:43:01.085  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.085  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.085  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:01.085  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:01.085  1357  1369 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 15:43:01.095  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:01.095  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.095  6417  6417 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:43:01.095  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.095  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.095  1014  1343 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:01.095  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.095  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.095  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.095  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.095  2863  2881 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.105  1357  1357 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:43:01.105  1357  1357 D SapProfile: Bluetooth service connected
08-26 15:43:01.105  1357  1357 D Bluetoothsap: getConnectedDevices()
,08-26 15:43:01.105  6417  6883 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 15:43:01.105  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:43:01.105  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.105  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.105  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.105  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-26 15:43:01.105  6417  6883 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:01.105  6417  6883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:01.105  2863  2881 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.105  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.105  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.105  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.105  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.105  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.105  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.115  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.115  6417  6425 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:01.115  6417  6883 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-26 15:43:01.115  6417  6883 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.115  6417  6883 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.115  6417  6883 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18cec90e
08-26 15:43:01.115  6417  6883 D BluetoothSocket: channel: 19
08-26 15:43:01.115  1357  1368 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:01.115  6417  6883 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 15:43:01.115  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 15:43:01.115  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.115  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-26 15:43:01.115  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.115  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.115  1438  1464 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.115  1438  1464 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.115  1357  1357 D BluetoothPbap: Proxy object connected
08-26 15:43:01.115  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:01.115  1453  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.115  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 15:43:01.115  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:01.125  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.125  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.125  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.125  1453  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:01.125  1429  1437 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.125  1429  1437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:01.125  1453  1972 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:01.125  1453  1972 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:01.125  1357  6697 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:01.125  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 15:43:01.125  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.125  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.125  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.125  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.125  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.125  1357  1357 D BluetoothMap: Proxy object connected,
08-26 15:43:01.125  1357  1357 D MapProfile: Bluetooth service connected
08-26 15:43:01.125  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.125  1357  1357 D BluetoothMap: getConnectedDevices()
08-26 15:43:01.125  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:01.135  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.135  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.135  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.135  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:43:01.135  2863  2877 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.135  2863  2877 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.135  1173  3801 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.135  1173  3801 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:01.135  1357  1369 D BluetoothPan: Binding service...
,08-26 15:43:01.135  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 15:43:01.135  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.135  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.135  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.135  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.135  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.135  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.135  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:01.135  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:01.135  1357  1357 D PanProfile: Bluetooth service connected
08-26 15:43:01.135  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:43:01.135  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.135  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.135  6385  6400 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.135  6385  6400 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.145  1357  1368 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.145  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:01.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:01.145  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.145  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.145  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.145  1357  1368 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:43:01.145  1903  4369 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.145  1903  4369 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.145  6225  6235 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.145  6225  6235 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.145  1357  1357 D HeadsetProfile: Bluetooth service connected
08-26 15:43:01.145  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:01.145  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:01.145  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:01.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:01.145  1014  1043 D BluetoothPan: Binding service...
08-26 15:43:01.145  1014  1014 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.145  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:01.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 15:43:01.145  6417  6695 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:01.145  6417  6695 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:01.145  2863  2915 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:01.145  2863  2915 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:01.145  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:01.145  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:01.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.155  1357  6697 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:43:01.155  2863  2863 D BluetoothA2dp: Proxy object connected
08-26 15:43:01.155  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:43:01.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.155  1357  1369 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:01.155  1357  1357 D BluetoothInputDevice: Proxy object connected
,08-26 15:43:01.155  1357  1369 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:01.155  1357  1357 D HidProfile: Bluetooth service connected
,08-26 15:43:01.155  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:01.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:01.155  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.155  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.155  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 15:43:01.155  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:43:01.165  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.165  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-26 15:43:01.165  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:01.165  1357  1357 D BluetoothA2dp: Proxy object connected
,08-26 15:43:01.165  1357  1357 D A2dpProfile: Bluetooth service connected
,08-26 15:43:01.165  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:43:01.165  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f7a6e55, true
,08-26 15:43:01.165  1429  1429 D BluetoothHeadset: registerMessageListener
,08-26 15:43:01.175  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-26 15:43:01.175  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:43:01.175  1771  1771 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 15:43:01.175  1173  1173 D BluetoothTile:  getBluetoothState : 12
,08-26 15:43:01.175  1014  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:01.175  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.185  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:01.185  6417  6426 D HeadsetService: registerMessageListener
08-26 15:43:01.185  6417  6426 D HeadsetService: registerMessageListener
08-26 15:43:01.185  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:01.185  6417  6847 D HeadsetStateMachine: Disconnected process message: 70
08-26 15:43:01.185  6417  6847 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@20220f2f
,08-26 15:43:01.185  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-26 15:43:01.185  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 15:43:01.185  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.185  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:01.185  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:01.185  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:01.185  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:01.185  6417  6888 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 15:43:01.195  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 15:43:01.195  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 15:43:01.195  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 15:43:01.195  1014  1473 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.195  1014  1339 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 15:43:01.195  1357  1357 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 15:43:01.195  1357  1357 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 15:43:01.195  1357  1357 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 15:43:01.195  1357  1357 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 15:43:01.195  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:01.195  6417  6847 D HeadsetStateMachine: Disconnected process message: 9
,08-26 15:43:01.195  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:01.195  6417  6847 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 15:43:01.205   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 15:43:01.205  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
08-26 15:43:01.205   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:43:01.205   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-26 15:43:01.205   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 15:43:01.205   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:43:01.205   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:43:01.205   283   283 V audio_hw_primary: adev_set_parameters: exit
08-26 15:43:01.205  6417  6847 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:43:01.205  6417  6888 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:43:01.205  6417  6888 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:01.215  6417  6888 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-26 15:43:01.215  6417  6888 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.215  6417  6888 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.215  6417  6888 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c7af93c
,08-26 15:43:01.215  6417  6888 D BluetoothSocket: channel: 5
,08-26 15:43:01.215  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:01.215  1014  1544 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 15:43:01.215  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.215  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:01.215  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.215  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:01.225  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:01.225  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:01.235  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:01.235  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:43:01.235  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:01.235  6417  6417 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:01.245  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:01.245  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.245  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.245  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:01.245  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:01.255  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:01.255  1014  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:01.255  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:01.265  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.265  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:01.265  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:01.265  1903  6894 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:43:01.275  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 15:43:01.275  1014  1491 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:01.275  1014  1343 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:01.275  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.275  1014  1343 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:01.275  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:01.295  6417  6898 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 15:43:01.295  6417  6898 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:01.295  6417  6898 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-26 15:43:01.295  6417  6898 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:01.295  6417  6898 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:01.295  6417  6898 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b9c6d28
08-26 15:43:01.295  6417  6898 D BluetoothSocket: channel: 12
08-26 15:43:01.295  6417  6898 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:01.295  1014  3278 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:01.295  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:01.295  1014  3278 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:01.295  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:01.305  1903  6894 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 15:43:01.735  1014  1250 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:43:01.735  1014  1250 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4153, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-26 15:43:01.735  1014  1250 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-26 15:43:01.735  1014  1250 D BatteryService: stay LED for charging
,08-26 15:43:01.735  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:43:01.735  1014  1014 I MotionRecognitionService: Plugged
,08-26 15:43:01.745  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:43:01.745  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:43:01.745  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:43:01.745  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:43:01.745  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-26 15:43:01.765  6417  6417 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:43:01.765  6417  6847 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:43:01.765  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:43:01.775  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:43:01.775  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:43:01.885  1014  2774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 15:43:01.925  1014  1343 I art     : Explicit concurrent mark sweep GC freed 47299(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.371ms total 162.587ms
,08-26 15:43:02.325   288   288 E SMD     : DCD OFF
,08-26 15:43:02.535  1014  2729 D SSRM:n  : SIOP:: AP = 350
,08-26 15:43:03.095  6225  6277 D BluetoothAdapter: disable()
,08-26 15:43:03.095  1014  1491 D SettingsProvider: name = bluetooth_on
,08-26 15:43:03.115  6417  6839 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 15:43:03.115  6417  6839 D BluetoothAdapterProperties: Setting state to 13
08-26 15:43:03.115  6417  6839 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,08-26 15:43:03.115  6417  6839 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:03.115  1014  3081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.115  6417  6839 D BluetoothAdapterService: updateAdapterState state is 13
08-26 15:43:03.115  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.115  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.115  1014  3081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.115  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:03.115  6417  6839 D BluetoothAdapterService: Autoconnection is available 
08-26 15:43:03.115  6417  6839 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 15:43:03.115  6417  6839 D BluetoothAdapterService: terminating service from this receiver
08-26 15:43:03.115  6417  6417 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 15:43:03.115  6417  6417 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1fccda41, channel: 19, state: LISTENING
08-26 15:43:03.115  6417  6417 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1fccda41, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18cec90e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3feebe6mSocket: android.net.LocalSocket@394eb527 impl:android.net.LocalSocketImpl@24df33d4 fd:FileDescriptor[75]
08-26 15:43:03.115  6417  6417 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@394eb527 impl:android.net.LocalSocketImpl@24df33d4 fd:FileDescriptor[75]
,08-26 15:43:03.125  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.125  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-26 15:43:03.125  1173  1173 D BluetoothTile:  onBluetoothStateChange:
08-26 15:43:03.125  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 15:43:03.135  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:03.135  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:03.135  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.135  1173  1173 D BluetoothTile:  getBluetoothState : 13
,08-26 15:43:03.135  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:03.135  1771  1771 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:03.135  1014  1343 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:03.145  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.145  1014  1490 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:03.145  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:03.145  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:43:03.145  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.145  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:03.155  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:03.155  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:03.155  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.155  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.155  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.155  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.155  1014  3081 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:03.155  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.155  6417  6839 D BluetoothAdapterProperties: onBluetoothDisable(),
08-26 15:43:03.155  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:03.155  6417  6839 D BluetoothAdapterProperties: mDiscovering is false
08-26 15:43:03.155  1014  3278 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:43:03.155  6417  6839 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,08-26 15:43:03.165  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.165  1014  3081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:03.165  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:03.165  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.165  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:03.165  6225  6225 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:03.165  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:03.175  1014  1491 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:03.175  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.175  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.175  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.175  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:03.175  1357  1357 D BluetoothPbap: Proxy object disconnected
,08-26 15:43:03.185  1357  1357 D PbapServerProfile: Bluetooth service disconnected
,08-26 15:43:03.185  6417  6842 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:43:03.185  6417  6842 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:03.195  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:03.195  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:03.195  6417  6839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 15:43:03.195  6417  6839 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 15:43:03.195  6417  6839 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 15:43:03.195  6417  6839 E bt-btif : BTM_SEC_CLR[17]: id 
,08-26 15:43:03.195  6417  6839 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:43:03.195  6417  6857 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 15:43:03.195  6417  6857 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 15:43:03.195  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:03.195  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:03.195  6417  6857 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 15:43:03.195  6417  6898 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 15:43:03.205  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:03.205  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:03.205  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.205  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
08-26 15:43:03.205  6417  6417 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1ecbd97d, channel: 5, state: LISTENING
,08-26 15:43:03.215  6417  6417 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1ecbd97d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c7af93c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cbde072mSocket: android.net.LocalSocket@31677cc3 impl:android.net.LocalSocketImpl@12e5b940 fd:FileDescriptor[77]
,08-26 15:43:03.215  6417  6417 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@31677cc3 impl:android.net.LocalSocketImpl@12e5b940 fd:FileDescriptor[77]
,08-26 15:43:03.215  6417  6417 I BtOppRfcommListener: stopping Accept Thread
08-26 15:43:03.215  6417  6417 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11c19079, channel: 12, state: LISTENING
08-26 15:43:03.215  6417  6417 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11c19079, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b9c6d28, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@591bemSocket: android.net.LocalSocket@2bbb221f impl:android.net.LocalSocketImpl@260d296c fd:FileDescriptor[79]
,08-26 15:43:03.215  6417  6417 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2bbb221f impl:android.net.LocalSocketImpl@260d296c fd:FileDescriptor[79]
,08-26 15:43:03.215  6417  6898 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:43:03.225  6417  6417 V BluetoothOppManager: cleanUp...
,08-26 15:43:03.235  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:03.245  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 15:43:03.395  6417  6857 W bt-btif : ag scb idx 1 not allocated
08-26 15:43:03.395  6417  6857 W bt-btif : ag scb idx 2 not allocated
08-26 15:43:03.395  6417  6857 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 15:43:03.395  6417  6879 I bt_userial_mct: exiting userial_read_thread
08-26 15:43:03.395  6417  6879 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 15:43:03.395  6417  6842 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 15:43:03.395  6417  6859 I bt_vendor: hw_epilog_process
,08-26 15:43:03.405  6417  6842 D bt_userial_mct: userial_close
08-26 15:43:03.405  6417  6842 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 15:43:03.625  1014  1320 E Watchdog: !@Sync 4
,08-26 15:43:03.815  6417  6842 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off,
08-26 15:43:03.815  6417  6842 I bt_vendor: bluetooth satus is on
08-26 15:43:03.815  6417  6842 I bt_vendor: bt-vendor : resetting BT status
08-26 15:43:03.815  6417  6842 I bt_vendor: Starting hciattach daemon
08-26 15:43:03.815  6417  6842 I bt_vendor: try to set false
08-26 15:43:03.815  6417  6842 I bt_vendor: Starting hciattach daemon
08-26 15:43:03.815  6417  6842 I bt_vendor: try to set false
08-26 15:43:03.815  6417  6842 I bt_vendor: cleanup
08-26 15:43:03.815  6417  6857 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 15:43:03.815  6417  6842 I GKI_LINUX: GKI_exit_task 0 done
08-26 15:43:03.815  6417  6842 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 15:43:03.815  6417  6839 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 15:43:03.815  6417  6839 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:03.815  6417  6839 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 15:43:03.815  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 15:43:03.815  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 15:43:03.815  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 15:43:03.815  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-26 15:43:03.815  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 15:43:03.825  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.825  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.825  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.825  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 15:43:03.825  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:03.825  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 15:43:03.825  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:03.825  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 15:43:03.825  6417  6417 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 15:43:03.825  6417  6417 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:43:03.825  6417  6417 D BtGatt.GattService: stop()
08-26 15:43:03.825  6417  6417 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 15:43:03.825  1014  1544 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:43:03.825  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.825  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.825  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 15:43:03.825  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 15:43:03.825  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
08-26 15:43:03.825  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.825  6417  6417 D HeadsetService: Received stop request...Stopping profile...
08-26 15:43:03.825  1014  1343 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.825  1014  1343 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.835  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.835  1014  1343 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.835  1014  1343 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.835  1014  1343 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.835  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:43:03.835  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:03.835  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:03.835  1014  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.835  1014  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.835  1014  1473 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.835  1014  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.835  1014  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.835  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 15:43:03.835  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:43:03.835  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:03.835  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:03.835  1357  1357 D HeadsetProfile: Bluetooth service disconnected
08-26 15:43:03.835  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.835  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.845  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.845  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.845  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.845  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 15:43:03.845  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 15:43:03.845  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:03.845  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.845  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.845  1014  1544 W ActivityManager: userId = 0, bbcId = -10000,
08-26 15:43:03.845  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.845  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.845  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.845  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.845  6417  6839 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService,
,08-26 15:43:03.845  1014  1490 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.845  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 15:43:03.855  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:03.855  1014  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.855  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:43:03.855  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:43:03.855  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:03.855  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.855  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.855  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.855  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService,
,08-26 15:43:03.855  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:43:03.855  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:03.855  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:03.855  6417  6839 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:03.855  6417  6839 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 15:43:03.855  6417  6839 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 15:43:03.855  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 15:43:03.855  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 15:43:03.855  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 15:43:03.855  6417  6417 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService,
08-26 15:43:03.855  6417  6417 D A2dpService: Received stop request...Stopping profile...
08-26 15:43:03.855  6417  6852 D A2dpStateMachine: Exit Disconnected: -1
08-26 15:43:03.865  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.865  1357  1357 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:03.865  1014  1014 D BluetoothA2dp: Proxy object disconnected
,08-26 15:43:03.865  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 15:43:03.865  2863  2863 D BluetoothA2dp: Proxy object disconnected
,08-26 15:43:03.865  1357  1357 D A2dpProfile: Bluetooth service disconnected
,08-26 15:43:03.865  6417  6417 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 15:43:03.865  6417  6417 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:43:03.865  6417  6417 D HidService: Received stop request...Stopping profile...
,08-26 15:43:03.865  6417  6417 D HidService: Stopping Bluetooth HidService
,08-26 15:43:03.865  6417  6417 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:43:03.865  6417  6417 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 15:43:03.865  6417  6417 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:43:03.875  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd,
,08-26 15:43:03.875  6417  6417 D HealthService: Received stop request...Stopping profile...
08-26 15:43:03.875  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
08-26 15:43:03.875  1357  1357 D BluetoothInputDevice: Proxy object disconnected
08-26 15:43:03.875  1357  1357 D HidProfile: Bluetooth service disconnected
,08-26 15:43:03.875  6417  6417 D PanService: Received stop request...Stopping profile...
,08-26 15:43:03.875  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.875  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 15:43:03.875  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:43:03.875  1357  1357 D PanProfile: Bluetooth service disconnected
,08-26 15:43:03.885  6417  6417 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:43:03.885  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.885  6417  6417 D SapService: Received stop request...Stopping profile...
08-26 15:43:03.885  6417  6417 D SapService: Stopping Bluetooth SapService
08-26 15:43:03.885  6417  6417 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@31c9a7bd
,08-26 15:43:03.885  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 15:43:03.885  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:03.885  6417  6417 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 15:43:03.885  6417  6417 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:03.885  6417  6417 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 15:43:03.885  6417  6853 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 15:43:03.885  6417  6417 I GKI_LINUX: GKI_exit_task 2 done
08-26 15:43:03.885  6417  6417 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 15:43:03.885  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-26 15:43:03.885  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.885  6417  6417 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.885  1357  1357 D BluetoothMap: Proxy object disconnected
,08-26 15:43:03.895  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 15:43:03.895  1357  1357 D MapProfile: Bluetooth service disconnected
08-26 15:43:03.895  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.895  6417  6417 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.895  6417  6417 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:43:03.895  6417  6417 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:43:03.895  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 15:43:03.895  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.895  6417  6417 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:03.895  6417  6417 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:43:03.895  6417  6417 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 15:43:03.895  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-26 15:43:03.895  6417  6417 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 15:43:03.895  6417  6417 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 15:43:03.895  6417  6417 E BluetoothAdapterService(835299261): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-26 15:43:03.895  6417  6417 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 15:43:03.895  6417  6417 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 15:43:03.895  1357  1357 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 15:43:03.895  1357  1357 D SapProfile: Bluetooth service disconnected
,08-26 15:43:03.895  6417  6839 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-26 15:43:03.895  6417  6839 D BluetoothAdapterProperties: Setting state to 10
08-26 15:43:03.895  6417  6839 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-26 15:43:03.895  6417  6839 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:03.895  6417  6839 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 15:43:03.895  6417  6839 D BluetoothAdapterService: Autoconnection is available 
,08-26 15:43:03.895  6417  6839 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 15:43:03.895  6417  6839 I BluetoothAdapterState: Entering OffState
08-26 15:43:03.895  1357  6697 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:03.895  1357  6697 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.895  1357  1368 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 15:43:03.895  1357  1368 D Bluetoothsap: Unbinding service...
,08-26 15:43:03.905  6417  6425 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:03.905  1357  1369 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:43:03.905  1438  1464 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.905  1438  1464 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.905  1429  6884 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:03.905  1429  6884 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.905  1453  2523 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:03.905  1453  2523 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.905  1357  6697 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 15:43:03.905  2863  2915 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.905  2863  2915 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  1173  1186 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:03.915  1173  1186 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.915  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 15:43:03.915  6385  6400 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.915  6385  6400 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  1903  1912 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.915  1903  1912 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  6225  6235 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 15:43:03.915  6225  6235 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  6225  6235 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 15:43:03.915  6225  6235 D BluetoothLeAdvertiser: Exit stop advertising
08-26 15:43:03.915  6225  6235 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 15:43:03.915  6225  6235 D BluetoothLeScanner: Exiting stopAllScan
08-26 15:43:03.915  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:03.915  6417  6695 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 15:43:03.915  6417  6695 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 15:43:03.915  2863  2877 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:03.915  1357  6697 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 15:43:03.925  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:03.925  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-26 15:43:03.925  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:43:03.935  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.935  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-26 15:43:03.935  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:03.935  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.935  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:03.935  1173  1719 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.935  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.935  1173  1173 D BluetoothTile:  getBluetoothState : 10
08-26 15:43:03.935  1173  1719 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.945  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
08-26 15:43:03.945  1173  1173 D BluetoothAdapter: 326135988: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.945  1014  1490 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 15:43:03.945  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 15:43:03.945  1014  1473 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:03.945  1771  1771 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:03.945  1903  2118 D BluetoothAdapter: 52051256: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.945  1903  2118 D BluetoothAdapter: 52051256: getState() :  mService = null. Returning STATE_OFF
,08-26 15:43:03.945  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:03.945  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:03.945  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:03.945  1014  1133 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:43:03.945  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.955  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.955  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:03.955  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:03.955  6417  6842 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 15:43:03.955  6417  6417 I GKI_LINUX: GKI_exit_task 1 done
08-26 15:43:03.955  6417  6417 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 15:43:03.955  6417  6417 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 15:43:03.955  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:03.955  1014  1491 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 15:43:03.955  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:03.955  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:03.955  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:03.955  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:03.965  6417  6417 I art     : System.exit called, status: 0
08-26 15:43:03.965  6417  6417 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:43:03.965  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:03.975  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:03.975  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.975  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 15:43:04.055  1014  1543 I ActivityManager: Process com.android.bluetooth (pid 6417)(adj 0) has died(69,1080)
,08-26 15:43:04.075  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:04.075  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:43:04.075  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:04.075  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.075  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:04.075  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:04.085  1903  6915 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:43:04.095  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:43:04.105  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:04.105  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:04.105  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:04.105  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:04.115  1903  6915 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 15:43:04.325   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:43:05.325   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:43:05.325   288   288 E SMD     : DCD OFF
,08-26 15:43:06.105  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:06.105  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:06.325   314   314 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 15:43:07.325   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application,
08-26 15:43:07.505  1014  1946 V SAMP_SPCM_test: CSC File load.. 
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 15:43:07.505  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 15:43:07.515  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall,
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:43:07.545  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,08-26 15:43:07.555  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 15:43:07.565  1014  1946 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-26 15:43:07.565  1014  1946 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-26 15:43:07.565  1014  1946 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 15:43:07.565  1014  1946 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:07.565  1014  1946 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:07.565  1014  1946 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:07.585  6918  6918 E Zygote  : MountEmulatedStorage()
08-26 15:43:07.585  6918  6918 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:07.585  6918  6918 E Zygote  : v2
08-26 15:43:07.585  6918  6918 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:07.585  1014  1946 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6918 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 15:43:07.585  6918  6918 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:43:07.585  6918  6918 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:43:07.585  6918  6918 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:07.605  6918  6918 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:07.605  6918  6918 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:07.625  6918  6918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:43:07.655  1014  1946 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 15:43:08.325   314   314 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 15:43:08.335   288   288 E SMD     : DCD OFF
,08-26 15:43:09.115  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:09.115  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28b1d70d added. We now have 6 listener(s)
,08-26 15:43:09.115  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:09.115  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:09.115  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@244cb6c2 added. We now have 7 listener(s)
,08-26 15:43:09.115  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:09.115  6225  6277 I System.out: IsBluetoothEnabled
,08-26 15:43:09.115  6225  6277 D BluetoothAdapter: disable()
,08-26 15:43:09.125  1014  1473 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 15:43:09.135  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 15:43:09.135  6225  6277 D BluetoothAdapter: enable()
,08-26 15:43:09.135  1014  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 15:43:09.135  1014  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:09.135  1014  1027 W BluetoothManagerService: 	,at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 15:43:09.135  1014  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-26 15:43:09.135  1014  1027 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-26 15:43:09.135  1014  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,08-26 15:43:09.135  1014  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446),
08-26 15:43:09.135  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:09.135  1014  1027 D SettingsProvider: name = bluetooth_on,
08-26 15:43:09.135  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:09.135  1014  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:09.145  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 15:43:09.145  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:09.145  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 15:43:09.145  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 15:43:09.145  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:09.145  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:09.145  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:09.145  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:09.155  6937  6937 E Zygote  : MountEmulatedStorage()
08-26 15:43:09.155  6937  6937 E Zygote  : v2
08-26 15:43:09.155  6937  6937 I libpersona: KNOX_SDCARD checking this for 1002
08-26 15:43:09.155  6937  6937 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:09.155  1014  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6937 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 15:43:09.165  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:43:09.165  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 15:43:09.165  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:09.185  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:09.185  6937  6937 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:09.205  6937  6937 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 15:43:09.205  6937  6937 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:43:09.225  6937  6937 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding GattService
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding HidService
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding HealthService
,08-26 15:43:09.265  6937  6937 D BtSettings.ProfileConfig: Adding PanService
,08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding SapService
,08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 15:43:09.275  6937  6937 D BtSettings.ProfileConfig: Adding HidDevService
08-26 15:43:09.275  6937  6937 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 15:43:09.275  1014  1543 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 15:43:09.275  1014  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.275  1014  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.275  1014  1543 D SettingsProvider: selectionArgs: false
08-26 15:43:09.275  1014  1543 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.275  1014  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.275  1014  1543 D SettingsProvider: ret = -1
,08-26 15:43:09.275  1014  1490 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 15:43:09.275  1014  1490 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.275  1014  1490 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.275  1014  1490 D SettingsProvider: selectionArgs: false
08-26 15:43:09.275  1014  1490 D SettingsProvider: selectionArgs: 1002
,08-26 15:43:09.275  1014  1490 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.275  1014  1490 D SettingsProvider: ret = -1
,08-26 15:43:09.275  1014  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 15:43:09.275  1014  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.275  1014  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.275  1014  1473 D SettingsProvider: selectionArgs: false
08-26 15:43:09.275  1014  1473 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.275  1014  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.275  1014  1473 D SettingsProvider: ret = -1
08-26 15:43:09.275  1014  1250 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-26 15:43:09.275  1014  1250 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1250 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1250 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1250 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1250 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:43:09.285  1014  1250 D SettingsProvider: ret = -1
08-26 15:43:09.285  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 15:43:09.285  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:43:09.285  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1026 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1026 D SettingsProvider: selectionArgs: 1002
,08-26 15:43:09.285  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1026 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  1133 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-26 15:43:09.285  1014  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1133 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1133 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1133 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  1343 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 15:43:09.285  1014  1343 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1343 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 15:43:09.285  1014  1343 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1343 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1343 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1343 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  1544 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 15:43:09.285  1014  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1544 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1544 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1544 D SettingsProvider: ret = -1
08-26 15:43:09.285  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:09.285  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1491 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1491 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1491 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:09.285  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1027 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  1027 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1027 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  3278 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 15:43:09.285  1014  3278 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  3278 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  3278 D SettingsProvider: selectionArgs: false
08-26 15:43:09.285  1014  3278 D SettingsProvider: selectionArgs: 1002
,08-26 15:43:09.285  1014  3278 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  3278 D SettingsProvider: ret = -1
,08-26 15:43:09.285  1014  1339 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 15:43:09.285  1014  1339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.285  1014  1339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.285  1014  1339 D SettingsProvider: selectionArgs: false
,08-26 15:43:09.285  1014  1339 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.285  1014  1339 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.285  1014  1339 D SettingsProvider: ret = -1
,08-26 15:43:09.305  6937  6937 D BluetoothAdapterState: make,
,08-26 15:43:09.305  6937  6937 I bluedroid: init
,08-26 15:43:09.305  6937  6952 I BluetoothAdapterState: Entering OffState
08-26 15:43:09.305  6937  6937 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:43:09.315  6937  6937 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 15:43:09.315  6937  6937 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 15:43:09.315  6937  6937 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 15:43:09.315  6937  6937 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 15:43:09.315  6937  6937 I bluedroid: get_profile_interface socket
08-26 15:43:09.315  6937  6937 I bluedroid: get_profile_interface map_client
08-26 15:43:09.315  6937  6955 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 15:43:09.315  6937  6955 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-26 15:43:09.315  6937  6955 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:43:09.315  6937  6955 I bluedroid: getModelRssiValues
08-26 15:43:09.315  6937  6955 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 15:43:09.315  6937  6955 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:09.315  6937  6937 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 15:43:09.315  1014  1014 D SettingsProvider: name = bluetooth_name
,08-26 15:43:09.315  6937  6955 D BluetoothAdapterProperties: Name is: A5-1
,08-26 15:43:09.325  6937  6937 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:09.325  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 15:43:09.325   314   314 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
08-26 15:43:09.325  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.325  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.325  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.325  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.325  6937  6945 I bluedroid: config_hci_snoop_log
,08-26 15:43:09.325  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-26 15:43:09.335  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,08-26 15:43:09.335  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 15:43:09.335  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 15:43:09.335  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 15:43:09.345  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:09.345  6937  6937 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-26 15:43:09.345  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 15:43:09.345  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 15:43:09.345  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 15:43:09.355  6937  6952 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 15:43:09.355  6937  6952 D BluetoothAdapterProperties: Setting state to 11
,08-26 15:43:09.355  6937  6952 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 15:43:09.355  6937  6952 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 15:43:09.355  6937  6952 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 15:43:09.355  6937  6952 D BluetoothAdapterService: Autoconnection is available 
08-26 15:43:09.355  6937  6952 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 15:43:09.355  6937  6952 D BluetoothSecureManager: getInstant: null
,08-26 15:43:09.365  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:09.365  6937  6952 D BluetoothSecureManager: calling getMethod for getService
08-26 15:43:09.365  6937  6952 D BluetoothSecureManager: calling getService
,08-26 15:43:09.365  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-26 15:43:09.365  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:09.365  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:09.375  1173  1173 D BluetoothTile:  getBluetoothState : 11
08-26 15:43:09.375  6937  6952 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2631175
,08-26 15:43:09.375  1014  1491 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 15:43:09.375  1014  1491 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 15:43:09.375  6937  6952 D BtConfig.SecureMode: isSecureModeOn:false
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:43:09.375  1771  1771 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:09.375  1014  1339 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:09.375  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 15:43:09.375  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:09.375  1014  1133 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 15:43:09.385  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:09.385  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:09.385  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 15:43:09.385  6937  6952 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 15:43:09.385  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:09.385  6937  6952 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:09.385  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 15:43:09.385  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:43:09.385  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:09.385  1014  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 15:43:09.385  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.385  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.385  1014  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:09.385  6937  6952 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:09.385  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 15:43:09.385  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 15:43:09.385  6937  6952 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:09.385  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 15:43:09.385  6937  6952 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 15:43:09.395  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:09.405  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:09.405  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 15:43:09.405  6937  6952 D BluetoothBondStateMachine: make
,08-26 15:43:09.405  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 15:43:09.405  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 15:43:09.405  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 15:43:09.405  6937  6957 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:43:09.415  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:09.415  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.415  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.415  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.415  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.415  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:09.415  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 15:43:09.415  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 15:43:09.415  6937  6937 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:09.415  6937  6937 D BtGatt.GattService: Received start request. Starting profile...
,08-26 15:43:09.415  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:09.415  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 15:43:09.415  6937  6937 D BtGatt.GattService: start()
,08-26 15:43:09.415  6937  6937 D BtGatt.GattService: start()
08-26 15:43:09.415  6937  6937 I bluedroid: get_profile_interface gatt
08-26 15:43:09.415  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:09.425  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.425  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:09.425  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:09.425  6937  6937 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:43:09.435  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:09.435  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:09.435  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 15:43:09.435  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:09.435  6937  6937 D BtGatt.GattService: mStartError = false
08-26 15:43:09.435  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:43:09.435  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.435  6937  6937 D HeadsetService: Received start request. Starting profile...
08-26 15:43:09.435  6937  6937 D HeadsetService: start()
,08-26 15:43:09.445  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.445  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.445  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 15:43:09.445  6937  6937 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 15:43:09.445  6937  6937 D HeadsetStateMachine: make
,08-26 15:43:09.445  6937  6937 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 15:43:09.455  1014  1339 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 15:43:09.455  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.455  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.455  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 15:43:09.455  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.455  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 15:43:09.455  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 15:43:09.455  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 15:43:09.455  1014  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:09.455  1014  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.465  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.465  1014  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.465  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.465  1014  1490 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 15:43:09.465  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.465  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.465  1014  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.465  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 15:43:09.465  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 15:43:09.465  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 15:43:09.465  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 15:43:09.465  6937  6937 I bluedroid: get_profile_interface handsfree
,08-26 15:43:09.465  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:09.465  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.465  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:09.465  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.465  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.475  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 15:43:09.475  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 15:43:09.475  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 15:43:09.485  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:09.485  1014  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:09.485  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.485  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:09.485  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.485  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.495  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 15:43:09.495  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 15:43:09.495  6937  6952 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 15:43:09.495  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:09.495  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.495  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:09.495  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:09.495  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.495  6937  6937 I DualScoManager: Instantiating Dual Sco Manager
08-26 15:43:09.495  6937  6937 I DualScoManager: Set HeadsetServiceHelper
,08-26 15:43:09.505  6937  6937 D BluetoothAtMessage: createCMTIContentObservers
,08-26 15:43:09.505  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 15:43:09.505  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 15:43:09.505  6937  6952 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 15:43:09.505  1014  1133 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 15:43:09.505  1014  1133 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 15:43:09.505  1014  1133 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:09.505  1014  1133 D SettingsProvider: selectionArgs: false
08-26 15:43:09.505  1014  1133 D SettingsProvider: selectionArgs: 1002
08-26 15:43:09.505  1014  1133 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 15:43:09.505  1014  1133 D SettingsProvider: ret = -1
08-26 15:43:09.505  1014  1133 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:09.505  1014  1133 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 15:43:09.505  6937  6962 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 15:43:09.505  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:43:09.505  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:09.505  1014  1133 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:09.505  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:09.505  6937  6937 D HeadsetService: mStartError = false
08-26 15:43:09.505  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:43:09.505  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 15:43:09.515  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:09.515  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 15:43:09.515  6937  6962 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 15:43:09.515  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 15:43:09.515  6937  6952 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 15:43:09.515  6937  6952 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 15:43:09.515  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 15:43:09.515  6937  6962 D HeadsetStateMachine: map size, before remove : 0
08-26 15:43:09.515  6937  6962 D HeadsetStateMachine: map size, after remove: 0
,08-26 15:43:09.515  6937  6952 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 15:43:09.515  6937  6937 D A2dpService: Received start request. Starting profile...
08-26 15:43:09.515  6937  6937 D A2dpService: start()
,08-26 15:43:09.515  6937  6937 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 15:43:09.515  6937  6937 I bluedroid: get_profile_interface avrcp
,08-26 15:43:09.525  6937  6937 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:09.545  6937  6937 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 15:43:09.545  6937  6964 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 15:43:09.555  6937  6937 I BluetoothA2dpServiceJni: classInitNative: succeeds,
08-26 15:43:09.555  6937  6937 D A2dpStateMachine: make
,08-26 15:43:09.555  6937  6937 I bluedroid: get_profile_interface a2dp
,08-26 15:43:09.555  6937  6966 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-26 15:43:09.555  6937  6937 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 15:43:09.565  6937  6937 D A2dpService: mStartError = false
08-26 15:43:09.565  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:09.565  6937  6937 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 15:43:09.565  6937  6965 D A2dpStateMachine: Enter Disconnected: -2
,08-26 15:43:09.565  1429  6884 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 15:43:09.565  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0,
08-26 15:43:09.565  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 15:43:09.565  1429  6884 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 15:43:09.565  6937  6937 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 15:43:09.575  6937  6937 D HidService: Received start request. Starting profile...
08-26 15:43:09.575  6937  6937 D HidService: start()
08-26 15:43:09.575  6937  6937 I bluedroid: get_profile_interface hidhost
,08-26 15:43:09.575  6937  6937 D HidService: setHidService(): set to: null
08-26 15:43:09.575  6937  6937 D HidService: mStartError = false
08-26 15:43:09.575  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:43:09.575  6937  6937 D HeadsetStateMachine: Proxy object connected
,08-26 15:43:09.575  6937  6937 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-26 15:43:09.575  6937  6962 D HeadsetStateMachine: Disconnected process message: 11
08-26 15:43:09.575  6937  6937 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 15:43:09.575  6937  6937 D HealthService: Received start request. Starting profile...
08-26 15:43:09.575  6937  6937 D HealthService: start()
,08-26 15:43:09.575  6937  6964 D BluetoothMediaBrowser: no now playing list
,08-26 15:43:09.585  6937  6964 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 15:43:09.585  6937  6937 I bluedroid: get_profile_interface health
,08-26 15:43:09.585  6937  6937 D HealthService: mStartError = false
,08-26 15:43:09.585  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:09.585  6937  6937 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 15:43:09.585  6937  6937 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-26 15:43:09.585  6937  6962 D HeadsetStateMachine: Disconnected process message: 18
08-26 15:43:09.585  6937  6937 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:43:09.585  6937  6937 D PanService: Received start request. Starting profile...
,08-26 15:43:09.585  6937  6937 D PanService: start()
08-26 15:43:09.585  6937  6937 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 15:43:09.585  6937  6937 I bluedroid: get_profile_interface pan
,08-26 15:43:09.585  6937  6937 D PanService: mStartError = false
,08-26 15:43:09.585  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:43:09.595  6937  6937 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:09.595  6937  6937 D BluetoothMapService: start()
,08-26 15:43:09.595  6937  6937 D BluetoothMapService: mStartError = false
08-26 15:43:09.595  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:09.595  6937  6937 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 15:43:09.595  6937  6937 D SapService: Received start request. Starting profile...
08-26 15:43:09.595  6937  6937 D SapService: start()
08-26 15:43:09.595  6937  6937 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 15:43:09.595  6937  6937 I bluedroid: get_profile_interface sap
08-26 15:43:09.595  6937  6937 D SapService: mStartError = false
08-26 15:43:09.595  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:09.595  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 15:43:09.595  6937  6937 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 15:43:09.595  6937  6937 D BluetoothA2dp: Proxy object connected
08-26 15:43:09.595  6937  6937 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 15:43:09.595  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 15:43:09.595  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 15:43:09.595  6937  6962 D HeadsetStateMachine: Disconnected process message: 10
08-26 15:43:09.595  6937  6962 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
08-26 15:43:09.595  6937  6962 D HeadsetStateMachine: Disconnected process message: 11
,08-26 15:43:09.605  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 15:43:09.605  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 15:43:09.625  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 15:43:09.625  6937  6937 E BluetoothAdapterService(243124583): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 15:43:09.635  6937  6952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 15:43:09.635  6937  6952 I bluedroid: enable
,08-26 15:43:09.635  6937  6970 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
08-26 15:43:09.635  6937  6952 I bt_hci_bdroid: init
08-26 15:43:09.635  6937  6952 I bt_vendor: bt-vendor : init
08-26 15:43:09.635  6937  6952 I bt_vendor: bt-vendor : get_bt_soc_type
,08-26 15:43:09.635  6937  6952 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 15:43:09.635  6937  6952 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-26 15:43:09.635  6937  6952 D bt_userial_mct: userial_init
,08-26 15:43:09.635  6937  6952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 15:43:09.635  6937  6952 I bt_vendor: Starting hciattach daemon
08-26 15:43:09.635  6937  6952 I bt_vendor: try to set false
,08-26 15:43:09.645  6937  6952 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 15:43:09.645  6937  6952 I bt_vendor: Starting hciattach daemon
08-26 15:43:09.645  6937  6952 I bt_vendor: try to set true
,08-26 15:43:09.665  6974  6974 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 15:43:09.725  6980  6980 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 15:43:09.725  6981  6981 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:43:09.745  6983  6983 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:43:09.755  6984  6984 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 15:43:09.765  6985  6985 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 15:43:09.775  6986  6986 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 15:43:09.955  6989  6989 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-26 15:43:09.965  6990  6990 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 15:43:09.995  6937  6952 I bt_vendor: bluetooth satus is on,
08-26 15:43:09.995  6937  6972 D bt_userial_mct: userial_open(port:0)
08-26 15:43:09.995  6937  6972 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 15:43:10.005  6937  6972 I bt_vendor: Done intiailizing UART,
,08-26 15:43:10.005  6937  6972 I bt_vendor: Done intiailizing UART,
08-26 15:43:10.005  6937  6972 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 15:43:10.005  6937  6972 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 15:43:10.015  6937  6992 D bt_userial_mct: Entering userial_read_thread(),
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 15:43:10.015  6937  6970 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 15:43:10.115  6937  6970 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 15:43:10.125  6937  6970 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa406a6e9 
,08-26 15:43:10.125  6937  6970 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa406a6e9 
,08-26 15:43:10.135  6937  6955 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 15:43:10.145  6937  6955 E bt-btif : Calling BTA_HhEnable
,08-26 15:43:10.145  6937  6955 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 15:43:10.145  6937  6955 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 15:43:10.145  6937  6955 E BluetoothServiceJni: populateRssiValuesNative
08-26 15:43:10.145  6937  6955 I bluedroid: getModelRssiValues
08-26 15:43:10.145  6937  6955 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 15:43:10.145  6937  6955 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 15:43:10.155  1014  1014 D SettingsProvider: name = bluetooth_name
,08-26 15:43:10.155  6937  6955 D BluetoothAdapterProperties: Name is: A5-1
,08-26 15:43:10.155  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.155  6937  6955 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 15:43:10.165  6937  6955 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:10.165  6937  6955 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:10.165  6937  6955 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-26 15:43:10.165  6937  6955 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-26 15:43:10.165  6937  6955 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 15:43:10.165  6937  6955 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 15:43:10.165  6937  6955 E bt-btif : btif_sock_init: !vhci_init
08-26 15:43:10.165  6937  6955 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 15:43:10.165  6937  6955 D IOP_DB_BT: db_open: db_open : handle 3028717584l, read 13894 bytes onto local cache
,08-26 15:43:10.165  6937  6955 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 15:43:10.165  6937  6955 D IOP_DB_BT: db_query: result 1
,08-26 15:43:10.165  6937  6955 I         : iop_db_open: iop_db_open status 0
,08-26 15:43:10.175  6937  6955 D bte_conf: Device ID record 1 : primary
08-26 15:43:10.175  6937  6955 D bte_conf:   vendorId            = 0075
08-26 15:43:10.175  6937  6955 D bte_conf:   vendorIdSource      = 0001
08-26 15:43:10.175  6937  6955 D bte_conf:   product             = 0100
08-26 15:43:10.175  6937  6955 D bte_conf:   version             = 0200
08-26 15:43:10.175  6937  6955 D bte_conf:   clientExecutableURL = 
08-26 15:43:10.175  6937  6955 D bte_conf:   serviceDescription  = 
08-26 15:43:10.175  6937  6955 D bte_conf:   documentationURL    = 
08-26 15:43:10.175  6937  6955 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 15:43:10.175  6937  6955 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 15:43:10.175  6937  6992 E bt_mct  : hci lib postload completed
,08-26 15:43:10.175  6937  6952 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 15:43:10.175  6937  6952 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:10.175  6937  6952 D BluetoothAdapterProperties: State =  11
,08-26 15:43:10.175  1014  1490 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 15:43:10.175  6937  6952 D BluetoothAdapterProperties: Setting state to 12
,08-26 15:43:10.175  6937  6952 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:10.185  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:10.195  6937  6955 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 15:43:10.195  6937  6955 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:10.195  6937  6955 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:10.195  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:10.195  1014  1339 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 15:43:10.195  1014  1339 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 15:43:10.195  1014  1339 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 15:43:10.195  1014  1339 D SettingsProvider: selectionArgs: false
,08-26 15:43:10.195  1014  1339 D SettingsProvider: selectionArgs: 1002
08-26 15:43:10.195  1014  1339 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 15:43:10.195  1014  1339 D SettingsProvider: ret = -1
,08-26 15:43:10.195  6937  6952 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 15:43:10.195  6937  6952 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 15:43:10.195  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.205  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.205  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.205  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.205  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.205  6937  6952 D BluetoothAdapterService: Autoconnection is available ,
08-26 15:43:10.205  6937  6952 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 15:43:10.205  6937  6952 D BluetoothAdapterService: starting service from this receiver
,08-26 15:43:10.215  1014  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 15:43:10.215  1357  1369 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.215  1357  1369 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.215  1357  1368 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 15:43:10.215  1357  1368 D Bluetoothsap: Binding service...
08-26 15:43:10.215  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.215  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.215  1357  1368 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-26 15:43:10.215  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.215  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.215  6937  6952 I BluetoothAdapterState: Entering On State from state = 11
08-26 15:43:10.215  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-26 15:43:10.225  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 15:43:10.225  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.225  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.225  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 15:43:10.225  1357  1368 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-26 15:43:10.225  1429  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.225  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.225  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.225  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.225  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.225  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.225  1429  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.225  2863  2877 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.235  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.235  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.235  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.235  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.235  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.235  2863  2877 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.235  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.235  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.235  6937  6937 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 15:43:10.235  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.235  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.235  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.235  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.245  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.245  6937  6945 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.245  6937  6945 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.245  1357  6697 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:43:10.245  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 15:43:10.245  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.245  1357  1357 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 15:43:10.245  1357  1357 D SapProfile: Bluetooth service connected
08-26 15:43:10.245  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.245  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.245  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.255  1357  1357 D Bluetoothsap: getConnectedDevices()
,08-26 15:43:10.255  1438  1452 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.255  1438  1452 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.255  6937  6937 I BluetoothPbapService: Handler(): got msg=1
,08-26 15:43:10.255  1014  1491 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:10.255  1453  1714 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.255  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.255  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 15:43:10.255  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.255  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.255  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.255  1453  1714 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.255  1429  6884 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.255  1429  6884 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.255  1453  2523 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.255  1453  2523 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.255  6937  6997 V BluetoothPbapService: PBAP Service initSocket try: 0
08-26 15:43:10.265  1357  1369 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:10.265  1357  1357 D BluetoothPbap: Proxy object connected
,08-26 15:43:10.265  1357  1357 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:10.265  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 15:43:10.265  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.265  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.265  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.265  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.265  1357  1357 D BluetoothMap: Proxy object connected
08-26 15:43:10.265  1429  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.265  1357  1357 D MapProfile: Bluetooth service connected
08-26 15:43:10.265  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.265  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:10.265  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.265  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.265  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.265  6937  6997 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:43:10.265  6937  6997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:10.265  1429  1445 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:43:10.265  1357  1357 D BluetoothMap: getConnectedDevices()
,08-26 15:43:10.265  2863  2915 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.265  2863  2915 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.275  1173  3801 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.275  1173  3801 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.275  1357  1368 D BluetoothPan: Binding service...
,08-26 15:43:10.275  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:10.275  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.275  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.275  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.275  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.275  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:10.275  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.275  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 15:43:10.275  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:10.275  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.275  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.275  6385  6396 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.275  6385  6396 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.275  6937  6997 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-26 15:43:10.275  6937  6997 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:10.275  6937  6997 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 15:43:10.275  6937  6997 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8672c10
08-26 15:43:10.275  6937  6997 D BluetoothSocket: channel: 19
08-26 15:43:10.275  6937  6997 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 15:43:10.275  1357  1369 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:10.275  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:10.275  1357  1357 D PanProfile: Bluetooth service connected
,08-26 15:43:10.275  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 15:43:10.275  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 15:43:10.275  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.275  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.275  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.275  1357  1369 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 15:43:10.275  1903  2105 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 15:43:10.275  1903  2105 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 15:43:10.285  6225  6237 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 15:43:10.285  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:10.285  6225  6237 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 15:43:10.285  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 15:43:10.285  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.285  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 15:43:10.285  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 15:43:10.285  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 15:43:10.285  1014  1043 D BluetoothPan: Binding service...
,08-26 15:43:10.285  1014  1014 D BluetoothA2dp: Proxy object connected
08-26 15:43:10.285  2863  2877 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:10.285  2863  2877 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.285  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:10.285  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.285  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.285  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.285  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.285  1357  6697 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 15:43:10.285  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:10.285  1357  1357 D HeadsetProfile: Bluetooth service connected
08-26 15:43:10.285  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 15:43:10.285  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 15:43:10.285  2863  2863 D BluetoothA2dp: Proxy object connected
,08-26 15:43:10.285  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.285  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.285  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 15:43:10.285  1357  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:10.295  1357  1368 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 15:43:10.295  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 15:43:10.295  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.295  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:10.295  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.295  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.295  6937  6945 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:10.295  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 15:43:10.295  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-26 15:43:10.295  1357  1357 D BluetoothInputDevice: Proxy object connected
08-26 15:43:10.295  1357  1357 D HidProfile: Bluetooth service connected
,08-26 15:43:10.295  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.295  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-26 15:43:10.295  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 15:43:10.295  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f7d106a, true
,08-26 15:43:10.305  1173  1173 D BluetoothTile:  onBluetoothStateChange:
,08-26 15:43:10.305  1429  1429 D BluetoothHeadset: registerMessageListener
,08-26 15:43:10.305  1771  1771 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 15:43:10.305  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.315  1173  1173 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 15:43:10.315  1173  1173 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.315  1173  1173 D BluetoothTile:  getBluetoothState : 12
08-26 15:43:10.315  1014  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:43:10.315  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.315  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.315  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:10.315  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:10.315  1357  1357 D BluetoothA2dp: Proxy object connected
08-26 15:43:10.315  1357  1357 D A2dpProfile: Bluetooth service connected
,08-26 15:43:10.315  6937  7001 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 15:43:10.315  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:10.315  6937  6996 D HeadsetService: registerMessageListener
,08-26 15:43:10.325  6937  6996 D HeadsetService: registerMessageListener,
,08-26 15:43:10.325  6937  6962 D HeadsetStateMachine: Disconnected process message: 70
08-26 15:43:10.325  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-26 15:43:10.325  6937  6962 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@27bad309
08-26 15:43:10.325  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 15:43:10.325  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 15:43:10.325  1357  1357 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 15:43:10.325  6937  7001 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:43:10.325  6937  7001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:10.325  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 15:43:10.325  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 15:43:10.325  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 15:43:10.325  1173  1719 D BluetoothTile:  handleUpdatestate:false name:null,
08-26 15:43:10.325  6937  7001 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 15:43:10.325  6937  7001 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:10.325  6937  7001 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 15:43:10.325  6937  7001 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18cec90e
08-26 15:43:10.335  6937  7001 D BluetoothSocket: channel: 5
,08-26 15:43:10.335  6937  6962 D HeadsetStateMachine: Disconnected process message: 9
08-26 15:43:10.335  6937  6962 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 15:43:10.335  1014  1343 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:10.335  1014  1339 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-26 15:43:10.335  1357  1357 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 15:43:10.335  1357  1357 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 15:43:10.335  1357  1357 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 15:43:10.335  1357  1357 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 15:43:10.335  1173  1173 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 15:43:10.345   283   680 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 15:43:10.345   283   680 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 15:43:10.345   283   680 V voice   : voice_set_parameters: exit with code(-2)
08-26 15:43:10.345   283   680 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 15:43:10.345   283   680 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 15:43:10.345   283   680 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 15:43:10.345   283   680 V audio_hw_primary: adev_set_parameters: exit
08-26 15:43:10.345  6937  6962 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 15:43:10.345  1357  1357 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:10.345  1014  3278 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 15:43:10.345  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.345  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.345  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.345  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 15:43:10.355  1357  1357 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:10.355  1357  1357 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 15:43:10.355  1173  1173 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:10.355  1173  1173 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 15:43:10.365  6937  6937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
08-26 15:43:10.365  6937  6937 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 15:43:10.365  1014  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 15:43:10.375  1014  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.375  1014  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.375  1014  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:10.375  1014  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 15:43:10.385  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:10.385  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 15:43:10.385  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:10.385  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.385  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:10.385  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:10.395  1903  7007 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 15:43:10.395  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 15:43:10.405  1014  1133 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:10.405  1014  1133 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.405  1014  1133 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 15:43:10.405  1014  1133 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:10.405  1014  3081 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 15:43:10.425  6937  7011 D BluetoothSocket: bindListen(): myUserId = 0
08-26 15:43:10.425  6937  7011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:10.425  6937  7011 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-26 15:43:10.425  6937  7011 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 15:43:10.425  6937  7011 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-26 15:43:10.425  6937  7011 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b9c6d28
08-26 15:43:10.425  6937  7011 D BluetoothSocket: channel: 12
08-26 15:43:10.425  6937  7011 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:10.505  1903  2079 I art     : Explicit concurrent mark sweep GC freed 58135(3MB) AllocSpace objects, 47(1877KB) LOS objects, 39% free, 14MB/24MB, paused 1.391ms total 85.880ms
,08-26 15:43:10.515  1014  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 15:43:10.515  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:10.515  1014  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 15:43:10.515  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 15:43:10.525  1903  7007 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:11.145  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:11.155  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:11.155  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:11.155  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30651cd3 added. We now have 8 listener(s)
,08-26 15:43:11.155  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:11.155  1014  1473 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:43:11.155  1014  1473 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:43:11.155  1014  1473 D SecContentProvider2: mCursor = null
,08-26 15:43:11.165  1014  1473 D WifiService: setWifiEnabled: false pid=6225, uid=10155
,08-26 15:43:11.165  1014  1473 D SettingsProvider: name = wifi_on
,08-26 15:43:11.165  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:11.165  1014  1491 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 15:43:11.165  1014  1491 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 15:43:11.175  1014  1491 D SecContentProvider2: mCursor = null
,08-26 15:43:11.175  1014  1491 D WifiService: setWifiEnabled: true pid=6225, uid=10155
,08-26 15:43:11.175  1014  1491 W ActivityManager: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 15:43:11.175  1014  1491 W WifiService: Failed getting userId using ActivityManagerNative
08-26 15:43:11.175  1014  1491 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6225, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 15:43:11.175  1014  1491 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 15:43:11.175  1014  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 15:43:11.175  1014  1491 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 15:43:11.175  1014  1491 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 15:43:11.175  1014  1491 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 15:43:11.175  1014  1491 D SettingsProvider: name = wifi_on
,08-26 15:43:11.185  1014  1123 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 15:43:11.335   288   288 E SMD     : DCD OFF
,08-26 15:43:11.545  1014  1041 D Tethering: interfaceAdded wlan0
,08-26 15:43:11.555  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:11.555  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:11.555  1014  1128 E Tethering: No numeric data
,08-26 15:43:11.565  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:43:11.565  1014  1128 D Tethering: clearTetheredNotification()
,08-26 15:43:11.565  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:11.565  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.565  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 15:43:11.565  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:11.565  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:43:11.565  1014  1128 D Tethering: InitialState.processMessage what=4
08-26 15:43:11.565  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 15:43:11.565  1173  1173 D HotspotTile: updateTetherState():false, false
08-26 15:43:11.575  1014  1128 E Tethering: No numeric data
,08-26 15:43:11.575  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 15:43:11.575  1014  1128 D Tethering: clearTetheredNotification()
08-26 15:43:11.575  1014  1041 D Tethering: interfaceAdded p2p0
,08-26 15:43:11.575  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 15:43:11.585  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:11.585  1173  1173 D HotspotTile: updateTetherState():false, false
,08-26 15:43:11.585  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 15:43:11.585  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 15:43:11.585  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,08-26 15:43:11.585   278   978 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 15:43:11.585   278   978 D SoftapController: Softap fwReload - Ok
,08-26 15:43:11.595  1014  1120 V NetworkStats: performPollLocked() took 29ms
08-26 15:43:11.595  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.595  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:11.595  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:11.595   278   978 D CommandListener: Setting iface cfg
08-26 15:43:11.595   278   978 D CommandListener: Trying to bring down wlan0
08-26 15:43:11.595  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:11.595  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:11.605   278   978 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:43:11.605  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:11.605  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.605  1014  1120 V NetworkStats: performPollLocked() took 9ms
,08-26 15:43:11.605  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.605  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.605  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:11.615  1014  1123 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 15:43:11.655  7025  7025 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 15:43:11.655  7025  7025 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 15:43:11.655  7025  7025 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 15:43:11.665  7025  7025 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 15:43:11.675   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7025
08-26 15:43:11.675   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 15:43:11.675  7025  7025 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 15:43:11.675  7025  7025 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:11.675  7025  7025 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 15:43:11.675  7025  7025 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 15:43:11.675   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7025
08-26 15:43:11.675   336   336 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-26 15:43:11.715  1014  1123 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-26 15:43:11.715  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 15:43:11.715  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 15:43:11.715  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.715  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.725  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:11.715  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.725  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-26 15:43:11.715  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:11.725  1173  1173 D HotspotTile: onReceive : 2, 0,
08-26 15:43:11.715  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:11.715  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 15:43:11.735  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:11.735  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:11.735  1014  1339 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:11.735  1014  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:11.735  1014  1339 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:11.735  1014  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:11.735  1014  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:11.735  3706  3706 I Hs20UtilService: Starting #17
08-26 15:43:11.735  3706  3727 I Hs20UtilService: Message received 5011
,08-26 15:43:11.745  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:43:11.745  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:43:11.745  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:43:11.745  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 15:43:11.795  1014  1490 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 15:43:11.795  1014  1490 D BatteryService: level:86, scale:100, status:2, health:2, present:true, voltage: 4142, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-26 15:43:11.795  1014  1490 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-26 15:43:11.795  1014  1490 D BatteryService: stay LED for charging
,08-26 15:43:11.795  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 15:43:11.795  1014  1014 I MotionRecognitionService: Plugged
,08-26 15:43:11.795  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 15:43:11.795  1173  1173 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 15:43:11.795  1173  1173 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 15:43:11.795  1412  1412 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 15:43:11.805  1412  1412 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 86
,08-26 15:43:11.815  6937  6937 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 15:43:11.815  6937  6962 D HeadsetStateMachine: Disconnected process message: 10
,08-26 15:43:11.825  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:43:11.825  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
08-26 15:43:11.825  1173  1173 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:86 status:2 health:2
,08-26 15:43:11.835   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-26 15:43:11.835  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-26 15:43:11.905  7025  7025 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 15:43:11.905  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-26 15:43:11.915  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-26 15:43:11.915   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7025
08-26 15:43:11.915   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-26 15:43:11.915  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,08-26 15:43:11.915  7025  7025 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:11.915  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.915  7025  7025 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:11.915  7025  7025 E wpa_supplicant: SIM READ ERROR
08-26 15:43:11.915  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.915  7025  7025 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:11.915  7025  7025 E wpa_supplicant: SIM READ ERROR
08-26 15:43:11.915  7025  7025 I wpa_supplicant: Blacklist: Clear (all) 
08-26 15:43:11.915  7025  7025 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:43:11.915  7025  7025 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:43:11.915  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:11.915  7025  7025 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 15:43:11.915  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 15:43:11.915  7025  7025 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 15:43:11.915  7025  7025 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:43:11.925  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:43:11.925  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:11.925  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 15:43:11.985  7025  7025 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 15:43:12.555  1014  2729 D SSRM:n  : SIOP:: AP = 340
,08-26 15:43:12.605  7025  7025 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 15:43:12.605  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-26 15:43:12.625  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-26 15:43:12.625   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7025
08-26 15:43:12.625   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-26 15:43:12.625  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-26 15:43:12.625  7025  7025 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:12.625  7025  7025 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 15:43:12.625  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-26 15:43:12.635  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-26 15:43:12.635   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7025
08-26 15:43:12.635   336   336 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-26 15:43:12.635  7025  7025 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-26 15:43:12.635  7025  7025 I wpa_supplicant: ssSupport state is = 1
08-26 15:43:12.635  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 15:43:12.635  7025  7025 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:12.635  7025  7025 E wpa_supplicant: SIM READ ERROR
08-26 15:43:12.635  7025  7025 I wpa_supplicant: wpa_default_ap_write_once
08-26 15:43:12.635  7025  7025 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 15:43:12.635  7025  7025 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 15:43:12.645  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 15:43:12.645  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
08-26 15:43:12.645  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 15:43:12.735  7025  7025 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 15:43:12.735  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 15:43:12.795  7025  7025 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 15:43:12.795  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 15:43:12.795  7025  7025 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:43:12.805  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-26 15:43:12.805  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 15:43:12.805  7025  7025 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-26 15:43:12.805  7025  7025 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 15:43:12.815  7025  7025 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 15:43:12.815  7025  7025 E wpa_supplicant: SIM READ ERROR,
08-26 15:43:12.815  7025  7025 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 15:43:12.825  7025  7025 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 15:43:12.835  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210],
08-26 15:43:12.835  7025  7025 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 15:43:12.835  1014  1123 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:43:12.835  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:12.835  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:12.835  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:12.835  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:12.835  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:12.835  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:12.835  1173  1173 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 15:43:12.835  1173  1173 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 15:43:12.835  1173  1719 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 15:43:12.845  1173  1173 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:12.845  1173  1173 D HotspotTile: onReceive : 3, 0
,08-26 15:43:12.845  1357  1357 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 15:43:12.855  1014  3081 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 15:43:12.855  1014  3081 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:12.855  1014  3081 W ActivityManager: userId = 0, bbcId = -10000
,08-26 15:43:12.855  1014  3081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:12.855  1014  3081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:12.855  3706  3706 I Hs20UtilService: Starting #18
08-26 15:43:12.855  3706  3727 I Hs20UtilService: Message received 5011
08-26 15:43:12.865  1014  1123 E WifiConfigStore: Not a HS20
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.865  6225  6225 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:12.865  1014  1123 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 15:43:12.865  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [65]
08-26 15:43:12.865  1014  1123 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 15:43:12.865  7025  7025 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 15:43:12.865  7025  7025 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 15:43:12.865  7025  7025 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 15:43:12.865  7025  7025 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 15:43:12.865  7025  7025 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 15:43:12.865  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 15:43:12.865  7025  7025 I wpa_supplicant: First Scan Start
08-26 15:43:12.865  7025  7025 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 15:43:12.875  6225  6225 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:12.875  1014  1123 D WifiNative-wlan0: Setting external_sim to 1
08-26 15:43:12.875  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 15:43:12.875  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 15:43:12.875  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
08-26 15:43:12.875  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 15:43:12.875  1014  1123 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 15:43:12.875  1014  1123 I WifiNative-HAL: startHal
08-26 15:43:12.875  1014  1123 E wifi    : getStaticLongField sWifiHalHandle 0x9ca4d88c
08-26 15:43:12.875  1014  1123 I WifiNative-HAL: Could not start hal
08-26 15:43:12.875  1014  1123 E WifiNative-wlan0: do suspend true
08-26 15:43:12.875  6469  6469 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 15:43:12.875  1014  1122 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 15:43:12.875   278   978 D CommandListener: Setting iface cfg
08-26 15:43:12.875   278   978 D CommandListener: Trying to bring up p2p0
08-26 15:43:12.875  1014  1122 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 15:43:12.885  1014  1122 D WifiP2pService: P2pEnablingState
08-26 15:43:12.885  1014  1122 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 15:43:12.885  1014  1122 D WifiP2pService: P2p socket connection successful
08-26 15:43:12.885  1014  1122 D WifiP2pService: P2pEnabledState
08-26 15:43:12.885  1014  1123 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 15:43:12.885  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 15:43:12.885  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:43:12.885  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:43:12.885  1014  1123 E WifiNative-wlan0: invaild command id : 215
08-26 15:43:12.885  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-26 15:43:12.885  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.885  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:12.885  1014  1148 I WifiNative-HAL: startHal
08-26 15:43:12.885  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9dbff9bc
08-26 15:43:12.885  1014  1148 I WifiNative-HAL: Could not start hal
08-26 15:43:12.885  1014  1148 E WifiScanningService: could not start HAL
08-26 15:43:12.885  1014  1123 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 15:43:12.885  1014  1123 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 15:43:12.885  1014  1123 E WifiNative-wlan0: invaild command id : 215
08-26 15:43:12.885  7025  7025 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:43:12.895  1014  1122 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 15:43:12.895  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:43:12.895  7025  7025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 15:43:12.895  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 15:43:12.895  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:43:12.895  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 15:43:12.895  1014  1044 D WifiDisplayController: disconnect
08-26 15:43:12.895  7025  7025 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-26 15:43:12.895  1014  1044 D WifiDisplayController: updateConnection
08-26 15:43:12.895  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 15:43:12.895  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:43:12.895  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:12.895  1173  1173 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 15:43:12.895  1014  1123 D SecContentProvider2: mCursor = null
08-26 15:43:12.895  1014  1490 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 15:43:12.895  1173  1173 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 15:43:12.905  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 15:43:12.905  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
08-26 15:43:12.905  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 15:43:12.905  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 15:43:12.905  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 15:43:12.905  1014  1122 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-26 15:43:12.905  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 15:43:12.905  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:43:12.905  1014  1122 D WifiP2pService: DeviceAddress: 7e:96:ac
08-26 15:43:12.905  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:43:12.905  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  secondary type: null
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  wps: 0
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  grpcapab: 0
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  devcapab: 0
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  status: 3
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  wfdInfo: null
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  groupownerAddress: null
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  GOdeviceName: null
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  interfaceAddress: 
08-26 15:43:12.905  1014  1044 D WifiDisplayController:  SConnectInfo : null
08-26 15:43:12.905  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:12.905  1014  1123 D SecContentProvider2: mCursor = null
08-26 15:43:12.905  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:43:12.905  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:12.905  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:43:12.905  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:43:12.915  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 15:43:12.915  6439  6439 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 15:43:12.915  6439  6439 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 15:43:12.925  6454  6454 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 15:43:12.935  1014  1122 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 15:43:12.935  1014  1122 D WifiP2pService: InactiveState
,08-26 15:43:12.935  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-26 15:43:12.935  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:43:12.935  7025  7025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 15:43:12.935  1014  1122 D WifiP2pService: InactiveState{ what=143376 }
,08-26 15:43:12.935  1014  1122 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:13.205  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:13.205  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:13.215  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 15:43:13.215  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:43:13.215  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2ef5da57 Bundle[{}]
,08-26 15:43:13.215  6225  6277 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:43:13.215  6225  6277 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 15:43:13.215  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:43:13.215  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 15:43:13.225  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 15:43:13.225  6225  6277 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:43:13.225  6225  6277 I System.out: Running OutgoingSocketThread
,08-26 15:43:13.225  6225  7032 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1177)
,08-26 15:43:13.235  6225  7032 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 60772
,08-26 15:43:13.235  6225  7032 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 15:43:14.105  7025  7025 I wpa_supplicant: nl80211: Received scan results (18 BSSes),
,08-26 15:43:14.105  7025  7025 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-26 15:43:14.105  7025  7025 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-26 15:43:14.105  1014  7030 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 15:43:14.115  7025  7025 I wpa_supplicant: Trying to associate with  'G700',
,08-26 15:43:14.115  7025  7025 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-26 15:43:14.115  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-26 15:43:14.125  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:14.125  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:43:14.225  6225  6277 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1178)
,08-26 15:43:14.225  6225  6277 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1178)
,08-26 15:43:14.235  6225  6277 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1183)
,08-26 15:43:14.235  6225  6277 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 15:43:14.235  6225  6277 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1184)
,08-26 15:43:14.235  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.235  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@807c010 added. We now have 2 listener(s)
,08-26 15:43:14.235  7025  7025 E wpa_supplicant: Cmd 35605 not handled
,08-26 15:43:14.235  7025  7025 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-26 15:43:14.235  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-26 15:43:14.235  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:14.245  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:14.235  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:43:14.235  7025  7025 I wpa_supplicant: Associated with F4.99.3E
08-26 15:43:14.245  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:14.235  7025  7025 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 15:43:14.235  7025  7025 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 15:43:14.235  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
08-26 15:43:14.245  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 15:43:14.245  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 15:43:14.245  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
08-26 15:43:14.245  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.245  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.245  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.245  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.245  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2431d709 added. We now have 9 listener(s),
,08-26 15:43:14.245  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.245  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 15:43:14.245  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.245  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 15:43:14.245  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,08-26 15:43:14.245  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 15:43:14.245  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:43:14.255  1014  1128 E Tethering: No numeric data
08-26 15:43:14.255  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 15:43:14.255  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.255  7025  7025 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 15:43:14.255  7025  7025 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 15:43:14.255  7025  7025 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 15:43:14.265  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:14.255  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 15:43:14.255  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 15:43:14.255  1014  1128 D Tethering: clearTetheredNotification()
08-26 15:43:14.255  7025  7025 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 15:43:14.255  7025  7025 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 15:43:14.255  7025  7025 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 15:43:14.255  7025  7025 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 15:43:14.255  7025  7025 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 15:43:14.255  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
08-26 15:43:14.265  1173  1173 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 15:43:14.255  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
08-26 15:43:14.265  1173  1173 D HotspotTile: updateTetherState():false, false
08-26 15:43:14.265  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:14.265  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:14.265  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:14.265  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:14.265  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:43:14.265  1014  1120 V NetworkStats: performPollLocked() took 8ms
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.275  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:14.275  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.275  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.275  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:14.275  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:14.275  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5ab32f added. We now have 3 listener(s)
,08-26 15:43:14.275  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.275  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1790cd3c added. We now have 10 listener(s)
08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.275  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:14.275  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.275  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.275  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.275  1014  1123 D WifiNative-wlan0: callSECApiVoid - ID [50]
08-26 15:43:14.275  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.275  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@807c010 removed from the list
08-26 15:43:14.275  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.275  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2431d709 removed from the list
08-26 15:43:14.275  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.275  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.285  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.285  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.285  1014  1123 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.285  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2431d709 not in the list
08-26 15:43:14.285  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.285  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.285  1014  1123 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 15:43:14.285  1014  1125 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 15:43:14.285  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:43:14.285  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.285  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1790cd3c removed from the list
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.285  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.285  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.285  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-26 15:43:14.285  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5ab32f removed from the list
08-26 15:43:14.285  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:14.285  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 15:43:14.285  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.285  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.285  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.285  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.295  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.295  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f97dac5 added. We now have 2 listener(s)
08-26 15:43:14.295  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:43:14.295  1014  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:14.295  1014  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:14.295  1014  1544 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:14.295  1014  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:14.295  1014  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:14.295  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.295  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.295  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.295  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.295  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ae5c1a added. We now have 9 listener(s)
08-26 15:43:14.295  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.295  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.295  3706  3706 I Hs20UtilService: Starting #19
08-26 15:43:14.295  3706  3727 I Hs20UtilService: Message received 5007
08-26 15:43:14.295  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:14.295  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 15:43:14.305  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 15:43:14.305  1014  1123 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:43:14.305  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 15:43:14.305  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:14.305  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:43:14.305  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 15:43:14.305  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.315  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.315  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-26 15:43:14.315  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.315  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.315  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143b8128 added. We now have 3 listener(s)
,08-26 15:43:14.315   278   978 D CommandListener: Setting iface cfg
08-26 15:43:14.315  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.315  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.315  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.315  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.315  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.315  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.315  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba05e41 added. We now have 10 listener(s)
08-26 15:43:14.315  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.315  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.315  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:14.315  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.315  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.315  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:14.315  1014  1123 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 15:43:14.325  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.325  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 15:43:14.325  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:43:14.325  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:14.325  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:43:14.335  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.335  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.335   288   288 E SMD     : DCD OFF
,08-26 15:43:14.335  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.335  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:14.335  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.335  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 15:43:14.335  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:14.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:14.335  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:14.345  6937  6996 D BtGatt.GattService: registerClient() - UUID=71a4d7a8-1129-4c3a-b1f2-e1f443dcef66,
,08-26 15:43:14.345  1014  1123 E WifiNative-wlan0: do suspend false
,08-26 15:43:14.345  1014  1122 D WifiP2pService: InactiveState{ what=143375 },
08-26 15:43:14.345  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:43:14.355  1014  1123 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 15:43:14.355  1014  1123 D SecContentProvider2: mCursor = null
,08-26 15:43:14.385  6937  6955 D BtGatt.GattService: onClientRegistered() - UUID=71a4d7a8-1129-4c3a-b1f2-e1f443dcef66, clientIf=6
,08-26 15:43:14.385  6225  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:43:14.385  6937  7000 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.395  6937  6959 D BtGatt.ScanManager: handling starting scan
08-26 15:43:14.395  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:14.395  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:14.395  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.395  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:14.395  6937  6959 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7dc967
,08-26 15:43:14.395  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.395  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:14.395  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.405  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.405  6937  6955 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 15:43:14.405  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.405  6937  6959 D BtGatt.ScanManager: allow scan with filters
08-26 15:43:14.405  6937  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 15:43:14.405  6937  6959 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 15:43:14.405  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:43:14.405  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.405  6937  6959 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.405  6937  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.415  6937  6955 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:14.415  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.415  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:43:14.415  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.425  6225  6277 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:43:14.425  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.425  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:43:14.425  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.425  6937  6998 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:14.425  6937  6946 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.425  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:14.425  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.435  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:14.435  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.435  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:14.435  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.435  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.435  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.435  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.435  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.435  6937  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 39
,08-26 15:43:14.435  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.435  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:14.435  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.435  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.435  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.435  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.445  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f97dac5 removed from the list
08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.445  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ae5c1a removed from the list
08-26 15:43:14.445  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.445  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.445  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.445  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.445  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31ae5c1a not in the list
08-26 15:43:14.445  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.445  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.445  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba05e41 removed from the list
08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.445  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.445  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.445  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.445  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@143b8128 removed from the list
,08-26 15:43:14.445  6937  6959 D BtGatt.ScanManager: filter size is 1
08-26 15:43:14.445  6937  6959 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 15:43:14.455  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 15:43:14.455  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.455  6937  6959 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:43:14.455  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.455  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e539d7d added. We now have 2 listener(s)
,08-26 15:43:14.455  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 15:43:14.455  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:43:14.455  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.455  6937  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 15:43:14.455  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.455  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.455  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.455  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f445472 added. We now have 9 listener(s)
08-26 15:43:14.455  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.455  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.465  6937  6955 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 15:43:14.465  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.465  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.465  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.475  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:14.475  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d34d40 added. We now have 3 listener(s)
,08-26 15:43:14.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 15:43:14.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.475  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c019479 added. We now have 10 listener(s)
08-26 15:43:14.475  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.475  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.475  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.475  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:14.475  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.475  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.475  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:14.475  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.475  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.485  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.485  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.485  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.485  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.485  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 15:43:14.485  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.495  6937  6946 D BtGatt.GattService: registerClient() - UUID=72bee713-9712-433c-8fcf-4b050fd344c9
,08-26 15:43:14.535  6937  6955 D BtGatt.GattService: onClientRegistered() - UUID=72bee713-9712-433c-8fcf-4b050fd344c9, clientIf=6
,08-26 15:43:14.535  6225  6237 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 15:43:14.535  6937  6999 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.535  6937  6959 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.535  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:14.535  6937  6955 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 15:43:14.545  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:14.545  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.545  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:14.545  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.545  6937  6959 D BtGatt.ScanManager: allow scan with filters
08-26 15:43:14.545  6937  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:14.545  6937  6959 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 15:43:14.545  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 15:43:14.545  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.545  6937  6959 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 15:43:14.545  6937  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.545  6937  6955 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:14.545  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.555  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.555  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:14.555  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.555  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 15:43:14.555  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.565  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.575  7039  7039 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 15:43:14.575  6937  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 40
,08-26 15:43:14.575  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.575  6225  6277 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 15:43:14.575  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:14.575  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.575  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.575  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.575  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.575  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e539d7d removed from the list
08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 15:43:14.575  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f445472 removed from the list
08-26 15:43:14.575  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.575  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.575  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.575  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:14.575  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.575  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.575  7039  7039 I dhcpcd  : version 5.5.6 starting
08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.575  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f445472 not in the list
,08-26 15:43:14.575  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:14.575  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 15:43:14.585  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.585  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:14.585  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.585  7039  7039 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 15:43:14.585  6937  7000 D BtGatt.GattService: stopScan() - queue size =1,
08-26 15:43:14.585  6937  6945 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:14.585  6937  6959 D BtGatt.ScanManager: filter size is 1
08-26 15:43:14.585  6937  6959 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 15:43:14.585  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.585  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.585  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 15:43:14.585  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.585  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:14.595  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-26 15:43:14.595  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:14.595  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.595  6937  6959 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:14.595  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-26 15:43:14.595  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:14.595  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.595  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c019479 removed from the list
,08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.595  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.595  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.595  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.595  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15d34d40 removed from the list,
08-26 15:43:14.595  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.595  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.595  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.595  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.595  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdff35 added. We now have 2 listener(s)
08-26 15:43:14.605  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 15:43:14.605  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.605  6937  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 15:43:14.605  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.605  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.605  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.605  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.605  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee5ffca added. We now have 9 listener(s)
,08-26 15:43:14.605  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.615  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.615  6937  6955 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:43:14.615  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.615  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.625  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:14.625  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:14.625  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:43:14.625  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.625  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de58458 added. We now have 3 listener(s)
,08-26 15:43:14.635  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.645  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 15:43:14.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.645  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.645  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1c59b1 added. We now have 10 listener(s)
08-26 15:43:14.645  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.645  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.645  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:14.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-26 15:43:14.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:14.645  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:14.645  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.675  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.675  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.675  7039  7039 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 15:43:14.675  7039  7039 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 15:43:14.675  7039  7039 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 15:43:14.675  7039  7039 I dhcpcd  : bssid match
,08-26 15:43:14.675  7039  7039 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-26 15:43:14.675  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:43:14.675  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true,
08-26 15:43:14.675  6225  6277 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.685  6937  6945 D BtGatt.GattService: registerClient() - UUID=82ca24dc-a996-478e-9798-35c8ea83f631
,08-26 15:43:14.725  6937  6955 D BtGatt.GattService: onClientRegistered() - UUID=82ca24dc-a996-478e-9798-35c8ea83f631, clientIf=6
,08-26 15:43:14.725  6225  6237 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 15:43:14.725  6937  6996 D BtGatt.GattService: start scan with filters
08-26 15:43:14.725  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:14.725  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:43:14.725  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.725  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.725  6937  6955 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 15:43:14.725  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: allow scan with filters
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-26 15:43:14.725  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 15:43:14.725  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.725  6937  6959 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 15:43:14.725  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.725  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:43:14.735  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.735  6937  6955 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 15:43:14.735  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.735  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.735  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 15:43:14.735  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.755  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:14.755  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.755  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.755  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.755  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdff35 removed from the list
08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.755  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee5ffca removed from the list
08-26 15:43:14.755  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.755  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:14.755  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.755  6937  6959 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 41
,08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.755  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee5ffca not in the list
,08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.755  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 15:43:14.755  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 15:43:14.765  6937  6998 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:14.765  6937  6959 D BtGatt.ScanManager: filter size is 1
,08-26 15:43:14.765  6937  6959 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 15:43:14.765  6937  6999 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 15:43:14.765  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.765  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.765  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.765  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.765  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:14.765  6937  6955 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 15:43:14.765  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.765  6937  6959 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:14.765  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:14.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:14.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.775  6937  6955 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 15:43:14.775  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.775  6937  6959 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 15:43:14.775  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:14.775  6225  6225 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.775  6225  6225 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d1c59b1 removed from the list
08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.775  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.775  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1de58458 removed from the list
,08-26 15:43:14.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.775  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3debdfed added. We now have 2 listener(s)
,08-26 15:43:14.775  6937  6955 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 15:43:14.775  6937  6955 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 15:43:14.775  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 15:43:14.785  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.785  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.785  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.785  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f6be22 added. We now have 9 listener(s)
,08-26 15:43:14.785  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.785  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.785  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.785  7039  7039 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:14.795  6225  6277 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:14.795  6225  6277 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:14.795  6225  6277 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.795  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.795  6225  6225 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.795  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.795  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df48670 added. We now have 3 listener(s)
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.805  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.805  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb38de9 added. We now have 10 listener(s)
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.805  6225  6277 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.805  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.805  6225  6277 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:14.805  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.805  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.805  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.805  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3debdfed removed from the list
,08-26 15:43:14.805  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.805  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f6be22 removed from the list
,08-26 15:43:14.805  6225  6277 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:14.805  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.815  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.815  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.815  6225  6277 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f6be22 not in the list
08-26 15:43:14.815  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.815  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:43:14.815  6225  6277 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb38de9 removed from the list
08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.815  6225  6277 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.815  6225  6277 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.815  6225  6277 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.815  6225  6277 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3df48670 removed from the list
,08-26 15:43:14.815  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 15:43:14.815  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 15:43:14.815  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-26 15:43:14.815  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:14.825  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 15:43:14.825  6225  6277 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.825  6225  7047 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1191, name: My test thread name)
,08-26 15:43:14.825  6225  7047 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1191, thread name: My test thread name)
08-26 15:43:14.825  6225  7047 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:14.825  7039  7039 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,08-26 15:43:14.835  6225  7048 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1193, name: My test thread name)
,08-26 15:43:14.835  6225  7048 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1193, thread name: My test thread name)
08-26 15:43:14.835  6225  7048 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1193, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:14.835  6225  6277 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-26 15:43:14.845  6225  6277 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 15:43:14.845  6225  6277 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 15:43:14.845  6225  6277 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 15:43:14.845  6225  6277 D com.test.thalitest.ThaliTestRunner: Total duration: 24371 ms
,08-26 15:43:14.845  6225  6277 I jxcore-log: *Native tests were executed*
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.845  6225  6277 I jxcore-log: Total number of executed tests:  80
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.845  6225  6277 I jxcore-log: Number of passed tests:  80
08-26 15:43:14.845  6225  6277 I jxcore-log: ,
08-26 15:43:14.845  6225  6277 I jxcore-log: Number of failed tests:  0
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.845  6225  6277 I jxcore-log: Number of ignored tests:  0
08-26 15:43:14.845  6225  6277 I jxcore-log: 
,08-26 15:43:14.845  6225  6277 I jxcore-log: Total duration:  24371
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.845  6225  6277 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 15:43:14.845  6225  6277 I jxcore-log: 
,08-26 15:43:14.845  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.845  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.845  6225  6277 I jxcore-log: 
08-26 15:43:14.855  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.855  6225  6277 I jxcore-log: 
08-26 15:43:14.855  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.855  6225  6277 I jxcore-log: 
08-26 15:43:14.855  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.855  6225  6277 I jxcore-log: 
08-26 15:43:14.855  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.855  6225  6277 I jxcore-log: 
,08-26 15:43:14.855  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-26 15:43:14.855  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6225 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
,08-26 15:43:14.865  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.865  6225  6277 I jxcore-log: 
08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:14.875  6225  6277 I jxcore-log: 
,08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-26 15:43:14.875  6225  6277 I jxcore-log: 
08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
,08-26 15:43:14.875  6225  6277 I jxcore-log: 
08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.875  6225  6277 I jxcore-log: 
08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.875  6225  6277 I jxcore-log: 
08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 15:43:14.875  6225  6277 I jxcore-log: 
,08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.875  6225  6277 I jxcore-log: 
,08-26 15:43:14.875  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:14.875  6225  6277 I jxcore-log: 
,08-26 15:43:14.935  6225  6225 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 15:43:14.935  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:14.935  6225  6277 I jxcore-log: 
,08-26 15:43:15.095  6225  6225 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 15:43:15.095  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.095  6225  6277 I jxcore-log: 
,08-26 15:43:15.105  7057  7057 D AndroidRuntime: ,
08-26 15:43:15.105  7057  7057 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 15:43:15.105  7057  7057 D AndroidRuntime: CheckJNI is OFF,
,08-26 15:43:15.105  7057  7057 D AndroidRuntime: readGMSProperty: start
08-26 15:43:15.105  7057  7057 D AndroidRuntime: readGMSProperty: already setted!!
08-26 15:43:15.105  7057  7057 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 15:43:15.105  7057  7057 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
08-26 15:43:15.105  7057  7057 D AndroidRuntime: readGMSProperty: end
08-26 15:43:15.105  7057  7057 D AndroidRuntime: addProductProperty: start
,08-26 15:43:15.165  1014  1123 E WifiNative-wlan0: do suspend true
,08-26 15:43:15.185  1014  1122 D WifiP2pService: InactiveState{ what=143375 },
08-26 15:43:15.185  1014  1122 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 15:43:15.195  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.195  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 15:43:15.195  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.195  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.195  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.195  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.195  1014  1123 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-26 15:43:15.195  1014  1123 E WifiStateMachine: VerifyingLinkState enter
08-26 15:43:15.205  1014  1123 D WifiNative-wlan0: callSECApiInt - ID [210]
08-26 15:43:15.205  1014  1125 E ConnectivityService: updateNetworkInfo()
,08-26 15:43:15.205  1014  1125 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 15:43:15.205  1014  1125 D ConnectivityService: Adding iface wlan0 to network 503
,08-26 15:43:15.205  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 15:43:15.205  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:15.205  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:15.205  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 15:43:15.205  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 15:43:15.215  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.215  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 15:43:15.215  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.215  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.215  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.215  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.215  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:15.215  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 15:43:15.225  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.225  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.225  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 15:43:15.225  3706  3706 I Hs20UtilService: Starting #20
,08-26 15:43:15.225  3706  3727 I Hs20UtilService: Message received 5007
08-26 15:43:15.225  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.225  1357  1357 I NearbySettings: MountReceiver.onReceive - Keep current state
08-26 15:43:15.225  1014  1123 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 15:43:15.235  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 15:43:15.235  1173  1173 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.235  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 15:43:15.245  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.245  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.245  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.245  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.245  1014  1123 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
08-26 15:43:15.245  1014  1123 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:15.245  7057  7057 E AffinityControl: AffinityControl: registerfunction enter,
08-26 15:43:15.245  1014  1490 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 15:43:15.245  1014  1490 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.245  1014  1490 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:15.245  1014  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.245  1014  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:15.245  1014  1125 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
08-26 15:43:15.245  3706  3706 I Hs20UtilService: Starting #21
,08-26 15:43:15.255  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 15:43:15.255  1014  1125 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
08-26 15:43:15.255  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 15:43:15.255  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,08-26 15:43:15.255  3706  3727 I Hs20UtilService: Message received 5007
08-26 15:43:15.255  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-26 15:43:15.255  1014  1125 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,08-26 15:43:15.255  1014  1125 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 15:43:15.255  1014  1125 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-26 15:43:15.255  1014  1125 D ConnectivityService: LTETest block dns file not exists
,08-26 15:43:15.255  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.255  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:15.255  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.265  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.265  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.265  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.265  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 15:43:15.265  1357  1357 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 15:43:15.265  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 15:43:15.265  1014  1125 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.265  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:43:15.265  1014  1125 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 15:43:15.265  1014  1125 E ConnectivityService: updateNetworkInfo()
08-26 15:43:15.265  1014  1125 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.265  1014  1125 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.275  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:15.275  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 15:43:15.275  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 15:43:15.275  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-26 15:43:15.275  1014  7033 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 15:43:15.275  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 15:43:15.275   278   974 D EnterpriseController: uids 1000
08-26 15:43:15.275   278   974 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 15:43:15.275   278   974 D Netd    : getNetworkForDns: using netid 503 for uid 1000
08-26 15:43:15.275  6225  6225 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:15.275  6225  6277 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.275  6225  6277 I jxcore-log: 
08-26 15:43:15.275  7057  7057 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-26 15:43:15.275  1357  1357 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 15:43:15.275  1357  1357 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 15:43:15.275  1357  3037 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 15:43:15.285  1014  1125 D ConnectivityService:    accepting network in place of null,
,08-26 15:43:15.285  1014  1123 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:15.285  1014  1122 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 15:43:15.285  1453  1453 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 15:43:15.285  1453  1453 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 15:43:15.285  1014  1125 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1,
08-26 15:43:15.285  1014  1125 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-26 15:43:15.285  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 15:43:15.295  1014  3081 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-26 15:43:15.295  1014  1125 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 15:43:15.295  1014  3081 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 15:43:15.295  1014  3081 D PackageManager: START PACKAGE DELETE: observer{1009265157}
08-26 15:43:15.295  1014  3081 D PackageManager: pkg{<packageName>}
08-26 15:43:15.295  1014  3081 D PackageManager: user{0}
08-26 15:43:15.295  1014  3081 D PackageManager: caller{2000}
08-26 15:43:15.295  1014  3081 D PackageManager: flags{2}
08-26 15:43:15.295  1014  3081 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 15:43:15.295  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 15:43:15.295  1014  3081 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:43:15.295  1014  1120 V NetworkStats: updateIfacesLocked()
08-26 15:43:15.295  1014  3081 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 15:43:15.295  1014  1120 V NetworkStats: performPollLocked(flags=0x1)
08-26 15:43:15.295  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 15:43:15.295  1014  1125 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.295  1014  1128 D Tethering: MasterInitialState.processMessage what=3
08-26 15:43:15.295  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-26 15:43:15.295  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 15:43:15.295  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 15:43:15.295  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-26 15:43:15.295  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.295  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:15.295  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 15:43:15.295  1173  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:43:15.305  3836  6286 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 15:43:15.305  1014  3278 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 15:43:15.305  1014  3278 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:15.305  1014  3278 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 15:43:15.305  1014  3278 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:15.305  1014  1120 V NetworkStats: performPollLocked() took 4ms
08-26 15:43:15.305  1014  3278 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 15:43:15.305  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 15:43:15.305  1014  1121 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 15:43:15.305  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.305  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:15.305  3706  3706 I Hs20UtilService: Starting #22
,08-26 15:43:15.305  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-26 15:43:15.305  3706  3727 I Hs20UtilService: Message received 5007
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.305  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.305  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.315  1357  1357 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 15:43:15.315  1357  1357 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 15:43:15.335  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-26 15:43:15.335  1014  1039 I ActivityManager: Killing 6225:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 15:43:15.375  1014  7033 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 15:43:15.425  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:43:15 GMT], X-Android-Received-Millis=[1472218995436], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472218995406]}
08-26 15:43:15.435  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 15:43:15.435  1014  7033 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 15:43:15.435  1014  1125 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.435  1014  1125 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-26 15:43:15.435  1014  1125 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-26 15:43:15.435  1014  1125 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-26 15:43:15.435  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 15:43:15.435  1173  1713 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:43:15.435  3836  6286 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 15:43:15.445  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{397e10db u0 com.test.thalitest/.MainActivity t127}
,08-26 15:43:15.455  1173  1173 D StatusBar.NetworkController: EthernetConnected: false
,08-26 15:43:15.455  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-26 15:43:15.455  1173  1173 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-26 15:43:15.455  1173  1173 D StatusBar.NetworkController: updateDataNetType()
08-26 15:43:15.455  1173  1173 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-26 15:43:15.455  1173  1173 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 15:43:15.455  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-26 15:43:15.465  1014  1054 I ActivityManager:   Force finishing activity ActivityRecord{397e10db u0 com.test.thalitest/.MainActivity t127 f}
08-26 15:43:15.465  1014  1054 W ActivityManager: Duplicate finish request for ActivityRecord{397e10db u0 com.test.thalitest/.MainActivity t127 f}
,08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 15:43:15.465  1173  1173 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 15:43:15.465  1173  1173 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 15:43:15.485  1014  1133 I WindowState: WIN DEATH: Window{265d18bb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:43:15.485   257  1545 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-26 15:43:15.485  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 15:43:15.495   257  1094 I SurfaceFlinger: id=13 Removed NainActivit (-2/8),
08-26 15:43:15.495  1014  1133 D InputDispatcher: Focus left window: 6225
,08-26 15:43:15.505   257   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-26 15:43:15.505  1014  1039 D InputDispatcher: Focused application released
,08-26 15:43:15.505  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 15:43:15.505  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 15:43:15.505  5020  5020 I art     : Explicit concurrent mark sweep GC freed 2200(125KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 714us total 33ms
,08-26 15:43:15.505  1014  1343 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 15:43:15.515  1014  3278 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 15:43:15.515  1014  3278 D SecContentProvider2: mCursor = null
,08-26 15:43:15.515  1014  1490 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-26 15:43:15.515  1014  1490 D SecContentProvider2: mCursor = null
,08-26 15:43:15.525  1014  1339 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-26 15:43:15.525  1014  1339 D SecContentProvider2: mCursor = null
,08-26 15:43:15.525  1014  1250 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 15:43:15.525  1014  1250 D SecContentProvider2: mCursor = null
,08-26 15:43:15.535  1014  1133 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-26 15:43:15.535  1014  1133 D SecContentProvider2: mCursor = null
,08-26 15:43:15.535  1014  3081 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-26 15:43:15.535  1014  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 15:43:15.535  1014  3081 D SecContentProvider2: mCursor = null
,08-26 15:43:15.545  1771  1771 E SamsungIME: mOCRHelper is null
,08-26 15:43:15.565  3836  3836 I art     : Explicit concurrent mark sweep GC freed 22714(1383KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.348ms total 97.132ms
,08-26 15:43:15.565  1014  1120 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-26 15:43:15.565  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.565  1014  1120 V NetworkStats: performPollLocked(flags=0x3)
,08-26 15:43:15.565  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 15:43:15.565  1014  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 15:43:15.575  1014  1120 V NetworkStats: performPollLocked() took 6ms
08-26 15:43:15.575  1014  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:15.585  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:43:15.595  1438  1438 D RegisteredServicesCache: empty dynamic service
,08-26 15:43:15.605  6034  6034 I art     : Explicit concurrent mark sweep GC freed 569(33KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 789us total 122.715ms
,08-26 15:43:15.605  3729  3729 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 15:43:15 GMT+02:00 2016
,08-26 15:43:15.605  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 15:43:15.615  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-26 15:43:15.685  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 15:43:15.685  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 15:43:15.685  1014  1014 I art     : Explicit concurrent mark sweep GC freed 86078(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 28MB/42MB, paused 3.992ms total 204.914ms
,08-26 15:43:15.685  1014  1054 I art     : WaitForGcToComplete blocked for 172.580ms for cause Explicit
,08-26 15:43:15.775  1014  1014 D RCPManagerService: PackageReceiver onReceive()
08-26 15:43:15.775  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 15:43:15.785  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.785  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-26 15:43:15.785  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-26 15:43:15.785  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-26 15:43:15.785  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-26 15:43:15.795  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 15:43:15.795  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 15:43:15.795  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 15:43:15.795  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 15:43:15.795  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 15:43:15.795  1014  1125 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: uID is 10155
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 15:43:15.795  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 15:43:15.805  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-26 15:43:15.805  1014  2729 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-26 15:43:15.805  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-26 15:43:15.805  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-26 15:43:15.815  3121  3121 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-26 15:43:15.825  6547  6547 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-26 15:43:15.855  1014  1054 I art     : Explicit concurrent mark sweep GC freed 14268(775KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 28MB/42MB, paused 3.336ms total 169.950ms
,08-26 15:43:15.855  1014  1491 I art     : WaitForGcToComplete blocked for 268.420ms for cause Explicit
,08-26 15:43:15.905  1014  1054 D PackageManager: delete codoeFile: 
,08-26 15:43:15.915  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-26 15:43:15.915  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
08-26 15:43:15.915  1014  1054 D PackageManager: result of delete: 1{1009265157}
,08-26 15:43:15.925  7057  7057 D AndroidRuntime: Shutting down VM
,08-26 15:43:16.005  1014  1491 I art     : Explicit concurrent mark sweep GC freed 6044(305KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.561ms total 153.347ms
,08-26 15:43:16.005  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 15:43:16.005  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.005  1903  2109 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:43:16.005  1014  1339 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 15:43:16.005  1014  1339 D SecContentProvider2: mCursor = null
,08-26 15:43:16.015  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:16.015  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 15:43:16.015  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 15:43:16.015   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 15:43:16.015  3729  3729 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-26 15:43:16.015  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 15:43:16.015  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 15:43:16.015  1014  1038 W TextServicesManagerService: no available spell checker services found
,08-26 15:43:16.015  1014  3081 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-26 15:43:16.015  1014  3081 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-26 15:43:16.025  1014  3081 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 15:43:16.025  3729  3729 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-26 15:43:16.025  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.025  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.025  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.025  1014  3081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.025  3729  3729 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 15:43:16.035  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.035  1014  1490 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,08-26 15:43:16.045  7087  7087 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.045  7087  7087 E Zygote  : v2
,08-26 15:43:16.045  7087  7087 I libpersona: KNOX_SDCARD checking this for 10094
08-26 15:43:16.045  7087  7087 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.045  7087  7087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:43:16.045  1014  3081 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7087 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
,08-26 15:43:16.045  7087  7087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-26 15:43:16.045  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-26 15:43:16.055  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.055  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.055  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 15:43:16.055  7087  7087 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:43:16.055  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.055  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.055  1173  1173 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 15:43:16.055  3729  3729 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-26 15:43:16.055  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.065  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 15:43:16.065  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-26 15:43:16.075  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-26 15:43:16.075  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-26 15:43:16.075  7097  7097 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.075  7097  7097 I libpersona: KNOX_SDCARD checking this for 10044
08-26 15:43:16.075  7097  7097 E Zygote  : v2
08-26 15:43:16.075  7097  7097 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:16.075  7097  7097 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:43:16.075  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7097 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-26 15:43:16.075  7097  7097 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:43:16.085  7097  7097 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:43:16.085  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-26 15:43:16.095  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.095  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.095  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.095  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.095  7087  7087 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.095  7087  7087 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.105  7097  7097 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.115  7097  7097 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.115  7118  7118 E Zygote  : MountEmulatedStorage()
,08-26 15:43:16.115  7118  7118 E Zygote  : v2
08-26 15:43:16.115  7118  7118 I libpersona: KNOX_SDCARD checking this for 10149
08-26 15:43:16.115  7118  7118 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.115  7118  7118 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 15:43:16.115  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7118 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 15:43:16.125  7118  7118 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:43:16.125  7118  7118 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.135  7057  7057 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 15:43:16.155  7097  7097 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 15:43:16.165  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 15:43:16.165  1014  1054 D PackageManager: userId{-1}
08-26 15:43:16.165  1014  1054 D PackageManager: andCode{true}
,08-26 15:43:16.165  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.165  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 15:43:16.175  7118  7118 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.175  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.175  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.175  7118  7118 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.175  6937  6953 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 15:43:16.185  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.195  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:43:16.195  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.195  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 15:43:16.195  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.195  7087  7087 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 15:43:16.205  7087  7087 D elm:15183: ELMEngine.ELMEngine( context ).
,08-26 15:43:16.205  7087  7087 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-26 15:43:16.205  1014  1543 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-26 15:43:16.205  1014  1543 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-26 15:43:16.205  1014  1543 W ActivityManager: userId = 0, bbcId = -10000
08-26 15:43:16.205  1014  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 15:43:16.205  1014  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-26 15:43:16.215  7087  7087 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-26 15:43:16.215  3443  3443 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-26 15:43:16.215  3443  3443 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-26 15:43:16.215  3443  3443 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-26 15:43:16.215  3443  3443 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.215  3443  3443 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.215  3443  3443 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.215  3443  3443 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.215  3443  3443 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.215  3443  3443 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 15:43:16.225  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 15:43:16.225  6918  6918 I art     : Explicit concurrent mark sweep GC freed 514(39KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 809us total 68.237ms
,08-26 15:43:16.225  6918  7117 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-26 15:43:16.235  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.235  3729  7086 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-26 15:43:16.235  7087  7087 D elm:15183: ElmAgentService : onCreate()
,08-26 15:43:16.235  7087  7136 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-26 15:43:16.235  7087  7136 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-26 15:43:16.235  7087  7136 D elm:15183: MDMBridge.getInstance()
08-26 15:43:16.235  7087  7136 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
08-26 15:43:16.235  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.235  3729  7086 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-26 15:43:16.245  6530  6530 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 15:43:16.245  6530  6530 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 15:43:16.245  6530  6530 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 15:43:16.245  6530  6530 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-26 15:43:16.245  7087  7136 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 15:43:16.245  3729  3729 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-26 15:43:16.245  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.245  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 15:43:16.245  1014  1250 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-26 15:43:16.245  7118  7118 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-26 15:43:16.245  7118  7118 D ThemeInfoUtil: isCurrentFestival = false
08-26 15:43:16.245  1014  1490 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 15:43:16.245  1014  1490 D SecContentProvider2: mCursor = null
,08-26 15:43:16.245  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.245  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.255  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.255  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.255  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.255  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 15:43:16.255  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:16.265  7138  7138 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.265  7138  7138 E Zygote  : v2
,08-26 15:43:16.265  7138  7138 I libpersona: KNOX_SDCARD checking this for 10032
08-26 15:43:16.265  7138  7138 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.265  7138  7138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:43:16.275  1014  1250 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7138 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-26 15:43:16.275  7138  7138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:43:16.275  7138  7138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.275  1014  3278 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
08-26 15:43:16.285  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 15:43:16.285  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 15:43:16.285  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.285  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.285  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.285  1014  3278 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.285  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 15:43:16.305  1014  1125 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 15:43:16.305  1014  3278 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7150 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,08-26 15:43:16.305  7150  7150 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.305  7150  7150 E Zygote  : v2
08-26 15:43:16.305  7150  7150 I libpersona: KNOX_SDCARD checking this for 10152
08-26 15:43:16.305  7150  7150 I libpersona: KNOX_SDCARD not a persona
,08-26 15:43:16.305  7150  7150 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 15:43:16.305  7150  7150 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:43:16.305  7150  7150 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 15:43:16.315  7087  7087 D elm:15183: ElmAgentService : onDestroy().
08-26 15:43:16.315  7138  7138 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:16.315  7138  7138 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.325  1475  1475 D Launcher.Model: reloadBadges entered.
,08-26 15:43:16.325  5929  5954 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-26 15:43:16.325  5929  5954 D BadgeProvider: sendNotify, [notify] : null
08-26 15:43:16.325  5929  5954 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-26 15:43:16.325  5929  5954 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 15:43:16.325  5929  5954 D BadgeProvider: update, [UpdateCount] : 1
,08-26 15:43:16.335  7150  7150 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 15:43:16.335  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-26 15:43:16.335  7150  7150 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.335  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-26 15:43:16.335  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-26 15:43:16.335  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:16.345  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.345  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.345  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.345  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.355  7172  7172 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.355  7172  7172 E Zygote  : v2
,08-26 15:43:16.355  7172  7172 I libpersona: KNOX_SDCARD checking this for 1000
08-26 15:43:16.355  7172  7172 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:16.355  1014  1027 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7172 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 15:43:16.365  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 15:43:16.365  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 15:43:16.365  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 15:43:16.365  1014  1027 I ActivityManager: Killing 6034:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-26 15:43:16.385  1014  1473 I ActivityManager: Killing 6160:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-26 15:43:16.395  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 15:43:16.395  7172  7172 D ActivityThread: Added TimaKeyStore provider
,08-26 15:43:16.405  7138  7187 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-26 15:43:16.425  7097  7097 D NearbySource: Nearby Source Create!
08-26 15:43:16.425  1014  1250 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-26 15:43:16.425  7097  7097 D NearbyContext: Nearby Context Create!
,08-26 15:43:16.435  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.435  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.435  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 15:43:16.435  1014  1250 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 15:43:16.435  7138  7187 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-26 15:43:16.445  7189  7189 E Zygote  : MountEmulatedStorage()
08-26 15:43:16.445  7189  7189 E Zygote  : v2
08-26 15:43:16.445  7189  7189 I libpersona: KNOX_SDCARD checking this for 10035
08-26 15:43:16.445  7189  7189 I libpersona: KNOX_SDCARD not a persona
08-26 15:43:16.445  7189  7189 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-26 15:43:16.445  6652  6652 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 15:43:16.445  6652  6652 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 15:43:16.455  1014  1250 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7189 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 15:43:16.445  6652  6652 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 15:43:16.455  7138  7187 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 15:43:16.455  7189  7189 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051

```
