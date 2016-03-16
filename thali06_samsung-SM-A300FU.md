#### Test 63012666d6bb2e8_thali06_samsung-SM-A300FU Logs


```
--------- beginning of main,
03-16 14:33:51.043   288   288 E SMD     : DCD OFF
03-16 14:33:51.323  6187  6187 D AndroidRuntime: 
03-16 14:33:51.323  6187  6187 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 14:33:51.333  6187  6187 D AndroidRuntime: CheckJNI is OFF
03-16 14:33:51.333  6187  6187 D AndroidRuntime: readGMSProperty: start
03-16 14:33:51.333  6187  6187 D AndroidRuntime: readGMSProperty: already setted!!
03-16 14:33:51.333  6187  6187 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 14:33:51.333  6187  6187 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 14:33:51.333  6187  6187 D AndroidRuntime: readGMSProperty: end
03-16 14:33:51.333  6187  6187 D AndroidRuntime: addProductProperty: start
03-16 14:33:51.463  6187  6187 E AffinityControl: AffinityControl: registerfunction enter
03-16 14:33:51.483  6187  6187 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 14:33:51.493  1019  1349 E PersonaManagerService: inState():  stateMachine is null !!
03-16 14:33:51.493  1019  1349 I PersonaManagerService: PersonaId don't exist
03-16 14:33:51.493  1019  1349 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 14:33:51.503  1019  1349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
03-16 14:33:51.513  1019  1349 W ActivityManager: mDVFSHelper.acquire()
03-16 14:33:51.513  1019  1349 D FocusedStackFrame: Set to : 0
03-16 14:33:51.513  1019  1349 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:51.513  1019  1349 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:51.513  1019  1349 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:51.513  1019  1349 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:51.523  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 14:33:51.523  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 14:33:51.533  6199  6199 E Zygote  : MountEmulatedStorage()
03-16 14:33:51.533  6199  6199 E Zygote  : v2
03-16 14:33:51.533  6199  6199 I libpersona: KNOX_SDCARD checking this for 10167
03-16 14:33:51.533  6199  6199 I libpersona: KNOX_SDCARD not a persona
03-16 14:33:51.533  1019  1349 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6199 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 14:33:51.533  1019  1349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 14:33:51.533  1019  1349 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:33:51.533  1019  1349 D InputDispatcher: Focused application set to: xxxx
03-16 14:33:51.533  1019  1349 D InputDispatcher: Focus left window: 1480
03-16 14:33:51.533  6199  6199 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:33:51.533  6187  6187 D AndroidRuntime: Shutting down VM
03-16 14:33:51.533  6199  6199 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:33:51.543  6199  6199 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 14:33:51.543  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:33:51.543  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 14:33:51.543   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
03-16 14:33:51.553  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:33:51.553  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 14:33:51.563  6199  6199 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:33:51.563  6199  6199 D ActivityThread: Added TimaKeyStore provider
03-16 14:33:51.573  1019  1491 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 14:33:51.573  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 14:33:51.593   257  1099 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-16 14:33:51.593   257   445 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-16 14:33:51.603  1019  1491 D PersonaManager: isKioskContainerExistOnDevice
03-16 14:33:51.603  1480  1480 D Launcher: onTrimMemory. Level: 20
03-16 14:33:51.603  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{2a5ae479 token=android.os.BinderProxy@90f7d9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 14:33:51.613  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 14:33:51.703  6199  6199 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-16 14:33:51.713  6199  6199 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3043-3044)
03-16 14:33:51.713  6199  6199 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 14:33:51.743  6199  6199 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28daeb86}
03-16 14:33:51.743  6199  6199 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-16 14:33:51.743  6199  6199 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-16 14:33:51.743  6187  6187 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 14:33:51.773  6199  6199 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 14:33:51.773  6199  6199 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:33:51.773  6199  6199 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 14:33:51.793  6199  6199 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-16 14:33:51.793  6199  6199 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 14:33:51.793  6199  6199 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-16 14:33:51.793  6199  6199 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:33:51.793  6199  6199 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:33:51.793  6199  6199 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:33:51.793  6199  6199 I Adreno-EGL: Local Branch: 
03-16 14:33:51.793  6199  6199 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:33:51.793  6199  6199 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:33:51.793  6199  6199 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-16 14:33:52.013  6199  6199 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:33:52.033  6199  6199 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 14:33:52.033  6199  6199 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-16 14:33:52.033  6199  6199 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 14:33:52.043  6199  6199 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 14:33:52.053  6199  6199 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:33:52.053  6199  6199 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:33:52.103  6199  6239 D OpenGLRenderer: Render dirty regions requested: true
,03-16 14:33:52.103  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{9b9efd1 u0 com.test.thalitest/.MainActivity t23}
,03-16 14:33:52.113  1019  1583 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 14:33:52.113  1019  1583 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 14:33:52.113  1019  1583 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-16 14:33:52.113  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 14:33:52.113  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 14:33:52.113  6199  6226 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,03-16 14:33:52.123  6199  6199 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:33:52.123  6199  6199 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 14:33:52.133   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,03-16 14:33:52.153  1019  1583 D InputDispatcher: Focus entered window: 6199
,03-16 14:33:52.153  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:33:52.153  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 14:33:52.153  6199  6199 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 14:33:52.153  6199  6239 I OpenGLRenderer: Initialized EGL, version 1.4
,03-16 14:33:52.163  6199  6239 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 14:33:52.163  6199  6239 D OpenGLRenderer: Enabling debug mode 0
,03-16 14:33:52.193  6199  6199 V ActivityThread: updateVisibility : ActivityRecord{cc620e token=android.os.BinderProxy@146add10 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-16 14:33:52.223  1019  1349 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 14:33:52.233  1180  1180 I StatusBar: Icon Only
,03-16 14:33:52.233  1180  1180 D PanelView: There is/are notification(s) 
,03-16 14:33:52.243  1019  6241 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:33:52.243  6199  6199 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@146add10 time:203571,
,03-16 14:33:52.243  6199  6199 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 14:33:52.243  1019  1049 I ActivityManager: Displayed Component not be shown by security: +641ms (total +1m26s168ms)
,03-16 14:33:52.243  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9b9efd1 u0 com.test.thalitest/.MainActivity t23} time:203579
03-16 14:33:52.243  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-16 14:33:52.253   257  1100 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,03-16 14:33:52.253   257  1099 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,03-16 14:33:52.293  1783  1783 I SamsungIME: getCurrentCandidateView
,03-16 14:33:52.323  1783  1783 D SamsungIME: Dismiss ExpandCandiate
,03-16 14:33:52.353  1783  1783 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:33:52.393  1783  1783 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:33:52.423  1783  1783 I SamsungIME: KeybaordView init() : load resources
,03-16 14:33:52.443  1783  1783 I SamsungIME: getCurrentKeyboard
03-16 14:33:52.443  1783  1783 I SamsungIME: getTextKeyboard
,03-16 14:33:52.453  6199  6199 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6199
,03-16 14:33:52.473  1783  1783 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 14:33:52.593  6199  6199 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 14:33:52.803  6199  6242 D jxcore_app_log: JniHelper::setJavaVM(0xb76d7448), pthread_self() = -1211903600
,03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-16 14:33:52.813  6199  6242 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a26871f added. We now have 1 listener(s)
,03-16 14:33:52.813  6199  6242 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-16 14:33:52.813  6199  6242 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-16 14:33:52.823  6199  6242 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"},
03-16 14:33:52.823  6199  6242 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,03-16 14:33:52.823  6199  6242 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f74ca added. We now have 1 listener(s)
,03-16 14:33:52.823  6199  6242 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-16 14:33:52.833  6199  6242 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage,
,03-16 14:33:52.833  6199  6242 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-16 14:33:52.833  6199  6242 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-16 14:33:52.833  6199  6242 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-16 14:33:52.833  6199  6242 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 14:33:52.833  6199  6242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 14:33:52.843  6199  6242 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 14:33:52.843  6199  6242 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 14:33:52.843  6199  6242 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-16 14:33:52.843  6199  6242 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 14:33:52.853  6199  6199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,03-16 14:33:52.853  6199  6199 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:33:52.883  6199  6199 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 14:33:53.383  6199  6250 W jxcore-log: Initializing JXcore engine
03-16 14:33:53.383  6199  6250 W jxcore-log: JXcore engine is ready
,03-16 14:33:53.433  1833  1833 E audit   : type=1400 msg=audit(1458135233.433:205): avc:  denied  { ioctl } for  pid=6250 comm="Thread-1069" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-16 14:33:53.433  1833  1833 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-16 14:33:53.433  1833  1833 E audit   : type=1300 msg=audit(1458135233.433:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9d9fb8f8 items=0 ppid=307 ppcomm=main pid=6250 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1069" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 14:33:53.433  1833  1833 E audit   : type=1320 msg=audit(1458135233.433:205): 
,03-16 14:33:53.443  6199  6250 W jxcore-log: Starting JXcore engine
,03-16 14:33:53.543  6199  6250 W jxcore-log: Platform android
03-16 14:33:53.543  6199  6250 W jxcore-log: 
03-16 14:33:53.543  6199  6250 W jxcore-log: Process ARCH arm
03-16 14:33:53.543  6199  6250 W jxcore-log: 
,03-16 14:33:53.753  6199  6250 I jxcore-log: JXcore Cordova bridge is ready!
03-16 14:33:53.753  6199  6250 I jxcore-log: 
,03-16 14:33:53.753  6199  6250 W jxcore-log: JXcore engine is started
,03-16 14:33:53.753  6199  6242 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-16 14:33:53.763  6199  6199 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 14:33:53.773  6199  6250 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 14:33:53.773  6199  6250 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 14:33:53.783  6199  6199 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 14:33:53.783  6199  6199 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 14:33:53.783  1019  1497 D FocusedStackFrame: Set to : 0
03-16 14:33:53.783  1019  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:33:53.783  1019  1497 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 14:33:53.783  1019  1497 D InputDispatcher: Focused application set to: xxxx
03-16 14:33:53.783  1019  1497 D InputDispatcher: Focus left window: 6199
03-16 14:33:53.793  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:33:53.793  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 14:33:53.793  1019  1497 I ActivityManager: Killing 4205:com.sec.spp.push/u0a32 (adj 15): empty #31
,03-16 14:33:53.823   257  1100 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
03-16 14:33:53.823   257  1100 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,03-16 14:33:53.823  1019  1140 W ActivityManager: mDVFSHelper.acquire()
,03-16 14:33:53.833  1019  1140 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,03-16 14:33:53.843  6199  6199 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@cb6763b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 14:33:53.843  6199  6199 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@cb6763b that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:33:53.843  6199  6199 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:33:53.853  6199  6199 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2e588158 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 14:33:53.853  6199  6199 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2e588158 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:33:53.853  6199  6199 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:33:53.853  1480  1480 D Launcher: onRestart, Launcher: 254875037
,03-16 14:33:53.853  1480  1480 D Launcher: onStart, Launcher: 254875037
,03-16 14:33:53.853  1480  1480 D Launcher.HomeView: onStart
,03-16 14:33:53.863  1480  1480 D Launcher: onResume, Launcher: 254875037
03-16 14:33:53.863  1019  1526 D SettingsProvider: name = kids_home_mode
,03-16 14:33:53.863  1019  1526 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:33:53.863  1019  1526 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:33:53.863  1019  1526 D SettingsProvider: selectionArgs: false
03-16 14:33:53.863  1019  1526 D SettingsProvider: selectionArgs: 10006
,03-16 14:33:53.863  1019  1526 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:33:53.863  1019  1526 D SettingsProvider: ret = -1
,03-16 14:33:53.863  1480  1480 D Launcher.HomeView: onResume,
,03-16 14:33:53.863  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 14:33:53.873  1480  1480 D MenuAppsGridFragment: onResume
,03-16 14:33:53.873  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:53.873  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 14:33:53.873  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.873  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
03-16 14:33:53.873  1019  1220 D ActivityManager: handle home activity for 0
03-16 14:33:53.873  1019  1220 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 14:33:53.873  1019  1220 D KnoxTimeoutHandler: post home show event for user 0
03-16 14:33:53.873  1019  1220 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-16 14:33:53.873  1019  1220 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 14:33:53.873  1019  1220 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 14:33:53.873  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 14:33:53.873  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-16 14:33:53.873  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 14:33:53.873  1480  1480 D Launcher.HomeView: onPause
03-16 14:33:53.873  1480  1480 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 14:33:53.883  1019  1491 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
03-16 14:33:53.883  1019  1491 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-16 14:33:53.883  1019  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:53.883  1019  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.883   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
03-16 14:33:53.883  1019  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
03-16 14:33:53.883  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 14:33:53.893  4998  4998 D GalleryCacheReady: Receive : home resume
,03-16 14:33:53.893  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 14:33:53.893  1019  1583 D InputDispatcher: Focus entered window: 1480
,03-16 14:33:53.893  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:33:53.893  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 14:33:53.893  1480  1480 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 14:33:53.903  1019  3779 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:33:53.903  1480  1480 V ActivityThread: updateVisibility : ActivityRecord{2a5ae479 token=android.os.BinderProxy@90f7d9 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,03-16 14:33:53.903  1480  1480 D Launcher.HomeView: onStop
03-16 14:33:53.903  1019  3686 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
03-16 14:33:53.913  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.913  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.913  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 14:33:53.913  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.913  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.913  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
03-16 14:33:53.913  6199  6199 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-16 14:33:53.913  2413  2413 D Recents_RecreateReceiver: onReceive by home
,03-16 14:33:53.913  1019  1349 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.913  1019  6255 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 14:33:53.913  1019  1349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.913  1019  1349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,03-16 14:33:53.923  1180  1180 I StatusBar: Icon Only
03-16 14:33:53.923  1180  1180 D PanelView: There is/are notification(s) 
,03-16 14:33:53.933  1783  1783 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-16 14:33:53.933  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4205/cgroup.procs: No such file or directory
,03-16 14:33:53.943  5659  5659 D Mms/UIEventReceiver: ui event
03-16 14:33:53.943  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.943  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.943  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 14:33:53.943  1480  1480 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@90f7d9 time:205275
,03-16 14:33:53.943  1019  1349 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.943  1019  1349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.943  1019  1349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-16 14:33:53.943  6036  6036 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-16 14:33:53.953  1019  1349 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:53.953  1019  1349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.953  1019  1349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-16 14:33:53.953  1019  1349 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1480, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,03-16 14:33:53.963  1019  1349 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:53.963  1019  1349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.963  1019  1349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-16 14:33:53.963  1019  1349 I splitIntent: Queue : backgroundsplit_2 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-16 14:33:53.973  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:53.973  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:53.973  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,03-16 14:33:53.973  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{575b03f u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:205304
03-16 14:33:53.973  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-16 14:33:53.973  6036  6036 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-16 14:33:54.043   288   288 E SMD     : DCD OFF
,03-16 14:33:54.063  6251  6251 D AndroidRuntime: 
03-16 14:33:54.063  6251  6251 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 14:33:54.073  6251  6251 D AndroidRuntime: CheckJNI is OFF
,03-16 14:33:54.073  6251  6251 D AndroidRuntime: readGMSProperty: start
03-16 14:33:54.073  6251  6251 D AndroidRuntime: readGMSProperty: already setted!!
03-16 14:33:54.073  6251  6251 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 14:33:54.073  6251  6251 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 14:33:54.073  6251  6251 D AndroidRuntime: readGMSProperty: end
03-16 14:33:54.073  6251  6251 D AndroidRuntime: addProductProperty: start
,03-16 14:33:54.103  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-16 14:33:54.213  6251  6251 E AffinityControl: AffinityControl: registerfunction enter,
,03-16 14:33:54.243  6251  6251 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-16 14:33:54.253  1019  1479 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
03-16 14:33:54.253  1019  1479 D PackageManager: START PACKAGE DELETE: observer{243835045}
03-16 14:33:54.253  1019  1479 D PackageManager: pkg{<packageName>}
03-16 14:33:54.253  1019  1479 D PackageManager: user{0}
03-16 14:33:54.253  1019  1479 D PackageManager: caller{2000}
03-16 14:33:54.253  1019  1479 D PackageManager: flags{2}
03-16 14:33:54.253  1019  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,03-16 14:33:54.253  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 14:33:54.253  1019  1479 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 14:33:54.253  1019  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 14:33:54.253  1019  1479 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 14:33:54.253  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 14:33:54.253  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-16 14:33:54.253  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
,03-16 14:33:54.253  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-16 14:33:54.263  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
,03-16 14:33:54.263  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-16 14:33:54.263  1019  1044 I ActivityManager: Killing 6199:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-16 14:33:54.333  1019  1057 W PackageSettings: Skipping PackageSetting{defb31f com.example.hello/10346} due to missing metadata
,03-16 14:33:54.373  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-16 14:33:54.383  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-16 14:33:54.433  3976  3976 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 1.670ms total 40.974ms
,03-16 14:33:54.453  5993  5993 I art     : Explicit concurrent mark sweep GC freed 386(26KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/8MB, paused 851us total 74.771ms
,03-16 14:33:54.463  1019  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 14:33:54.473  1783  1783 E SamsungIME: mOCRHelper is null
,03-16 14:33:54.483  1851  2102 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 14:33:54.493  1019  1129 V NetworkStats: removeUidsLocked() for UIDs [10167]
,03-16 14:33:54.493  1019  1129 V NetworkStats: performPollLocked(flags=0x3)
03-16 14:33:54.493  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 14:33:54.493  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox updated
03-16 14:33:54.493  1019  1129 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-16 14:33:54.513  1019  1129 V NetworkStats: performPollLocked() took 24ms
,03-16 14:33:54.513  1019  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 14:33:54.543  3713  3713 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 14:33:54 GMT+01:00 2016
,03-16 14:33:54.543  1019  1349 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:54.543  1019  1349 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:33:54.543  1019  1349 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 14:33:54.553  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 14:33:54.553  1019  1130 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 14:33:54.563  3713  3713 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-16 14:33:54.563  1019  3427 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
,03-16 14:33:54.563  1019  3427 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-16 14:33:54.563  1019  3427 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-16 14:33:54.563  1019  3427 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
03-16 14:33:54.563  1019  3427 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:54.563  1019  3427 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:54.563  1019  3427 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:54.563  1019  3427 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:33:54.573  6269  6269 E Zygote  : MountEmulatedStorage()
03-16 14:33:54.583  6269  6269 E Zygote  : v2
,03-16 14:33:54.583  6269  6269 I libpersona: KNOX_SDCARD checking this for 10090
03-16 14:33:54.583  6269  6269 I libpersona: KNOX_SDCARD not a persona
03-16 14:33:54.583  6269  6269 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-16 14:33:54.583  6269  6269 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-16 14:33:54.583  6269  6269 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:33:54.603   307   307 I art     : Explicit concurrent mark sweep GC freed 8696(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 23.189ms
,03-16 14:33:54.603  1019  3427 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6269 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-16 14:33:54.613  3713  3713 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,03-16 14:33:54.623  3713  3713 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 14:33:54.623   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.660ms
,03-16 14:33:54.623  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-16 14:33:54.623  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-16 14:33:54.623  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-16 14:33:54.633  1019  1019 I art     : Explicit concurrent mark sweep GC freed 31161(2MB) AllocSpace objects, 11(180KB) LOS objects, 33% free, 24MB/36MB, paused 3.494ms total 248.261ms
,03-16 14:33:54.633  1019  1057 I art     : WaitForGcToComplete blocked for 216.991ms for cause Explicit
,03-16 14:33:54.643   307   307 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 17.010ms,
,03-16 14:33:54.653  1443  1443 D RegisteredServicesCache: empty dynamic service
,03-16 14:33:54.653  6269  6269 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:33:54.653  6269  6269 D ActivityThread: Added TimaKeyStore provider
,03-16 14:33:54.653  3713  3713 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 14:33:54.653  1019  3767 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 14:33:54.653  1019  3767 D SecContentProvider2: mCursor = null
03-16 14:33:54.653  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 14:33:54.663  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.673  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-16 14:33:54.673  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.673  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-16 14:33:54.683  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.683  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-16 14:33:54.703  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-16 14:33:54.703  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
03-16 14:33:54.703  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.703  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-16 14:33:54.703  6269  6269 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-16 14:33:54.703  6269  6269 D elm:15121: ELMEngine.ELMEngine( context ).
,03-16 14:33:54.703  6269  6269 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-16 14:33:54.713  1019  1599 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:54.713  1019  1599 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:54.713  1019  1599 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-16 14:33:54.713  6269  6269 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-16 14:33:54.723  6269  6269 D elm:15121: ElmAgentService : onCreate()
,03-16 14:33:54.723  6269  6285 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-16 14:33:54.733  6269  6285 D elm:15121: MainReceiver.listeningToPackageRemoved()
,03-16 14:33:54.733  6269  6285 D elm:15121: MDMBridge.getInstance()
03-16 14:33:54.733  6269  6285 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 14:33:54.733  6269  6285 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,03-16 14:33:54.743  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-16 14:33:54.753  3713  6268 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-16 14:33:54.763  3713  6268 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-16 14:33:54.763  6269  6269 D elm:15121: ElmAgentService : onDestroy().
,03-16 14:33:54.763  3713  3713 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-16 14:33:54.813  1019  1057 I art     : Explicit concurrent mark sweep GC freed 11883(586KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 3.247ms total 182.816ms
,03-16 14:33:54.833  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-16 14:33:54.843  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.853  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.863  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.863  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 14:33:54.863  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:33:54.863  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:33:54.863  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.883  1019  1057 D PackageManager: delete codoeFile: 
,03-16 14:33:54.883  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
,03-16 14:33:54.883  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-16 14:33:54.883  1019  1057 D PackageManager: result of delete: 1{243835045}
,03-16 14:33:54.883  6251  6251 D AndroidRuntime: Shutting down VM
,03-16 14:33:54.893  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 14:33:54.893  1019  1057 D PackageManager: userId{-1}
03-16 14:33:54.893  1019  1057 D PackageManager: andCode{true}
,03-16 14:33:54.913  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.913  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-16 14:33:54.913  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
03-16 14:33:54.913  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 14:33:54.913  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-16 14:33:54.923  1019  1162 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 14:33:54.923  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
03-16 14:33:54.923  1019  2750 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
,03-16 14:33:54.923  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.923  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.923  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:33:54.933  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.933  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:33:54.933  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:33:54.943  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:33:54.943  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:33:54.943  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:33:54.943  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-16 14:33:54.943  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-16 14:33:55.003  5707  5707 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-16 14:33:55.003  5707  5707 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:33:55.003  5707  5707 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,03-16 14:33:55.003  5707  5707 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-16 14:33:55.013  5796  5796 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-16 14:33:55.023  5796  5796 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-16 14:33:55.023  1019  3778 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:55.023  1019  3778 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:55.023  1019  3778 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-16 14:33:55.033  4998  4998 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-16 14:33:55.093  6251  6251 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 14:33:55.103  5659  5659 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-16 14:33:55.103  1019  1479 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:33:55.103  1019  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:55.103  1019  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-16 14:33:55.113  1019  1526 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:55.113  1019  1526 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:55.113  1019  1526 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-16 14:33:55.113  5659  6290 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,03-16 14:33:55.113  5659  6290 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
03-16 14:33:55.113  1019  1031 I TactileAssist: enable value -1
03-16 14:33:55.113  1019  1031 I TactileAssist: internal enable value -1
,03-16 14:33:55.113  1019  1031 I TactileAssist: intensity value -1
03-16 14:33:55.113  1019  1031 I TactileAssist: saveAppList value true
,03-16 14:33:55.123  1019  1031 I TactileAssist: List of disabled apps :,
,03-16 14:33:55.133  5882  5882 D Compatibility: onReceive() it will make start service
,03-16 14:33:55.133  1019  1220 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:55.133  1019  1220 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:55.143  1019  1220 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-16 14:33:55.143  1019  2750 D SSRM:n  : SIOP:: AP = 290
,03-16 14:33:55.143  1019  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:33:55.143  1019  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:55.143  1019  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:33:55.143  1019  1583 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:33:55.153  5882  6291 D Compatibility: onHandleIntent()
,03-16 14:33:55.163  6293  6293 E Zygote  : MountEmulatedStorage(),
03-16 14:33:55.163  6293  6293 I libpersona: KNOX_SDCARD checking this for 10055
03-16 14:33:55.163  6293  6293 E Zygote  : v2
03-16 14:33:55.163  6293  6293 I libpersona: KNOX_SDCARD not a persona
03-16 14:33:55.163  5882  6291 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
03-16 14:33:55.163  1019  1583 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6293 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
03-16 14:33:55.163  6293  6293 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-16 14:33:55.163  5882  6291 D Compatibility: found: 2
03-16 14:33:55.163  5882  6291 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-16 14:33:55.163  5882  6291 D Compatibility: skipping ResolveInfo{89d4c47 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-16 14:33:55.163  5882  6291 D Compatibility: considering ResolveInfo{1e214c74 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-16 14:33:55.163  5882  6291 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-16 14:33:55.163  5882  6291 D Compatibility: enabling receiver ResolveInfo{f31159d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-16 14:33:55.163  6293  6293 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-16 14:33:55.163  5882  6291 D Compatibility: enabling receiver ResolveInfo{ea3a12 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-16 14:33:55.163  6293  6293 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:33:55.173  5882  6291 D Compatibility: enabling receiver ResolveInfo{3d5865e3 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-16 14:33:55.173  5882  6291 D Compatibility: enabling receiver ResolveInfo{3e40bbe0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-16 14:33:55.183  5882  6291 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-16 14:33:55.193  6293  6293 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:33:55.193  6293  6293 D ActivityThread: Added TimaKeyStore provider
,03-16 14:33:55.223  6293  6293 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-16 14:33:55.253  6293  6293 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
03-16 14:33:55.253  6293  6293 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 14:33:55.253  6293  6293 D UserAnalysis: Create SecureDbHelper
,03-16 14:33:55.253  6293  6293 D IntelligenceServiceApplication: onCreate()
,03-16 14:33:55.253  6293  6293 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-16 14:33:55.253  6293  6293 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,03-16 14:33:55.263  6293  6293 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 14:33:55.263  6293  6293 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
,03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-16 14:33:55.263  6293  6293 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-16 14:33:55.263  6293  6293 W SQLiteOpenHelper: Opened privacy in read-only mode
,03-16 14:33:55.263  6293  6293 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 14:33:55.263  5904  5904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:33:55.263  6293  6293 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-16 14:33:55.263  1019  3778 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:33:55.263  1019  3778 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:33:55.263  1019  3778 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 14:33:55.273  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:55.273  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:55.273  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:33:55.273  1019  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:33:55.273  6293  6293 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-16 14:33:55.273  6293  6293 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)

```
