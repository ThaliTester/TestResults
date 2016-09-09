#### Test 8359176481a80d7_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
,09-09 22:02:03.258   291   291 E SMD     : DCD OFF
09-09 22:02:03.528  6238  6238 D AndroidRuntime: 
09-09 22:02:03.528  6238  6238 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 22:02:03.528  6238  6238 D AndroidRuntime: CheckJNI is OFF
09-09 22:02:03.528  6238  6238 D AndroidRuntime: readGMSProperty: start
09-09 22:02:03.528  6238  6238 D AndroidRuntime: readGMSProperty: already setted!!
09-09 22:02:03.528  6238  6238 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 22:02:03.528  6238  6238 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 22:02:03.528  6238  6238 D AndroidRuntime: readGMSProperty: end
09-09 22:02:03.528  6238  6238 D AndroidRuntime: addProductProperty: start
09-09 22:02:03.658  6238  6238 E AffinityControl: AffinityControl: registerfunction enter
09-09 22:02:03.688  6238  6238 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 22:02:03.698  1014  1137 E PersonaManagerService: inState():  stateMachine is null !!
09-09 22:02:03.698  1014  1137 I PersonaManagerService: PersonaId don't exist
09-09 22:02:03.698  1014  1137 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 22:02:03.698  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-09 22:02:03.708  1014  1137 W ActivityManager: mDVFSHelper.acquire()
09-09 22:02:03.718  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 22:02:03.718  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 22:02:03.718  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:03.718  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:03.728  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:03.728  1014  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:03.738  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 22:02:03.738  1014  1137 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6249 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 22:02:03.738  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 22:02:03.738  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-09 22:02:03.738  1014  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:03.738   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-09 22:02:03.738  6249  6249 E Zygote  : MountEmulatedStorage()
09-09 22:02:03.738  6249  6249 E Zygote  : v2
09-09 22:02:03.738  6249  6249 I libpersona: KNOX_SDCARD checking this for 10155
09-09 22:02:03.738  6249  6249 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:03.748  6249  6249 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:03.748  6249  6249 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:03.748  6249  6249 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 22:02:03.758  1014  1137 D InputDispatcher: Focused application set to: xxxx
09-09 22:02:03.758  1014  1137 D InputDispatcher: Focus left window: 3178
09-09 22:02:03.758  6238  6238 D AndroidRuntime: Shutting down VM
09-09 22:02:03.758  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:03.758  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 22:02:03.778  6249  6249 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:03.778  6249  6249 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:03.788  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 22:02:03.788  1014  1014 V ActivityManager: Display changed displayId=0
09-09 22:02:03.808  1014  1027 D PersonaManager: isKioskContainerExistOnDevice
09-09 22:02:03.828   257  4464 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-09 22:02:03.828   257   443 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-09 22:02:03.848  3178  3178 V ActivityThread: updateVisibility : ActivityRecord{1ae39c59 token=android.os.BinderProxy@145049e4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-09 22:02:03.928  6249  6249 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-09 22:02:03.948  6249  6249 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 3859-3860)
09-09 22:02:03.948  6249  6249 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 22:02:03.968  6238  6238 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 22:02:03.978  6249  6249 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16f5bb65}
,09-09 22:02:03.978  6249  6249 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 22:02:03.978  6249  6249 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 22:02:04.008  6249  6249 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 22:02:04.008  6249  6249 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:04.008  6249  6249 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 22:02:04.038  6249  6249 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-09 22:02:04.038  6249  6249 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-09 22:02:04.038  6249  6249 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-09 22:02:04.038  6249  6249 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:04.038  6249  6249 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:04.038  6249  6249 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:04.038  6249  6249 I Adreno-EGL: Local Branch: 
09-09 22:02:04.038  6249  6249 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:04.038  6249  6249 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:04.038  6249  6249 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:04.158  6249  6275 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-09 22:02:04.198  6249  6249 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:04.208  6249  6249 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 22:02:04.218  6249  6249 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-09 22:02:04.218  6249  6249 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 22:02:04.228  6249  6249 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 22:02:04.238  6249  6249 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:04.238  6249  6249 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 22:02:04.268   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:04.278  6249  6288 D OpenGLRenderer: Render dirty regions requested: true
,09-09 22:02:04.288  1014  3033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 22:02:04.288  1014  3033 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 22:02:04.288  1014  3033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 22:02:04.288  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-09 22:02:04.288  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 22:02:04.298  6249  6249 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-09 22:02:04.298  6249  6249 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 22:02:04.308   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-09 22:02:04.318  1014  2991 D InputDispatcher: Focus entered window: 6249
,09-09 22:02:04.318  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 22:02:04.328  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:04.328  6249  6249 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 22:02:04.328  6249  6288 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 22:02:04.328  6249  6288 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 22:02:04.328  6249  6288 D OpenGLRenderer: Enabling debug mode 0
,09-09 22:02:04.368  6249  6249 V ActivityThread: updateVisibility : ActivityRecord{300ad924 token=android.os.BinderProxy@20f59cb6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-09 22:02:04.398  1014  3239 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 22:02:04.398  1178  1178 D PanelView: There is/are notification(s) 
,09-09 22:02:04.398  1014  6291 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:04.408  1014  1044 I ActivityManager: Displayed Component not be shown by security: +598ms (total +691ms)
,09-09 22:02:04.408  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1163981e u0 com.test.thalitest/.MainActivity t128} time:114329
09-09 22:02:04.408  1014  1044 W ActivityManager: mDVFSHelper.release()
,09-09 22:02:04.418  1789  1789 I SamsungIME: getCurrentCandidateView
,09-09 22:02:04.418  6249  6249 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-09 22:02:04.418  6249  6249 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20f59cb6 time:114336
,09-09 22:02:04.418   257  4464 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-09 22:02:04.418   257   445 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-09 22:02:04.478  6249  6249 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6249
,09-09 22:02:04.488  1789  1789 D SamsungIME: Dismiss ExpandCandiate
,09-09 22:02:04.588  6249  6249 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 22:02:04.618  1789  1789 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 22:02:04.658  1789  1789 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 22:02:04.668  1789  1789 I SamsungIME: KeybaordView init() : load resources
,09-09 22:02:04.698  1789  1789 I SamsungIME: getCurrentKeyboard
09-09 22:02:04.698  1789  1789 I SamsungIME: getTextKeyboard
,09-09 22:02:04.718  1789  1789 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 22:02:04.718  6249  6292 D jxcore_app_log: JniHelper::setJavaVM(0xb7b61328), pthread_self() = -1207148368
,09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-09 22:02:04.718  6249  6292 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a68d354 added. We now have 1 listener(s)
,09-09 22:02:04.728  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-09 22:02:04.728  6249  6292 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 22:02:04.728  6249  6292 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:04.728  6249  6292 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 22:02:04.738  6249  6292 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e574243 added. We now have 1 listener(s)
09-09 22:02:04.738  6249  6292 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:04.738  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 22:02:04.738  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-09 22:02:04.738  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-09 22:02:04.738  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 22:02:04.738  6249  6292 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 22:02:04.748  6249  6292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:04.748  6249  6292 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-09 22:02:04.748  6249  6292 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:04.748  6249  6292 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:04.758  6249  6292 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 22:02:04.758  6249  6292 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:04.758  6249  6292 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 22:02:04.768  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:04.768  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:04.788  6249  6249 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 22:02:05.258  1789  6296 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 22:02:05.268   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:05.268  6249  6301 W jxcore-log: Initializing JXcore engine
09-09 22:02:05.268  6249  6301 W jxcore-log: JXcore engine is ready
,09-09 22:02:05.328  1903  1903 E audit   : type=1400 msg=audit(1473451325.328:205): avc:  denied  { ioctl } for  pid=6301 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 22:02:05.328  1903  1903 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:05.328  1903  1903 E audit   : type=1300 msg=audit(1473451325.328:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eb008f8 items=0 ppid=320 ppcomm=main pid=6301 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-09 22:02:05.328  1903  1903 E audit   : type=1320 msg=audit(1473451325.328:205): 
,09-09 22:02:05.348  6249  6301 W jxcore-log: Starting JXcore engine
,09-09 22:02:05.348  5440  5440 D FactoryTest: Not factory mode
,09-09 22:02:05.348  5440  5440 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-09 22:02:05.348  5440  5440 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-09 22:02:05.348  5440  5440 D MTPRx   : still no open session command from host, so toast
,09-09 22:02:05.348  5440  5440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-09 22:02:05.348  5440  5440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
09-09 22:02:05.348  5440  5440 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115269
,09-09 22:02:05.358  1014  1557 E PersonaManagerService: inState():  stateMachine is null !!
09-09 22:02:05.358  1014  1557 I PersonaManagerService: PersonaId don't exist
09-09 22:02:05.358  1014  1557 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-09 22:02:05.358  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 22:02:05.358  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:05.358  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:05.358  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-09 22:02:05.358  1014  1557 W ActivityManager: mDVFSHelper.acquire()
,09-09 22:02:05.378  1014  1557 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:05.378  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:05.378  1014  1557 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 22:02:05.388  1014  1557 D InputDispatcher: Focused application set to: xxxx
,09-09 22:02:05.388  1014  1557 D InputDispatcher: Focus left window: 6249
,09-09 22:02:05.388  5440  5440 E MTPRx   : started activity for popup
,09-09 22:02:05.388  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:05.388  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101,
,09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 22:02:05.418  5440  5440 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:05.438  5440  5440 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-09 22:02:05.438  1014  3233 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-09 22:02:05.438  1014  3233 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 22:02:05.438  1014  3233 D InputDispatcher: Focused application set to: xxxx
,09-09 22:02:05.438  1014  3233 D InputDispatcher: Focus entered window: 6249
,09-09 22:02:05.438  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 22:02:05.438  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:05.438  1014  1027 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 22:02:05.448  1014  1027 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@394dfca9 attribute=null, token = android.os.BinderProxy@146ed339
,09-09 22:02:05.458  6249  6301 W jxcore-log: Platform android
09-09 22:02:05.458  6249  6301 W jxcore-log: 
,09-09 22:02:05.468  6249  6301 W jxcore-log: Process ARCH arm
09-09 22:02:05.468  6249  6301 W jxcore-log: 
,09-09 22:02:05.478  5440  5440 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-09 22:02:05.488  5440  5440 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-09 22:02:05.488  5440  5440 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-09 22:02:05.508  6249  6249 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 22:02:05.508  6249  6249 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-09 22:02:05.508  6249  6249 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-09 22:02:05.508  6249  6249 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-09 22:02:05.508  1014  3239 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-09 22:02:05.508  1014  3239 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 22:02:05.508  1014  3239 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 22:02:05.508  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 22:02:05.508  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 22:02:05.528  6249  6249 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 22:02:05.528  6249  6249 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 22:02:05.528  6249  6249 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@276547d5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9f6b61d, 16908290=android.view.AbsSavedState$1@9f6b61d}, android:focusedViewId=100}]}]
09-09 22:02:05.528  6249  6249 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 22:02:05.528  6249  6249 V ActivityThread: updateVisibility : ActivityRecord{300ad924 token=android.os.BinderProxy@20f59cb6 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 22:02:05.528  6249  6249 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 22:02:05.528  6249  6249 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 22:02:05.528  6249  6249 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20f59cb6 time:115447
,09-09 22:02:05.528  1014  1558 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:05.678  6249  6301 I jxcore-log: JXcore Cordova bridge is ready!,
09-09 22:02:05.678  6249  6301 I jxcore-log: 
09-09 22:02:05.678  6249  6301 W jxcore-log: JXcore engine is started
,09-09 22:02:05.678  6249  6292 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 22:02:05.688  6249  6249 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 22:02:06.148  1014  1492 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-09 22:02:06.148  1014  1492 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3900, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 22:02:06.148  1014  1492 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 22:02:06.148  1014  1492 D BatteryService: stay LED for charging
,09-09 22:02:06.148  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:06.148  1014  1014 I MotionRecognitionService: Plugged
,09-09 22:02:06.148  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:06.148  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-09 22:02:06.148  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 22:02:06.158  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 22:02:06.158  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,09-09 22:02:06.168  2633  2633 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:06.168  2633  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-09 22:02:06.178  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:06.178  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:06.178  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:06.258   291   291 E SMD     : DCD OFF
,09-09 22:02:06.268   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:06.968  1014  2768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-09 22:02:07.268   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:08.268   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:08.358  1014  1039 W ActivityManager: mDVFSHelper.release(),
,09-09 22:02:08.998  1014  2729 D SSRM:n  : SIOP:: AP = 330
,09-09 22:02:09.258   291   291 E SMD     : DCD OFF,
,09-09 22:02:09.268   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-09 22:02:10.088  1014  1093 V AlarmManager: waitForAlarm result :4
,09-09 22:02:10.088  1014  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0,
,09-09 22:02:10.098  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___,
,09-09 22:02:10.098  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
09-09 22:02:10.098  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-09 22:02:10.108  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-09 22:02:10.108  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,09-09 22:02:10.118  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-09 22:02:10.118  1910  1910 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-09 22:02:10.128  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,09-09 22:02:10.148  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:10.148  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-09 22:02:10.148  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,09-09 22:02:10.168  1014  2992 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:10.168  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.168  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:10.168  1014  2992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.168  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.188  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:10.188  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:10.198  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:10.218  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-09 22:02:10.228  3839  3839 D ConnectivityManager: CallingUid : 10012, CallingPid : 3839
,09-09 22:02:10.228  1014  3233 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 22:02:10.228  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-09 22:02:10.238  1014  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-09 22:02:10.238  1014  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,09-09 22:02:10.238  3839  6307 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 22:02:10.288  3839  6308 W DriveInitializer: Background init thread started
,09-09 22:02:10.298   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-09 22:02:10.298   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:10.298  3839  6308 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-09 22:02:10.348  1014  2991 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:10.348  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.358  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.358  1014  2991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.358  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 22:02:10.388  1014  1557 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 22:02:10.388  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.388  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:10.398  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.398  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:10.398  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.398  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.418  3839  6315 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
09-09 22:02:10.418  3839  6315 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-09 22:02:10.428  3839  6308 W DriveInitializer: Background init thread ended
,09-09 22:02:10.448  1910  1910 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 22:02:10.468  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.478  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.478  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.548  1014  3240 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:10.548  1014  3240 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.558  1014  3240 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.558  1014  3240 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:10.558  1014  3240 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.588  1014  3033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:10.588  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.598  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.598  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:10.598  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.648  1014  2991 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:10.658  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.658  1014  2991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:10.658  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.708  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:10.718  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.718  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:10.718  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.778  1014  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:10.778  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.778  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.778  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.778  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:10.778  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:10.778  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:10.778  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:10.798  6321  6321 E Zygote  : MountEmulatedStorage()
,09-09 22:02:10.798  6321  6321 E Zygote  : v2
09-09 22:02:10.798  6321  6321 I libpersona: KNOX_SDCARD checking this for 10012
09-09 22:02:10.798  6321  6321 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:10.798  1014  1472 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6321 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-09 22:02:10.808  6321  6321 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:10.808  6321  6321 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:10.808  6321  6321 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:10.828  6321  6321 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:10.828  6321  6321 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:10.848  6321  6321 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 22:02:10.848  6321  6321 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 22:02:10.888  6321  6321 I MultiDex: VM with version 2.1.0 has multidex support
09-09 22:02:10.888  6321  6321 I MultiDex: install
09-09 22:02:10.888  6321  6321 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-09 22:02:10.928  6321  6321 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-09 22:02:10.938  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-09 22:02:10.958  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:10.958  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.958  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:10.958  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.958  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:10.968  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:10.968  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:10.968  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:10.988  6321  6321 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 22:02:10.998  6321  6321 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ae1ae16: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 22:02:10.998  6321  6321 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-09 22:02:10.998  1910  1910 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=73f21212-1d1d-4ec8-8e7a-cba68fe6733c
,09-09 22:02:11.008  1014  1345 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 22:02:11.008  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 22:02:11.008  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.008  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.008  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.008  1910  1910 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 22:02:11.018  1910  1910 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 22:02:11.018  6321  6321 D ChimeraCfgMgr: Reading stored module config
,09-09 22:02:11.038  1014  3033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.038  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.038  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.038  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.118  6321  6321 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 22:02:11.118  6321  6321 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-09 22:02:11.128  6321  6340 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-09 22:02:11.208   286   712 D WVCdm   : Instantiating CDM.
,09-09 22:02:11.208   286   703 I WVCdm   : CdmEngine::OpenSession
,09-09 22:02:11.208   286   703 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-09 22:02:11.218  1612  1699 I art     : Explicit concurrent mark sweep GC freed 1412(48KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 720us total 22.929ms
,09-09 22:02:11.238   286   703 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-09 22:02:11.248  1910  2121 I art     : Explicit concurrent mark sweep GC freed 55933(3MB) AllocSpace objects, 11(416KB) LOS objects, 39% free, 14MB/23MB, paused 1.402ms total 74.720ms
,09-09 22:02:11.258   286   703 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,09-09 22:02:11.258   286   703 D DrmWidevineDash: Service_Initialize: starts!
,09-09 22:02:11.258   286   703 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-09 22:02:11.258   286   703 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 22:02:11.258   286   703 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-09 22:02:11.258   286   703 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 22:02:11.258   286   703 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 22:02:11.258   286   703 D QSEECOMAPI: : App is not loaded in QSEE
09-09 22:02:11.268   286   703 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-09 22:02:11.268   286   703 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-09 22:02:11.268   286   703 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-09 22:02:11.268   286   703 D QSEECOMAPI: : App is not loaded in QSEE
,09-09 22:02:11.288   286   703 D QSEECOMAPI: : Loaded image: APP id = 11
,09-09 22:02:11.288   286   703 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-09 22:02:11.298   286   703 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-09 22:02:11.298   286   703 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-09 22:02:11.298   286   703 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb172a000
09-09 22:02:11.298   286   703 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb172a000
09-09 22:02:11.298   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.298  1910  2105 W GCoreFlp: No location to return for getLastLocation()
,09-09 22:02:11.298   435   446 D DrmLibTime: got the req here! ret=0
09-09 22:02:11.298   435   446 D DrmLibTime: command id, time_cmd_id = 770
09-09 22:02:11.298   435   446 D DrmLibTime: time_getutcsec starts!
09-09 22:02:11.298   435   446 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-09 22:02:11.298   435   446 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-09 22:02:11.298   435   446 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-09 22:02:11.298   435   446 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-09 22:02:11.298   435   446 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
09-09 22:02:11.298   435   446 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-09 22:02:11.298   435   446 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
09-09 22:02:11.298   435   446 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-09 22:02:11.298   339   432 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-09 22:02:11.308   339  6345 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
,09-09 22:02:11.308   339  6345 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-09 22:02:11.308   339  6345 D QC-time-services: offset is: 0 for base: 0
,09-09 22:02:11.308   435   446 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-09 22:02:11.308   435   446 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-09 22:02:11.308   435   446 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473451331
09-09 22:02:11.308   435   446 D DrmLibTime: time_getutcsec returns 0, sec = 1473451331; nsec = 0
09-09 22:02:11.308   435   446 D DrmLibTime: time_getutcsec finished! 
09-09 22:02:11.308   435   446 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-09 22:02:11.308   435   446 D DrmLibTime: before calling ioctl to read the next time_cmd
09-09 22:02:11.308   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.308   339   432 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-09 22:02:11.308   286   703 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-09 22:02:11.308   286   703 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-09 22:02:11.308   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 22:02:11.308   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.308   286   703 D DrmWidevineDash: hlos api version =  9
09-09 22:02:11.308   286   703 D DrmWidevineDash: tz api version =  9
09-09 22:02:11.308   286   703 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 22:02:11.308   286   703 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-09 22:02:11.308   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-09 22:02:11.338   286   703 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb195d960
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb83ac0f8, dataLength=8
09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb83695d8, wrapped_rsa_key_length=1280
09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.338   286   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 22:02:11.338   286   703 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-09 22:02:11.338   286   703 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-09 22:02:11.338   286   712 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-09 22:02:11.338   286   712 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-09 22:02:11.338   286   712 I WVCdm   : CdmEngine::GenerateKeyRequest
09-09 22:02:11.338   286   712 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb83301d8, idLength=0xb185f730
09-09 22:02:11.338   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.348  6321  6335 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-09 22:02:11.348  6321  6335 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:11.348  6321  6335 I System.out: (HTTPLog)-Static: isShipBuild true
,09-09 22:02:11.348  6321  6335 I System.out: (HTTPLog)-Thread-1060-11846827: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-09 22:02:11.348  6321  6335 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:11.358   281   939 D EnterpriseController: uids 10012
09-09 22:02:11.358   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:11.358   281   939 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 22:02:11.368  1014  3033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.368  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.368  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.368  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 22:02:11.368  3839  6317 D UdcContextInitService: registered all accounts: true
,09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,09-09 22:02:11.378  1014  3239 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 22:02:11.378  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:11.378  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.378  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb185f746, maximum = 0xb185f747
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: hlos api version =  9
09-09 22:02:11.378   286   712 D DrmWidevineDash: tz api version =  9
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb185f7b4
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-09 22:02:11.378   286   712 D WVCdm   : PrepareKeyRequest: nonce=2062292835
09-09 22:02:11.378   286   712 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb83311c0
09-09 22:02:11.378   286   712 D DrmWidevineDash: message_length=1599, signature=0xb8350510, signature_length=0xb185f714
09-09 22:02:11.378   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.378  1910  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 22:02:11.388  1014  2992 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.388  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.388  1014  2992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.388  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.398  1910  2121 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-09 22:02:11.408  6321  6335 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 22:02:11.408  6321  6335 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6321, getuid(): 10012
,09-09 22:02:11.528  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:11.528  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-09 22:02:11.528  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.528  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.528  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.548   286   712 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-09 22:02:11.548   286   712 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-09 22:02:11.548   286   286 I WVCdm   : CdmEngine::CloseSession
09-09 22:02:11.548   286   286 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-09 22:02:11.548   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-09 22:02:11.558   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
09-09 22:02:11.558   286   286 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-09 22:02:11.558   286   286 I WVCdm   : L3 Terminate.,
09-09 22:02:11.558   286   286 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-09 22:02:11.558   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-09 22:02:11.558   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-09 22:02:11.558   286   286 D DrmWidevineDash: Service_Uninitialize: starts!
09-09 22:02:11.558   286   286 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-09 22:02:11.558   286   286 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-09 22:02:11.558   286   286 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
09-09 22:02:11.558   286   286 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-09 22:02:11.618  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.618  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.618  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.618  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.728  6321  6335 I qtaguid : Untagging socket 30
,09-09 22:02:11.788  1014  3239 I art     : Explicit concurrent mark sweep GC freed 34919(1865KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 27MB/41MB, paused 2.482ms total 151.748ms
,09-09 22:02:11.788  1014  3239 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-09 22:02:11.788  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-09 22:02:11.788  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:11.788  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.788  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.818  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.828  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:11.828  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.828  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.858  1014  3233 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-09 22:02:11.858  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 22:02:11.858  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.858  1014  3233 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:11.858  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.868  1910  2121 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:11.868   281   939 D EnterpriseController: uids 10012
09-09 22:02:11.868   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:11.868   281   939 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 22:02:11.868  1910  2121 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 22:02:11.868  1910  2121 I qtaguid : Tagging socket 76 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:11.888  1014  3239 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.888  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.888  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.888  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.888  1910  6352 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 22:02:11.888  1910  6350 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 22:02:11.888  1014  1472 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.888  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.888  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.888  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.908  1910  2121 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:11.918  1014  3239 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.918  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.918  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:11.918  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.918  1910  6352 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 22:02:11.918  1910  6350 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 22:02:11.918  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.918  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:11.918  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.918  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,09-09 22:02:11.948  1014  1371 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:11.948  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:11.948  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:11.948  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:11.948  1910  6352 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-09 22:02:11.948  1910  6350 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-09 22:02:11.948  1910  6350 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-09 22:02:11.968  1910  6350 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 22:02:12.028  1014  1137 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 22:02:12.068  1910  6350 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.068   281   939 D EnterpriseController: uids 10012
09-09 22:02:12.068   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:12.068   281   939 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 22:02:12.068  1910  6350 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-09 22:02:12.068  1910  6350 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1910, getuid(): 10012
,09-09 22:02:12.108  1910  6350 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1910, getuid(): 10012
,09-09 22:02:12.258   291   291 E SMD     : DCD OFF
,09-09 22:02:12.298  6358  6358 I dex2oat : ----------------------------------------------------,
09-09 22:02:12.298  6358  6358 I dex2oat : <SS>: S T A R T I N G . . .
09-09 22:02:12.298  6358  6358 I dex2oat : <SS>: Zip is absent. Canceled.
09-09 22:02:12.298  6358  6358 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-09 22:02:12.338  6358  6358 I dex2oat : dex2oat took 34.723ms (threads: 4)
,09-09 22:02:12.348  6321  6335 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:12.348  6321  6335 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:12.348  6321  6335 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:12.348  6321  6335 I Adreno-EGL: Local Branch: 
09-09 22:02:12.348  6321  6335 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:12.348  6321  6335 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:12.348  6321  6335 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:12.398  1014  1137 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 22:02:12.408  1910  6350 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.408  1910  6350 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1910, getuid(): 10012
,09-09 22:02:12.438  6321  6335 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:12.438  6321  6335 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:12.438  6321  6335 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:12.438  6321  6335 I Adreno-EGL: Local Branch: 
09-09 22:02:12.438  6321  6335 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:12.438  6321  6335 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:12.438  6321  6335 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:12.488  6321  6335 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-09 22:02:12.488  6321  6335 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:12.488  6321  6335 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:12.488  6321  6335 I Adreno-EGL: Local Branch: 
09-09 22:02:12.488  6321  6335 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:12.488  6321  6335 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:12.488  6321  6335 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:12.548  1014  1558 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 22:02:12.558  1910  6350 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.558  1910  6350 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1910, getuid(): 10012
,09-09 22:02:12.708  1014  1345 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-09 22:02:12.718  1910  6350 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.718  1910  6350 I qtaguid : Tagging socket 81 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1910, getuid(): 10012
,09-09 22:02:12.728  1910  6319 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.728  1910  6319 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 22:02:12.728  1910  6319 I qtaguid : Tagging socket 74 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:12.768  1910  6319 I qtaguid : Tagging socket 87 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:12.918  1910  2121 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 22:02:12.918  1910  2121 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-09 22:02:12.928  1910  2121 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-09 22:02:11.539+0200, stopTime=2016-09-09 22:02:12.934+0200, duration=1395ms
,09-09 22:02:12.938  1910  6367 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:12.938   281   939 D EnterpriseController: uids 10012
09-09 22:02:12.938   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:12.938   281   939 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-09 22:02:12.938  1910  6367 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 22:02:12.938  1910  6367 I qtaguid : Tagging socket 71 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:12.988  1910  6367 I qtaguid : Tagging socket 73 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:13.018  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 22:02:13.238  1910  6367 I qtaguid : Untagging socket 71
,09-09 22:02:13.238  1910  2121 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-09 22:02:13.768  1014  1053 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-09 22:02:14.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:15.078  1910  6366 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:15.078  1910  6366 I qtaguid : Tagging socket 71 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1910, getuid(): 10012
,09-09 22:02:15.258   291   291 E SMD     : DCD OFF
,09-09 22:02:15.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:15.318  1910  6366 I qtaguid : Untagging socket 71
,09-09 22:02:15.328  1910  2127 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-09 22:02:15.348  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-09 22:02:16.208  1014  3240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:16.208  1014  3240 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3917, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-09 22:02:16.208  1014  3240 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 22:02:16.208  1014  3240 D BatteryService: stay LED for charging
09-09 22:02:16.208  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:16.208  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 22:02:16.208  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 22:02:16.208  1014  1014 I MotionRecognitionService: Plugged
09-09 22:02:16.208  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
09-09 22:02:16.208  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 22:02:16.218  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,09-09 22:02:16.218  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:16.218  2633  2633 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:16.228  2633  2726 D HeadsetStateMachine: Disconnected process message: 10
,09-09 22:02:16.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2,
09-09 22:02:16.238  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:16.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:17.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:17.718  1014  1558 I ActivityManager: Killing 5357:com.google.android.talk/u0a104 (adj 15): empty #31
,09-09 22:02:18.258   291   291 E SMD     : DCD OFF
,09-09 22:02:18.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:18.278  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-09 22:02:18.278  6249  6301 I jxcore-log: 
,09-09 22:02:18.278  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-09 22:02:18.278  6249  6301 I jxcore-log: 
,09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:18.288  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:18.288  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:18.288  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 22:02:18.288  6249  6301 I jxcore-log: 
,09-09 22:02:18.288  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 22:02:18.288  6249  6301 I jxcore-log: 
,09-09 22:02:18.918  6249  6301 D executeNativeTests: Running unit tests
,09-09 22:02:18.998  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:18.998  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 added. We now have 2 listener(s)
,09-09 22:02:18.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 22:02:18.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:18.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:18.998  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:18.998  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 added. We now have 2 listener(s)
09-09 22:02:18.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:18.998  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:18.998  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.008  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:19.008  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:19.008  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:19.008  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.008  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 22:02:19.008  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 22:02:19.008  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 22:02:19.018  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.018  6249  6301 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,09-09 22:02:19.018  6249  6301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 22:02:19.018  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 22:02:19.018  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:19.018  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:19.018  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:19.028  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:19.028  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:19.028  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.028  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-09 22:02:19.028  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 removed from the list
,09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.028  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 removed from the list
,09-09 22:02:19.028  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.028  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:19.028  1014  2729 D SSRM:n  : SIOP:: AP = 340
09-09 22:02:19.028  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.028  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.028  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.028  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
,09-09 22:02:19.038  6249  6301 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
,09-09 22:02:19.038  1014  1046 I PowerManagerService: [PWL] Off : 50s ago,
09-09 22:02:19.038  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.038  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.038  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-09 22:02:19.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-09 22:02:19.038  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:19.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.038  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
,09-09 22:02:19.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.038  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list,
09-09 22:02:19.038  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.038  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 22:02:19.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.038  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-09 22:02:19.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:19.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:19.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-09 22:02:19.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.038  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 22:02:19.048  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:19.048  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:19.048  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.048  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:19.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.048  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.048  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.048  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.048  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.048  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.048  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
,09-09 22:02:19.048  6249  6301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 22:02:19.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.058  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 22:02:19.058  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:19.058  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:19.058  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:19.058  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:19.058  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 22:02:19.058  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:19.058  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 22:02:19.068  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:19.068  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 22:02:19.068  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.078  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:19.078  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:19.078  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage,
,09-09 22:02:19.088  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 22:02:19.088  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 22:02:19.088  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:19.098  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,09-09 22:02:19.108  2633  2647 D BtGatt.GattService: registerClient() - UUID=ee9e45aa-df6d-4653-82c1-05947138f8ca
,09-09 22:02:19.158  2633  2720 D BtGatt.GattService: onClientRegistered() - UUID=ee9e45aa-df6d-4653-82c1-05947138f8ca, clientIf=6
,09-09 22:02:19.158  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:19.158  2633  2970 D BtGatt.GattService: start scan with filters
,09-09 22:02:19.158  2633  2724 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:19.158  2633  2724 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:19.158  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-09 22:02:19.158  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:19.158  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:19.158  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:19.168  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.168  2633  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:19.168  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.168  2633  2724 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:19.168  2633  2724 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 22:02:19.178  2633  2724 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 22:02:19.178  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:19.178  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.178  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:19.178  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:19.178  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.188  6249  6301 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 22:02:19.188  2633  2724 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 22:02:19.188  2633  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:19.188  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:19.188  6249  6301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 22:02:19.188  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:19.188  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 22:02:19.188  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:19.198  2633  2970 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:19.198  2633  2651 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:19.198  2633  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:19.198  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:19.198  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:19.198  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 22:02:19.208  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:19.208  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 22:02:19.208  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-09 22:02:19.208  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.208  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.208  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:19.208  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.208  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 22:02:19.208  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.208  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.208  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 22:02:19.208  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.208  6249  6301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 22:02:19.208  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:19.228  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.228  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:19.228  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:19.228  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:19.228  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:19.228  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:19.228  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:19.228  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.238  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:19.238  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.238  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:19.248  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:19.248  2633  2724 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 79
,09-09 22:02:19.248  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:19.248  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:19.248  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:19.248  2633  2970 D BtGatt.GattService: registerClient() - UUID=69b04857-89d6-4433-91cb-85ebb7b4d20a
,09-09 22:02:19.258  2633  2724 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:19.258  2633  2724 D BtGatt.ScanManager: delete FilterIndex - 3
,09-09 22:02:19.268  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 22:02:19.268  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:19.268  2633  2724 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:19.268  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:19.268  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.268  2633  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:19.278   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-09 22:02:19.278  2633  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:19.278  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.298  2633  2720 D BtGatt.GattService: onClientRegistered() - UUID=69b04857-89d6-4433-91cb-85ebb7b4d20a, clientIf=6
,09-09 22:02:19.298  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:19.298  2633  2647 D BtGatt.GattService: start scan with filters
,09-09 22:02:19.298  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 22:02:19.298  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 22:02:19.298  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:19.298  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:19.298  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.298  2633  2724 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:19.308  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:19.308  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.308  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:19.308  6249  6301 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 22:02:19.308  2633  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:19.308  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.318  2633  2724 D BtGatt.ScanManager: allow scan with filters
09-09 22:02:19.318  2633  2724 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:19.318  2633  2724 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 22:02:19.318  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:19.318  6249  6301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 22:02:19.318  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:19.318  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 22:02:19.318  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.318  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 22:02:19.318  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:19.318  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:19.318  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:19.318  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:19.318  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:19.318  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:19.318  2633  2647 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:19.318  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:19.318  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.328  2633  2651 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:19.328  2633  2724 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:19.328  2633  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:19.328  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:19.328  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 22:02:19.328  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:19.328  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:19.338  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-09 22:02:19.338  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:19.338  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.338  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:19.338  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.338  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.338  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:19.338  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:19.338  2633  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:19.338  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.338  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
,09-09 22:02:19.338  6249  6301 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 22:02:19.338  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:19.338  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:19.358  2633  2724 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 80
,09-09 22:02:19.358  2633  2724 D BtGatt.ScanManager: filter size is 1
,09-09 22:02:19.358  2633  2724 D BtGatt.ScanManager: delete FilterIndex - 4
,09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.358  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:19.368  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 22:02:19.368  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.368  2633  2724 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:19.368  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:19.368  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:19.368  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:19.368  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:19.368  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:19.368  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:19.368  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:19.368  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.378  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:19.378  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.378  2633  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:19.378  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.378  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:19.388  2633  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:19.388  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:19.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:19.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:19.388  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 22:02:19.388  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:19.388  2633  2647 D BtGatt.GattService: registerClient() - UUID=54a2f200-732f-433a-807d-7bb8ced67b69
,09-09 22:02:19.438  2633  2720 D BtGatt.GattService: onClientRegistered() - UUID=54a2f200-732f-433a-807d-7bb8ced67b69, clientIf=6
,09-09 22:02:19.438  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:19.438  2633  2651 D BtGatt.GattService: start scan with filters
,09-09 22:02:19.438  2633  2724 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:19.438  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 22:02:19.438  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:19.438  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 22:02:19.438  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:19.448  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.448  2633  2720 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:19.448  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.448  2633  2724 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:19.448  2633  2724 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 22:02:19.448  2633  2724 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-09 22:02:19.448  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:19.448  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:19.458  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:19.458  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.458  2633  2724 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:19.458  2633  2724 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:19.458  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:19.458  2633  2720 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 22:02:19.458  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.468  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:19.468  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:19.478  6249  6301 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 22:02:19.478  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 22:02:19.478  6249  6301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-09 22:02:19.478  2633  2724 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 81
,09-09 22:02:19.478  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.478  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 22:02:19.478  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 22:02:19.478  2633  5265 D BtGatt.GattService: stopScan() - queue size =1
09-09 22:02:19.478  2633  2724 D BtGatt.ScanManager: filter size is 1
09-09 22:02:19.478  2633  2724 D BtGatt.ScanManager: delete FilterIndex - 5
09-09 22:02:19.478  2633  2970 D BtGatt.GattService: unregisterClient() - clientIf=6
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:19.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 22:02:19.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:19.488  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:19.488  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:19.488  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.488  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.488  6249  6301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 22:02:19.488  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is d,iscovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.488  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.488  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.488  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.488  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.488  2633  2720 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:19.488  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:19.488  2633  2724 D BtGatt.ScanManager: stopping BLe Batch
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.488  6249  6301 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 22:02:19.488  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.488  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.488  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.488  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.488  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.488  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.488  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.498  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 22:02:19.498  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.498  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.498  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.498  2633  2720 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.498  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:19.498  2633  2724 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.498  6249  6301 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-09 22:02:19.498  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.498  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.498  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.498  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.498  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.508  6249  6301 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.508  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.508  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 22:02:19.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 22:02:19.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 22:02:19.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.508  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.508  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.508  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:19.508  6249  6301 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-09 22:02:19.508  2633  2720 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 22:02:19.508  2633  2720 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:19.508  6249  6301 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 22:02:19.508  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 22:02:19.508  6249  6301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:19.508  6249  6301 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:19.508  6249  6301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:19.508  6249  6301 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 22:02:19.508  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:19.508  6249  6301 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 22:02:19.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 22:02:19.518  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-09 22:02:19.518  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 22:02:19.518  6249  6301 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 22:02:19.518  6249  6301 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 22:02:19.518  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.518  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.518  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.518  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.518  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.518  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 22:02:19.518  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.518  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.518  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.518  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.518  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.518  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.518  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.518  6249  6380 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.518  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.518  6249  6381 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
09-09 22:02:19.528  6249  6301 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
,09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 22:02:19.528  6249  6301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:19.528  6249  6301 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 22:02:19.528  6249  6301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:19.528  6249  6301 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 22:02:19.528  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.528  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.528  6249  6380 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.528  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.528  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.528  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.528  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.538  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.538  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.538  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.538  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.538  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.538  6249  6380 D BluetoothSocket: connect(): myUserId = 0
09-09 22:02:19.538  6249  6380 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 22:02:19.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:19.538  2633  2970 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:19.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 22:02:19.538  6249  6380 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:19.548  6249  6249 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:19.548  6249  6249 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6382 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.548  6249  6382 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.548  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:19.548  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.548  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.548  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.548  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.548  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6249 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.548  6249  6301 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 22:02:19.548  6249  6301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 22:02:19.548  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 22:02:19.548  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.548  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.548  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.548  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.558  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.558  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.558  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.558  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.558  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:19.558  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:19.558  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29404242 not in the list
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.558  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:19.558  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:19.558  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:19.558  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25988253 not in the list
09-09 22:02:19.568  6249  6301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:19.568  6249  6301 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 22:02:19.568  6249  6301 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-09 22:02:19.568  6249  6301 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 22:02:19.568  6249  6301 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 22:02:19.568  6249  6301 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-09 22:02:19.568  6249  6301 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 22:02:19.568  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:19.568  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27ed86fd added. We now have 2 listener(s),
09-09 22:02:19.568  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:19.568  6249  6301 D BluetoothAdapter: enable()
09-09 22:02:19.568  6249  6301 D BluetoothAdapter: enable(): BT is already enabled..!
09-09 22:02:19.568  1014  2992 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:19.568  1014  2992 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:19.568  1014  2992 D SecContentProvider2: mCursor = null
09-09 22:02:19.578  1014  2992 D WifiService: setWifiEnabled: true pid=6249, uid=10155
09-09 22:02:19.578  1014  2992 W ActivityManager: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:19.578  1014  2992 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:19.578  1014  2992 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:19.578  1014  2992 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 22:02:19.578  1014  2992 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:19.578  1014  2992 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:19.578  1014  2992 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:19.578  1014  2992 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 22:02:19.578  1014  2992 D SettingsProvider: name = wifi_on
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f1bff2 added. We now have 3 listener(s)
09-09 22:02:19.578  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d96a643 added. We now have 4 listener(s)
09-09 22:02:19.578  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:19.578  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3a9f64c0 added. We now have 5 listener(s)
09-09 22:02:19.578  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:19.588  1014  2991 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:19.588  1014  2991 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:19.588  1014  2991 D SecContentProvider2: mCursor = null
09-09 22:02:19.588  1014  2991 D WifiService: setWifiEnabled: false pid=6249, uid=10155
09-09 22:02:19.588  1014  2991 D SettingsProvider: name = wifi_on
09-09 22:02:19.598  6249  6301 D BluetoothAdapter: disable()
09-09 22:02:19.598  1014  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-09 22:02:19.598  2099  2099 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:19.598  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-09 22:02:19.598  1014  3033 D SettingsProvider: name = bluetooth_on
09-09 22:02:19.598  2099  2099 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:19.598  2099  2099 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-09 22:02:19.598  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 22:02:19.608  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:19.608  2099  2099 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-09 22:02:19.608  2099  2099 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-09 22:02:19.608  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
09-09 22:02:19.608  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:19.608  2633  2716 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 22:02:19.608  2633  2716 D BluetoothAdapterProperties: Setting state to 13
09-09 22:02:19.608  2633  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 22:02:19.608  2633  2716 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-09 22:02:19.608  2633  2716 D BluetoothAdapterService: updateAdapterState state is 13
09-09 22:02:19.608  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:19.608  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.608  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
09-09 22:02:19.608  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:19.608  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:19.618  2633  2633 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
09-09 22:02:19.618  2633  2633 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@217fce8f, channel: 19, state: LISTENING
09-09 22:02:19.618  2633  2633 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@217fce8f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@260397, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5f4b51cmSocket: android.net.LocalSocket@807d525 impl:android.net.LocalSocketImpl@de536fa fd:FileDescriptor[74]
09-09 22:02:19.618  2633  2633 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@807d525 impl:android.net.LocalSocketImpl@de536fa fd:FileDescriptor[74]
,09-09 22:02:19.618  2633  2716 D BluetoothAdapterService: Autoconnection is available 
,09-09 22:02:19.618  2633  2716 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-09 22:02:19.618  2633  2716 D BluetoothAdapterService: terminating service from this receiver
,09-09 22:02:19.618  1327  1327 D BluetoothPbap: Proxy object disconnected
09-09 22:02:19.618  1327  1327 D PbapServerProfile: Bluetooth service disconnected
,09-09 22:02:19.618  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.618  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:19.618  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.618  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
09-09 22:02:19.618  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:19.618  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:19.618  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-09 22:02:19.628  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.628  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.628  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:19.638  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:19.638  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:19.638  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-09 22:02:19.638  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:19.638  2633  2633 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28260708, channel: 5, state: LISTENING
09-09 22:02:19.638  2633  2633 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28260708, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@311b984, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@26859ea1mSocket: android.net.LocalSocket@2ebfc8c6 impl:android.net.LocalSocketImpl@25f90087 fd:FileDescriptor[76]
09-09 22:02:19.638  2633  2633 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ebfc8c6 impl:android.net.LocalSocketImpl@25f90087 fd:FileDescriptor[76]
,09-09 22:02:19.638  1014  1345 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-09 22:02:19.638  1014  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:19.638  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 22:02:19.638  1789  1789 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:19.638  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:19.648  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:19.648  2633  2633 I BtOppRfcommListener: stopping Accept Thread
09-09 22:02:19.648  2633  2633 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@38988bb4, channel: 12, state: LISTENING
09-09 22:02:19.648  2633  2633 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@38988bb4, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd869ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14bc83ddmSocket: android.net.LocalSocket@1e5fab52 impl:android.net.LocalSocketImpl@285b1e23 fd:FileDescriptor[80]
09-09 22:02:19.648  2633  2633 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e5fab52 impl:android.net.LocalSocketImpl@285b1e23 fd:FileDescriptor[80]
,09-09 22:02:19.648  2633  5013 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 22:02:19.648  2633  5013 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 22:02:19.648  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:19.648  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-09 22:02:19.648  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.648  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:19.648  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:19.648  1014  1322 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:19.648  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 22:02:19.648  2633  2716 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 22:02:19.648  2633  2716 D BluetoothAdapterProperties: mDiscovering is false
,09-09 22:02:19.648  1014  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:19.648  1014  1322 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.648  1014  1322 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:19.648  1014  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:19.648  2633  2716 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 22:02:19.658  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 22:02:19.658  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.658  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 22:02:19.658  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:19.668  2633  2720 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:19.668  2633  2720 D BluetoothAdapterProperties: Scan Mode:20
,09-09 22:02:19.668  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 22:02:19.678  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:19.678  2633  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-09 22:02:19.678  2633  2716 E bt-btif : btif_dm_generic_evtnup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-09 22:02:19.678  2633  2716 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-09 22:02:19.678  2633  2716 E bt-btif : cmd socket is not created
,09-09 22:02:19.678  2633  2808 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 22:02:19.678  2633  2808 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 22:02:19.678  2633  2716 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:19.678  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:19.678  1014  2991 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:19.678  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:19.678  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:19.678  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:19.678  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-09 22:02:19.678  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:19.678  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:19.678  2633  2808 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:19.688  2633  2633 V BluetoothOppManager: cleanUp...
,09-09 22:02:19.698  1327  1327 D DockEventReceiver: finishStartingService: stopping service
09-09 22:02:19.698  6249  6380 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@357e93e, channel: -1, state: INIT
09-09 22:02:19.698  6249  6380 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@357e93e, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1973639f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2a760cecmSocket: android.net.LocalSocket@36bb98b5 impl:android.net.LocalSocketImpl@7655b4a fd:FileDescriptor[109]
09-09 22:02:19.698  6249  6380 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@36bb98b5 impl:android.net.LocalSocketImpl@7655b4a fd:FileDescriptor[109]
,09-09 22:02:19.698  6249  6380 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
,09-09 22:02:19.698  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:19.708  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:19.708  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 22:02:19.708  1014  3233 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-09 22:02:19.708  1014  3233 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 22:02:19.708  1014  3233 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.708  1014  3233 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.708  1014  3233 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:19.728  6388  6388 E Zygote  : MountEmulatedStorage(),
09-09 22:02:19.728  6388  6388 E Zygote  : v2
09-09 22:02:19.728  6388  6388 I libpersona: KNOX_SDCARD checking this for 10003
09-09 22:02:19.728  6388  6388 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:19.728  1014  3233 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6388 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-09 22:02:19.728  6388  6388 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:19.738  6388  6388 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:19.738  6388  6388 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.768  6388  6388 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:19.768  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 22:02:19.768  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-09 22:02:19.768  6388  6388 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.768   281   943 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:19.768  1910  4413 V NativeCrypto: Read error: ssl=0xb8012fc8: I/O error during system call, Connection timed out
09-09 22:02:19.778  1910  4413 V NativeCrypto: SSL shutdown failed: ssl=0xb8012fc8: I/O error during system call, Broken pipe
,09-09 22:02:19.778  1910  4413 E GCM     : Wifi connection closed with errorCode 20
,09-09 22:02:19.778  1014  1137 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-09 22:02:19.778  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:19.778  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:19.778  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-09 22:02:19.778  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:19.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 22:02:19.778  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:19.778  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-09 22:02:19.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.778  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:19.778  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:19.778  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:19.778  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,09-09 22:02:19.778  1014  2215 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 22:02:19.778  1014  2215 I qtaguid : Tagging socket 356 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
,09-09 22:02:19.788  1014  2215 I qtaguid : Untagging socket 356
,09-09 22:02:19.788  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
09-09 22:02:19.788  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-09 22:02:19.788  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 22:02:19.788  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:19.788  1014  2215 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:19.798  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 22:02:19.798  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:19.798  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:19.798  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.798  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.798  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.798  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:19.798  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 22:02:19.798  1014  1014 D RttService: SCAN_AVAILABLE : 1
,09-09 22:02:19.798  1014  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:19.798  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 22:02:19.808  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:19.808  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
,09-09 22:02:19.808  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
,09-09 22:02:19.808  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 22:02:19.808  6388  6388 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-09 22:02:19.818  1014  1124 D WifiP2pService: P2pDisablingState
,09-09 22:02:19.818  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 22:02:19.818  1014  1124 D WifiP2pService: p2p socket connection lost
,09-09 22:02:19.818  1014  1125 E WifiNative-wlan0: do suspend true
09-09 22:02:19.818  1014  1124 D WifiP2pService: P2pDisabledState
,09-09 22:02:19.818  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-09 22:02:19.818  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-09 22:02:19.828  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:19.828  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
09-09 22:02:19.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.828  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:19.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.828  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:19.828  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.828  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 22:02:19.828  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:19.828  1014  1044 D WifiDisplayController: disconnect
09-09 22:02:19.828  1014  1044 D WifiDisplayController: updateConnection
09-09 22:02:19.828  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:19.828  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
09-09 22:02:19.828  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:19.828  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:19.828  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:19.828  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:19.828  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:19.828  1014  1371 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:19.828  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:19.848  6388  6388 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,09-09 22:02:19.848  6388  6388 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 22:02:19.848  6388  6388 D UserAnalysis: Create SecureDbHelper,
,09-09 22:02:19.848   281   939 D EnterpriseController: uids 1000
,09-09 22:02:19.848   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:19.848   281   939 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-09 22:02:19.848   281   943 D CommandListener: Clearing all IP addresses on wlan0
09-09 22:02:19.848  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 22:02:19.848  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-09 22:02:19.848  1178  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-09 22:02:19.848  1014  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 22:02:19.858  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-09 22:02:19.858  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:19.858  1014  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-09 22:02:19.858  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:19.858  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-09 22:02:19.858  1450  1450 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-09 22:02:19.858  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-09 22:02:19.858  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-09 22:02:19.858  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 22:02:19.858  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-09 22:02:19.858  1014  1128 D Tethering: MasterInitialState.processMessage what=3
09-09 22:02:19.858  6388  6388 D IntelligenceServiceApplication: onCreate()
,09-09 22:02:19.858  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 22:02:19.858  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 22:02:19.858  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:19.858  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.858  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 22:02:19.858  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 22:02:19.868  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 22:02:19.868  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 22:02:19.868  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: updateDataNetType()
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 22:02:19.868  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 22:02:19.868  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 22:02:19.868  2099  2099 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-09 22:02:19.868  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.868  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.868  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.868  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 22:02:19.868  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.868  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:19.868  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:19.868  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:19.868  6388  6388 D IntelligenceServiceApplication: no applications having user consent for prediction
09-09 22:02:19.868  3839  6307 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-09 22:02:19.868  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.868  1014  1122 V NetworkStats: performPollLocked() took 10ms
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:19.868  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:19.878  2633  2808 W bt-l2cap: HC lib lpm enable=0 return 0
09-09 22:02:19.878  2633  2901 I bt_userial_mct: exiting userial_read_thread
09-09 22:02:19.878  2633  2901 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
,09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:19.878  1014  1492 I ActivityManager: Killing 5056:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-09 22:02:19.878  2633  2808 W bt-btif : ag scb idx 1 not allocated
,09-09 22:02:19.878  2633  2720 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-09 22:02:19.878  2633  2808 W bt-btif : ag scb idx 2 not allocated
09-09 22:02:19.878  2633  2808 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 22:02:19.878  2633  2811 I bt_vendor: hw_epilog_process
09-09 22:02:19.878  2633  2720 D bt_userial_mct: userial_close
09-09 22:02:19.878  2633  2720 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
09-09 22:02:19.878  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:19.878  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:19.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:19.888  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-09 22:02:19.888  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:19.888  6388  6388 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-09 22:02:19.888  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:19.888  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:19.888  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:19.888  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:19.888  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.888  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.888  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:19.888  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:19.898  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:19.898  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 22:02:19.898  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-09 22:02:19.898  6388  6388 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-09 22:02:19.898  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:19.898  1178  1178 D HotspotTile: onReceive : 0, 0
09-09 22:02:19.898  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:19.898  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.898  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:19.898  1014  1492 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-09 22:02:19.898  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.898  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:19.898  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:19.898  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.898  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.898  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:19.898  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:19.898  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:19.908  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:19.908  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:19.908  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:19.908  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:19.918  6414  6414 E Zygote  : MountEmulatedStorage()
,09-09 22:02:19.918  6414  6414 E Zygote  : v2
,09-09 22:02:19.918  6414  6414 I libpersona: KNOX_SDCARD checking this for 10107
09-09 22:02:19.918  6414  6414 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:19.918  6414  6414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:19.918  1014  1492 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6414 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
,09-09 22:02:19.928  6414  6414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:19.928  6414  6414 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:19.948  6414  6414 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:19.948  6414  6414 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:19.978  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:19.998  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:19.998  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:19.998  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.008  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.008  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.008  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.018  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.018  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.018  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.018  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.018  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.018  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-09 22:02:20.018  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.018  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.018  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.028  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.028  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.028  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.028  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.028  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.028  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.028  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.028  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.038  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.038  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.038  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.038  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.038  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.038  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-09 22:02:20.038  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-09 22:02:20.048  6249  6249 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 22:02:20.108  2633  2720 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 22:02:20.108  2633  2720 I bt_vendor: bluetooth satus is on
09-09 22:02:20.108  2633  2720 I bt_vendor: bt-vendor : resetting BT status
09-09 22:02:20.108  2633  2720 I bt_vendor: Starting hciattach daemon
09-09 22:02:20.108  2633  2720 I bt_vendor: try to set false
09-09 22:02:20.108  2633  2720 I bt_vendor: Starting hciattach daemon
,09-09 22:02:20.108  2633  2720 I bt_vendor: try to set false
,09-09 22:02:20.108  2099  2099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 22:02:20.108  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:20.108  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:20.108  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:20.108  2633  2720 I bt_vendor: cleanup
,09-09 22:02:20.108  2633  2808 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-09 22:02:20.108  2633  2720 I GKI_LINUX: GKI_exit_task 0 done
,09-09 22:02:20.108  2633  2720 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-09 22:02:20.118  2633  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 22:02:20.118  2633  2716 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:20.118  2633  2716 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 22:02:20.118  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:20.118  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 22:02:20.118  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 22:02:20.118  1014  2992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:20.118  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.118  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.118  1014  2992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.118  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.118  2633  2633 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 22:02:20.118  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:20.118  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:20.118  2633  2633 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 22:02:20.118  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:20.118  2633  2633 D BtGatt.GattService: stop()
09-09 22:02:20.118  2633  2633 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 22:02:20.118  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:20.118  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.118  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.118  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.118  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.118  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:20.118  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:20.118  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:20.128  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:20.128  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:20.128  2633  2633 D HeadsetService: Received stop request...Stopping profile...
,09-09 22:02:20.128  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.128  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.128  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.128  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.128  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 22:02:20.128  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:20.128  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:20.128  2099  2099 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 22:02:20.128  2099  2099 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 22:02:20.128  2099  2099 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 22:02:20.128  2099  2099 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:20.128  2099  2099 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 22:02:20.128  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:20.138  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:20.138  1014  1128 D Tethering: InitialState.processMessage what=4
,09-09 22:02:20.138  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-09 22:02:20.138  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-09 22:02:20.138  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:20.138  1014  1128 E Tethering: No numeric data
09-09 22:02:20.138  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.138  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:20.138  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.138  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.138  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.138  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.138  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:20.138  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:20.138  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:20.138  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:20.138  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-09 22:02:20.138  1327  1327 D HeadsetProfile: Bluetooth service disconnected
,09-09 22:02:20.138  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:20.148  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:20.148  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:20.148  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:20.148  1014  1128 D Tethering: clearTetheredNotification()
,09-09 22:02:20.148  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:20.148  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:20.148  1014  2992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:20.148  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:20.148  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-09 22:02:20.148  1014  1122 V NetworkStats: performPollLocked() took 6ms
,09-09 22:02:20.148  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.148  1014  2992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.148  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.158  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:20.158  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:20.158  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:20.158  1014  3033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:20.158  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 22:02:20.158  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:20.158  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:20.158  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.158  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.158  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.158  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.158  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:20.158  2633  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService,
,09-09 22:02:20.158  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:20.158  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.158  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.158  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.158  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.158  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:20.158  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:20.168  1014  1371 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:20.168  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.168  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.168  1014  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.168  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:20.168  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:20.168  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:20.168  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:20.168  2633  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 22:02:20.168  2633  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:20.168  2633  2716 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 22:02:20.168  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 22:02:20.168  2633  2633 D A2dpService: Received stop request...Stopping profile...
09-09 22:02:20.168  2633  2732 D A2dpStateMachine: Exit Disconnected: -1
,09-09 22:02:20.178  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:20.178  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:20.178  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-09 22:02:20.178  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 22:02:20.178  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:20.178  2633  2633 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 22:02:20.178  2856  2856 D BluetoothA2dp: Proxy object disconnected
,09-09 22:02:20.178  1327  1327 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:20.178  1327  1327 D A2dpProfile: Bluetooth service disconnected
,09-09 22:02:20.188  2633  2633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 22:02:20.188  2633  2633 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-09 22:02:20.188  2633  2633 D HidService: Received stop request...Stopping profile...
09-09 22:02:20.188  1014  2991 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-09 22:02:20.188  2633  2633 D HidService: Stopping Bluetooth HidService
09-09 22:02:20.188  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-09 22:02:20.188  2633  2633 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 22:02:20.188  2633  2633 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 22:02:20.188  2633  2633 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-09 22:02:20.188  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.188  1014  2991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:20.188  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-09 22:02:20.188  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65,
,09-09 22:02:20.188   272   272 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7b6b7c8
09-09 22:02:20.188   272   272 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,09-09 22:02:20.188   272   272 I rmt_storage: wakelock acquired: 1, error no: 42
09-09 22:02:20.188   272   295 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1212762824)
,09-09 22:02:20.198  1910  1910 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 22:02:20.198  1910  1910 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 22:02:20.208  2633  2633 D HealthService: Received stop request...Stopping profile...
09-09 22:02:20.208  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:20.208  1327  1327 D BluetoothInputDevice: Proxy object disconnected
09-09 22:02:20.208  1327  1327 D HidProfile: Bluetooth service disconnected
,09-09 22:02:20.208  2633  2633 D PanService: Received stop request...Stopping profile...
09-09 22:02:20.208  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:20.208  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:20.208  2633  2633 D BluetoothMapService: Received stop request...Stopping profile...
,09-09 22:02:20.218  1327  1327 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:20.218  1327  1327 D PanProfile: Bluetooth service disconnected
,09-09 22:02:20.218  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:20.218  2633  2633 D SapService: Received stop request...Stopping profile...
,09-09 22:02:20.228  1327  1327 D BluetoothMap: Proxy object disconnected
09-09 22:02:20.228  1327  1327 D MapProfile: Bluetooth service disconnected
09-09 22:02:20.228  2633  2633 D SapService: Stopping Bluetooth SapService
09-09 22:02:20.228  2633  2633 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:20.228  1327  1327 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-09 22:02:20.228  1327  1327 D SapProfile: Bluetooth service disconnected
,09-09 22:02:20.228  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 22:02:20.228  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:20.228  2633  2633 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 22:02:20.228  2633  2633 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:20.228  2633  2633 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-09 22:02:20.228  2633  2733 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 22:02:20.228  2633  2633 I GKI_LINUX: GKI_exit_task 2 done
09-09 22:02:20.228  2633  2633 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 22:02:20.238  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
09-09 22:02:20.238  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true,
09-09 22:02:20.238  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.238  2633  2633 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.238  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 22:02:20.238  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.238  2633  2633 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
09-09 22:02:20.238  2633  2633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 22:02:20.238  2633  2633 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-09 22:02:20.238  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 22:02:20.238  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.238  2633  2633 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:20.238  2633  2633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 22:02:20.238  2633  2633 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 22:02:20.238  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-09 22:02:20.238  2633  2633 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 22:02:20.238  2633  2633 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-09 22:02:20.238  2633  2633 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-09 22:02:20.238  2633  2633 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 22:02:20.238  2633  2633 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-09 22:02:20.248  2633  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-09 22:02:20.248  2633  2716 D BluetoothAdapterProperties: Setting state to 10
09-09 22:02:20.248  2633  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-09 22:02:20.248  2633  2716 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:20.248  2633  2716 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 22:02:20.248  1327  1338 D BluetoothMap: onBluetoothStateChange: up=false
,09-09 22:02:20.248  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.248  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.248  2633  2716 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:20.248  2633  2716 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 22:02:20.248  2633  2716 I BluetoothAdapterState: Entering OffState
,09-09 22:02:20.258   272   295 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-09 22:02:20.258   272   295 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-09 22:02:20.258   272   295 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1212762824) wakelock released: 1, error no: 0
09-09 22:02:20.258   272   295 I rmt_storage: 
,09-09 22:02:20.268   272   272 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7b6b7c8
,09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=254 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=244 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=192 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  1014  1027 I ActivityManager: Killing 5499:com.google.android.partnersetup/u0a15 (adj 15): empty #31
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.k.c(PG:583)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  6414  6414 D StrictMode: StrictMode policy violation; ~duration=162 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.io.File.exists(File.java:363)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:20.268  6414  6414 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:20.268  1430  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.268  1430  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.268  2856  2929 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.268  2856  2929 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.278  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-09 22:02:20.278  1438  1449 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.278  1438  1449 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.278  2633  2651 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:20.278  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-09 22:02:20.288  1014  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:20.288  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:20.288  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.288  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.288  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:20.288  3679  3679 I Hs20UtilService: Starting #8
09-09 22:02:20.288  3679  3696 I Hs20UtilService: Message received 5007
09-09 22:02:20.288  1327  1339 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:20.288  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:20.288  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:20.288  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:20.288  2099  2099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-09 22:02:20.298  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 22:02:20.298  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:20.298  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:20.298  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:20.298  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 22:02:20.298  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.298  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:20.298  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:20.298  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.298  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:20.298  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 22:02:20.308  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:20.308  1178  1891 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.308  1178  1891 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.308  2856  2875 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:20.308  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 22:02:20.308  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:20.318  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:20.318  1450  3241 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.318  1450  3241 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.318  1327  1339 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.318  1327  1339 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.318  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:20.318  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:20.318  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:20.318  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-09 22:02:20.318  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-09 22:02:20.318  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.318  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.318  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.318  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.338  6455  6455 E Zygote  : MountEmulatedStorage()
09-09 22:02:20.338  6455  6455 I libpersona: KNOX_SDCARD checking this for 10068
09-09 22:02:20.338  6455  6455 E Zygote  : v2
09-09 22:02:20.338  6455  6455 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:20.338  6455  6455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:20.338  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6455 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:20.338  6455  6455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:20.338  6455  6455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:20.348  2633  2647 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.348  2633  2647 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.348  1910  1941 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:20.348  1910  1941 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:20.358  6249  6259 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:20.358  6249  6259 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:20.358  6249  6259 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 22:02:20.358  6249  6259 D BluetoothLeAdvertiser: Exit stop advertising
09-09 22:02:20.358  6249  6259 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 22:02:20.358  6249  6259 D BluetoothLeScanner: Exiting stopAllScan
09-09 22:02:20.358  6414  6446 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-09 22:02:20.358  1327  1338 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 22:02:20.358  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:20.358  6455  6455 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:20.358  6455  6455 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:20.368  1327  1339 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 22:02:20.368  1327  6453 D Bluetoothsap: onBluetoothStateChange: up=false
09-09 22:02:20.368  1327  6453 D Bluetoothsap: Unbinding service...
,09-09 22:02:20.368  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 22:02:20.378  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 22:02:20.378  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.378  1014  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 22:02:20.378  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:20.378  6455  6455 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 22:02:20.378  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-09 22:02:20.388  2633  2720 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 22:02:20.388  2633  2633 I GKI_LINUX: GKI_exit_task 1 done
09-09 22:02:20.388  2633  2633 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-09 22:02:20.388  2633  2633 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 22:02:20.388  2633  2633 I art     : System.exit called, status: 0
09-09 22:02:20.388  2633  2633 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 22:02:20.388  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-09 22:02:20.398  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:20.398  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:20.398  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 22:02:20.408  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.408  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-09 22:02:20.418  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.418  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.418  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:20.418  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:20.418  1178  1178 D BluetoothTile:  getBluetoothState : 10
09-09 22:02:20.418  1178  1738 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.418  1178  1738 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.418  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-09 22:02:20.418  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.428  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.428  1014  3233 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:20.428  1014  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:20.428  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:20.428  6455  6455 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:20.438  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:20.438  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-09 22:02:20.438  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-09 22:02:20.438  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 22:02:20.438  1789  1789 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-09 22:02:20.438  1910  2123 D BluetoothAdapter: 1011791344: getState() :  mService = null. Returning STATE_OFF
09-09 22:02:20.438  1910  2123 D BluetoothAdapter: 1011791344: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:20.438  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.438  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.438  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-09 22:02:20.438  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.438  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.438  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.438  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.458  6471  6471 E Zygote  : MountEmulatedStorage()
09-09 22:02:20.458  6471  6471 E Zygote  : v2
09-09 22:02:20.458  6471  6471 I libpersona: KNOX_SDCARD checking this for 10069
09-09 22:02:20.458  6471  6471 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:20.458  6471  6471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:20.458  6471  6471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:20.458  6471  6471 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:20.468  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6471 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
09-09 22:02:20.468  1014  1027 I ActivityManager: Killing 5590:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-09 22:02:20.468  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.468  1014  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:20.468  1014  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:20.468  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-09 22:02:20.468  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:20.478  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:20.478  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:20.478  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.478  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.478  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:20.478  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:20.478  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:20.478  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 22:02:20.478  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:20.478  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:20.478  1178  1178 D HotspotTile: onReceive : 1, 0
,09-09 22:02:20.488  1910  2123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:20.488  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:20.488  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:20.488  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:20.488  6471  6471 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:20.488  6471  6471 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:20.508  1014  1492 I ActivityManager: Process com.android.bluetooth (pid 2633)(adj 0) has died(39,1100)
,09-09 22:02:20.518  6471  6471 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:20.518  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.518  1014  1472 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:20.518  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-09 22:02:20.528  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-09 22:02:20.528  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.528  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.528  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.528  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.538  6490  6490 E Zygote  : MountEmulatedStorage()
09-09 22:02:20.538  1014  1472 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6490 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-09 22:02:20.538  6490  6490 E Zygote  : v2
09-09 22:02:20.538  6490  6490 I libpersona: KNOX_SDCARD checking this for 10104
09-09 22:02:20.538  6490  6490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:20.538  6490  6490 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:20.538  1014  1472 I ActivityManager: Killing 5826:com.sec.pcw.device/1000 (adj 15): empty #31
09-09 22:02:20.538  6490  6490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:20.548  6490  6490 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:20.558  6490  6490 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:20.568  6490  6490 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:20.578  6490  6490 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 22:02:20.738  6490  6513 I Babel   : MmsConfig: mnc/mcc: 0/0
09-09 22:02:20.738  6490  6513 I Babel   : MmsConfig.loadMmsSettings
09-09 22:02:20.738  6490  6513 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-09 22:02:20.738  6490  6513 I Babel   : MmsConfig.loadFromDatabase
,09-09 22:02:20.748  6490  6513 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-09 22:02:20.748  6490  6513 I Babel   : MmsConfig.loadFromResources
,09-09 22:02:20.758  6490  6513 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 22:02:20.758  6490  6513 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-09 22:02:20.768  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-09 22:02:20.768  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.768  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.768  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:20.768  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 22:02:20.778  6490  6490 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:20.818  6490  6490 I Babel_StickerModule: App launched.
,09-09 22:02:20.818  1014  3033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:20.818  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:20.828  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.828  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.828  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:20.828  3679  3679 I Hs20UtilService: Starting #9
,09-09 22:02:20.828  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:20.828  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:20.828  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:20.828  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:20.828  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:20.828  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-09 22:02:20.828  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:20.838  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:20.848  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:20.848  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:20.848  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.848  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.848  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:20.848  1014  1322 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-09 22:02:20.848  3679  3679 I Hs20UtilService: Starting #10
,09-09 22:02:20.848  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:20.848  1014  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.848  1014  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.848   286   703 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-09 22:02:20.848   286   703 W QCamera2Factory: getCameraInfo: X
,09-09 22:02:20.848  1014  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:20.848  1014  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:20.858   286   712 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-09 22:02:20.858   286   712 W QCamera2Factory: getCameraInfo: X
,09-09 22:02:20.868  6515  6515 E Zygote  : MountEmulatedStorage()
09-09 22:02:20.868  6515  6515 E Zygote  : v2
09-09 22:02:20.868  6515  6515 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:20.868  6515  6515 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:20.868  6515  6515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:20.868  1014  1322 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6515 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-09 22:02:20.868  6490  6490 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 22:02:20.868  6490  6490 W AudioCapabilities: Unsupported mime audio/evrc
,09-09 22:02:20.878  6490  6490 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 22:02:20.878  6515  6515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:20.878  6515  6515 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:20.888  6490  6490 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-09 22:02:20.888  6490  6490 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-09 22:02:20.888  6490  6490 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-09 22:02:20.898  6490  6490 W AudioCapabilities: Unsupported mime audio/x-ima
,09-09 22:02:20.898  6490  6490 W AudioCapabilities: Unsupported mime audio/qcelp
,09-09 22:02:20.898  6515  6515 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:20.898  6490  6490 W AudioCapabilities: Unsupported mime audio/evrc
09-09 22:02:20.898  6515  6515 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:20.908  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:20.908  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-09 22:02:20.908  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:20.918  6490  6490 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 22:02:20.918  6490  6490 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 22:02:20.918  6490  6490 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-09 22:02:20.928  6490  6490 W VideoCapabilities: Unsupported mime video/wvc1
,09-09 22:02:20.928  6490  6490 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-09 22:02:20.928  6490  6490 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-09 22:02:20.928  6490  6490 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-09 22:02:20.928  6490  6490 W VideoCapabilities: Unsupported mime video/mp43
,09-09 22:02:20.938  6490  6490 W VideoCapabilities: Unsupported mime video/sorenson
,09-09 22:02:20.938  6490  6490 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-09 22:02:20.938  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:20.948  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:20.948  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:20.948  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:20.948  1014  1027 I ActivityManager: Killing 5137:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-09 22:02:20.958  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.958  1014  3233 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.958  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.958  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.958  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.958  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.958  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.958  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.958  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.968  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.968  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:20.968  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-09 22:02:20.968  6490  6490 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 22:02:20.968  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.968  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.968  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.978  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.978  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:20.978  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.978  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.978  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.978  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.988  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:20.988  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:20.988  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.988  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.988  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.988  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.998  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.998  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.998  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:20.998  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:20.998  1014  1558 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-09 22:02:20.998  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-09 22:02:20.998  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:21.008  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:21.008  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-09 22:02:21.008  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.008  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.008  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:21.008  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.008  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.008  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:21.018  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.018  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:21.018  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-09 22:02:21.018  1014  2992 I ActivityManager: Killing 5844:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-09 22:02:21.028  1014  2992 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-09 22:02:21.028  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.028  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.028  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.028  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.038  6532  6532 E Zygote  : MountEmulatedStorage()
,09-09 22:02:21.038  6532  6532 E Zygote  : v2
09-09 22:02:21.038  6532  6532 I libpersona: KNOX_SDCARD checking this for 1000
,09-09 22:02:21.038  6532  6532 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.038  6532  6532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-09 22:02:21.038  1014  2992 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 22:02:21.038  6532  6532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.038  6532  6532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.058  1014  1041 D Tethering: interfaceRemoved wlan0
09-09 22:02:21.058  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 22:02:21.058  6532  6532 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.058  6532  6532 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.078  6532  6532 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-09 22:02:21.078  6532  6532 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 22:02:21.078  6532  6532 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 22:02:21.098  6532  6532 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-09 22:02:21.098  6532  6532 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-09 22:02:21.098  6532  6532 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-09 22:02:21.098  6532  6532 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:21.098  1014  2992 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-09 22:02:21.098  1014  2992 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-09 22:02:21.098  1014  2992 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-09 22:02:21.098  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.098  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.098  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.098  1014  2992 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.098  6532  6547 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-09 22:02:21.108  1014  2992 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6549 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:21.108  6549  6549 E Zygote  : MountEmulatedStorage()
09-09 22:02:21.108  6549  6549 E Zygote  : v2
09-09 22:02:21.108  6549  6549 I libpersona: KNOX_SDCARD checking this for 10111
09-09 22:02:21.108  6549  6549 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.118  1014  2992 I ActivityManager: Killing 5524:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-09 22:02:21.118  6549  6549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.118  6549  6549 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.118  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
09-09 22:02:21.118  6549  6549 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.118  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.118  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.118  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.118  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.138  6549  6549 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.138  6549  6549 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.138  6564  6564 E Zygote  : MountEmulatedStorage()
,09-09 22:02:21.138  6564  6564 E Zygote  : v2
09-09 22:02:21.138  6564  6564 I libpersona: KNOX_SDCARD checking this for 10009
09-09 22:02:21.138  6564  6564 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.138  6564  6564 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.138  6564  6564 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.148  6564  6564 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.148  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6564 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:21.148  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-09 22:02:21.148  1703  1703 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:21.158  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.158  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.158  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.158  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.168   320   320 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 22.279ms,
,09-09 22:02:21.178  6564  6564 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:21.178  6564  6564 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.178   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 17.016ms
,09-09 22:02:21.198   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 16.552ms
,09-09 22:02:21.208  6579  6579 E Zygote  : MountEmulatedStorage(),
09-09 22:02:21.208  6579  6579 E Zygote  : v2
,09-09 22:02:21.208  6579  6579 I libpersona: KNOX_SDCARD checking this for 10145
09-09 22:02:21.208  6579  6579 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:21.208  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6579 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-09 22:02:21.208  6579  6579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.218  1014  1041 D Tethering: interfaceRemoved p2p0,
09-09 22:02:21.218  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 22:02:21.218  6579  6579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.218  6579  6579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.228  1703  1703 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-09 22:02:21.228  1703  1703 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-09 22:02:21.228  1703  1703 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-09 22:02:21.228  1703  1703 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:21.228  1703  1703 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-09 22:02:21.238  1703  1703 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-09 22:02:21.238  1300  2438 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-09 22:02:21.238  1014  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-09 22:02:21.238  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.238  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.238  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.238  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.248  6579  6579 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.248  6579  6579 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.248  6594  6594 E Zygote  : MountEmulatedStorage()
09-09 22:02:21.248  6594  6594 E Zygote  : v2
09-09 22:02:21.248  6594  6594 I libpersona: KNOX_SDCARD checking this for 10081
09-09 22:02:21.248  6594  6594 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.248  6594  6594 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.258  6594  6594 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:21.258  1014  1492 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6594 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:21.258  6594  6594 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.268   291   291 E SMD     : DCD OFF,
,09-09 22:02:21.278  1703  1703 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-09 22:02:21.288  6579  6579 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 22:02:21.288  6579  6579 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 22:02:21.288  6594  6594 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:21.288  6579  6579 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-09 22:02:21.288  6594  6594 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:21.288  6579  6579 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:21.288  6579  6579 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 22:02:21.328  1014  3240 I ActivityManager: Killing 5860:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-09 22:02:21.338  3697  3697 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 22:02:21 GMT+02:00 2016
,09-09 22:02:21.338  1014  1472 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 22:02:21.338  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.338  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:21.338  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:21.338  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 22:02:21.348  3697  3697 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 22:02:21.348  6549  6549 I MusicStore: Database version: 108
,09-09 22:02:21.348  1014  2991 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-09 22:02:21.358  1014  2991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.358  1014  2991 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.358  1014  2991 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.358  1014  2991 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.358  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.358  3697  3697 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 22:02:21.358  3697  3697 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 22:02:21.368  6617  6617 E Zygote  : MountEmulatedStorage(),
09-09 22:02:21.368  6617  6617 I libpersona: KNOX_SDCARD checking this for 10034
09-09 22:02:21.368  6617  6617 E Zygote  : v2
09-09 22:02:21.368  6617  6617 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:21.368  6617  6617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.368  6617  6617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:21.368  1014  2991 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6617 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-09 22:02:21.368  6617  6617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.378  3697  3697 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 22:02:21.378  3697  6616 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 22:02:21.378  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 22:02:21.378  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 22:02:21.388  3697  6616 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-09 22:02:21.388  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.388  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:21.388  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:21.388  3697  6616 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-09 22:02:21.388  3697  6616 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-09 22:02:21.388  6617  6617 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.388  6617  6617 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.398  3697  3697 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
09-09 22:02:21.398  1014  1558 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.438  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 22:02:21.438  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.438  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.438  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.438  6617  6617 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-09 22:02:21.438  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.448  1014  2992 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.448  6639  6639 E Zygote  : MountEmulatedStorage()
09-09 22:02:21.448  1014  1472 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6639 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:21.448  6639  6639 E Zygote  : v2
09-09 22:02:21.448  6639  6639 I libpersona: KNOX_SDCARD checking this for 10113
09-09 22:02:21.448  6639  6639 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.448  6639  6639 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.458  1014  1472 I ActivityManager: Killing 5558:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-09 22:02:21.458  6639  6639 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.458  6639  6639 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.478  3243  6651 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-09 22:02:21.478  1014  2991 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.478  3243  6651 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-09 22:02:21.478  6639  6639 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.478  6639  6639 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.488  3243  6651 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-09 22:02:21.488  3243  6651 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-09 22:02:21.488  6549  6549 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 22:02:21.488  3243  6651 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-09 22:02:21.488  6549  6549 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 22:02:21.498  5877  5877 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-09 22:02:21.498  1014  1557 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-09 22:02:21.498  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.498  6075  6075 I SA      : [DM] init START
09-09 22:02:21.498  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.498  1014  1557 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-09 22:02:21.498  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-09 22:02:21.508  6075  6075 I SA      : [DM] This device is not a Vodafone
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-09 22:02:21.518  6075  6075 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-09 22:02:21.528  6075  6075 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-09 22:02:21.528  6075  6075 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-09 22:02:21.528  5877  6655 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-09 22:02:21.528  6075  6075 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-09 22:02:21.528  6075  6075 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-09 22:02:21.528  6075  6075 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-09 22:02:21.528  6075  6075 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-09 22:02:21.538  6549  6549 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-09 22:02:21.538  6075  6075 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-09 22:02:21.548  6075  6075 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-09 22:02:21.548  6075  6075 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-09 22:02:21.558  6075  6075 I SA      : [SCU] isHaveSA() - false
09-09 22:02:21.558  6075  6075 I SA      : support phone number id : false
09-09 22:02:21.558  6075  6075 I SA      : [DM] Supports Ref Jpn : true
,09-09 22:02:21.558  6075  6075 I SA      : [DM] init END
,09-09 22:02:21.558  5963  5985 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
09-09 22:02:21.558  6075  6075 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-09 22:02:21.558  1014  1557 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.558  6075  6075 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-09 22:02:21.558  6075  6075 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-09 22:02:21.568  6075  6075 I SA      : [SLFUCHKMGR] constructor called
,09-09 22:02:21.578  5963  5988 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-09 22:02:21.578  5963  5988 D BadgeProvider: sendNotify, [notify] : null
09-09 22:02:21.578  5963  5988 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-09 22:02:21.578  5963  5988 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 22:02:21.578  5963  5988 D BadgeProvider: update, [UpdateCount] : 1
,09-09 22:02:21.578  1477  1477 D Launcher.Model: reloadBadges entered.
,09-09 22:02:21.578  6075  6075 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-09 22:02:21.578  6075  6075 I SA      : [OR] == isSIMCardReady false ==
,09-09 22:02:21.578  6075  6075 I SA      : [SCU] == networkStateCheck == false
09-09 22:02:21.578  6075  6075 I SA      : [OR] onReceive END
,09-09 22:02:21.588  1230  1230 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:21.588  1014  1472 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.608  1014  1472 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.618  6549  6549 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-09 22:02:21.618  6549  6549 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d14eb69: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-09 22:02:21.618  6549  6549 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 22:02:21.618  6549  6549 D AndroidMusic: GMSCore installation verified
,09-09 22:02:21.628  1014  3033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:21.628  1014  3239 D RCPManagerService: exchangeData() failure , invalid userId
,09-09 22:02:21.628  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-09 22:02:21.638  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:21.638  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:21.638  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:21.648  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:21.648  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:21.648  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:21.648  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:21.648  1014  3240 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-09 22:02:21.648  1014  3240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.648  1014  3240 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.648  1014  3240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.648  1014  3240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.668  6665  6665 E Zygote  : MountEmulatedStorage(),
09-09 22:02:21.668  1014  3240 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6665 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 22:02:21.668  6665  6665 E Zygote  : v2
,09-09 22:02:21.668  6665  6665 I libpersona: KNOX_SDCARD checking this for 10159
09-09 22:02:21.668  6665  6665 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:21.668  1014  3240 I ActivityManager: Killing 5903:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
09-09 22:02:21.668  6665  6665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.668  6665  6665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:21.668  6665  6665 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.678  6549  6549 I ConfigStore: Config Database version: 1
,09-09 22:02:21.698  6665  6665 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.698  6665  6665 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.758  1014  1557 I ActivityManager: Killing 5976:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,09-09 22:02:21.758  1014  3033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:21.768  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-09 22:02:21.768  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:21.768  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:21.768  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:21.768   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 22:02:21.768   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.768  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 22:02:21.778  3839  3839 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 22:02:21.778  3839  4620 I iu.UploadsManager: num queued entries: 0
,09-09 22:02:21.778  3839  4620 I iu.UploadsManager: num updated entries: 0
,09-09 22:02:21.788  3839  4620 I iu.SyncManager: NEXT; no task
,09-09 22:02:21.788   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 22:02:21.788   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.788  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 22:02:21.788   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-09 22:02:21.788   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.788  1014  1371 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-09 22:02:21.788  1014  1371 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
09-09 22:02:21.788  1014  1371 W BroadcastQueue: android.os.TransactionTooLargeException
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-09 22:02:21.788  1014  1371 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 22:02:21.788  1014  1371 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 22:02:21.798  6549  6549 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-09 22:02:21.798  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.798  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:21.798  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.798  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:21.808  1014  1371 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6682 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
09-09 22:02:21.808  6682  6682 E Zygote  : MountEmulatedStorage(),
09-09 22:02:21.808  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-09 22:02:21.808  6682  6682 E Zygote  : v2
09-09 22:02:21.808  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
09-09 22:02:21.808  6682  6682 I libpersona: KNOX_SDCARD checking this for 10010
09-09 22:02:21.818  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:21.808  6682  6682 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:21.818  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:21.818  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 22:02:21.818  6682  6682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:21.818  6682  6682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:21.818  6682  6682 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 22:02:21.828  1014  1038 W libprocessgroup: failed to open /acct/uid_10010/pid_5976/cgroup.procs: No such file or directory
,09-09 22:02:21.838   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 22:02:21.838   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.838  6639  6688 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 22:02:21.838   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 22:02:21.838   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.838  6639  6688 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 22:02:21.848  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:21.848  6682  6682 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:21.858   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 22:02:21.858   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.858  6639  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 22:02:21.858   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 22:02:21.858   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:21.858  6639  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 22:02:21.868  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 22:02:21.978  1014  1345 I art     : Explicit concurrent mark sweep GC freed 51954(2MB) AllocSpace objects, 7(160KB) LOS objects, 33% free, 27MB/41MB, paused 2.411ms total 150.136ms
,09-09 22:02:21.978  1014  3033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:21.978  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-09 22:02:21.978  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:21.988  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:21.988  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:22.018  1014  1322 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:22.028  1014  1026 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:22.038  1014  3239 I AudioService: getStreamVolume 3 index 0
,09-09 22:02:22.038  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-09 22:02:22.038  1014  1557 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-09 22:02:22.048  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.048  6549  6549 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-09 22:02:22.048  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.058  6549  6549 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-09 22:02:22.058  1014  3239 I ActivityManager: Killing 5808:com.android.mms/u0a46 (adj 15): empty #31
,09-09 22:02:22.088  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:22.088  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 22:02:22.088  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:22.088  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:22.088  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:22.088  1014  1492 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:22.088  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.098  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:22.098  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:22.098  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:22.098  1014  3233 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:22.098  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.098  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:22.098  1014  3233 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:22.098  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:22.108  1014  1371 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:22.118  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-09 22:02:22.118  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.118  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.118  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.118  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.128  6720  6720 E Zygote  : MountEmulatedStorage()
09-09 22:02:22.128  6720  6720 E Zygote  : v2
09-09 22:02:22.128  6720  6720 I libpersona: KNOX_SDCARD checking this for 10002
09-09 22:02:22.128  6720  6720 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:22.128  6720  6720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:22.138  6720  6720 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:22.138  6720  6720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:22.148  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6720 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:22.148  6720  6720 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:22.148  6720  6720 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:22.168  1014  1137 D CountryDetector: No listener is left
,09-09 22:02:22.178  1014  3239 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-09 22:02:22.178  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.178  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:22.178  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:22.178  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 22:02:22.178  6549  6549 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-09 22:02:22.188  1014  3033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:22.188  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 22:02:22.188  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:22.188  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:22.188  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:22.188  6639  6639 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-09 22:02:22.198  1014  3033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:22.198  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:22.198  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:22.198  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 22:02:22.218  6639  6639 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2131-2132)
,09-09 22:02:22.218  6639  6639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 22:02:22.228  6639  6639 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ebfc8c6}
,09-09 22:02:22.228  1014  1557 I ActivityManager: Killing 5996:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
09-09 22:02:22.228  6639  6639 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 22:02:22.228  6639  6639 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 22:02:22.228  1014  1557 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-09 22:02:22.228  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.228  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.228  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.228  1014  1557 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.238  6741  6741 E Zygote  : MountEmulatedStorage()
09-09 22:02:22.238  6741  6741 E Zygote  : v2
09-09 22:02:22.238  6741  6741 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:22.238  6741  6741 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:22.238  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:22.248  6639  6639 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 22:02:22.248  1014  1557 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
09-09 22:02:22.248  6639  6639 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 22:02:22.248  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:22.248  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-09 22:02:22.248  6639  6639 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 22:02:22.268  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:22.268  6639  6639 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
09-09 22:02:22.268  6639  6639 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
09-09 22:02:22.268  6741  6741 D ActivityThread: Added TimaKeyStore provider
09-09 22:02:22.268  6639  6639 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-09 22:02:22.278  6639  6639 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 22:02:22.278  6639  6639 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 22:02:22.278  6639  6639 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 22:02:22.278  6639  6639 I Adreno-EGL: Local Branch: 
09-09 22:02:22.278  6639  6639 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 22:02:22.278  6639  6639 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 22:02:22.278  6639  6639 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 22:02:22.308  6741  6741 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-09 22:02:22.328  6639  6767 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 22:02:22.338  6639  6639 I NSApplication: Starting up...
,09-09 22:02:22.348  1014  1472 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-09 22:02:22.348  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.348  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.348  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.348  1014  1472 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.368  6772  6772 E Zygote  : MountEmulatedStorage(),
,09-09 22:02:22.368  6772  6772 E Zygote  : v2
09-09 22:02:22.368  6772  6772 I libpersona: KNOX_SDCARD checking this for 10120
09-09 22:02:22.368  6772  6772 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:22.368  6772  6772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:22.368  1014  1472 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6772 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:22.378  1014  1472 I ActivityManager: Killing 5928:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
09-09 22:02:22.378  1014  1472 I ActivityManager: Killing 6037:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32
,09-09 22:02:22.378  1014  1472 I ActivityManager: Killing 6017:com.wsomacp/u0a25 (adj 15): empty #33
,09-09 22:02:22.378  6772  6772 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:22.378  6772  6772 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 22:02:22.408  6772  6772 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:22.408  6772  6772 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:22.428  6772  6772 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 22:02:22.438  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-09 22:02:22.448  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-09 22:02:22.448  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:22.448  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-09 22:02:22.448  6741  6741 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-09 22:02:22.448  6741  6741 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-09 22:02:22.448  1014  3240 I ActivityManager: Killing 5888:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-09 22:02:22.618  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 22:02:22.628  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:22.628  1014  1027 D SecContentProvider2: mCursor = null
,09-09 22:02:22.628  1014  1027 D WifiService: setWifiEnabled: true pid=6249, uid=10155
09-09 22:02:22.628  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:22.628  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:22.628  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:22.628  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 22:02:22.628  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:22.628  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:22.628  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:22.628  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-09 22:02:22.628  1014  1027 D SettingsProvider: name = wifi_on
,09-09 22:02:22.628  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 22:02:22.758  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 22:02:22.758  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.758  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.758  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.758  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.778  6795  6795 E Zygote  : MountEmulatedStorage()
09-09 22:02:22.778  1014  1558 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6795 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 22:02:22.778  6795  6795 E Zygote  : v2
09-09 22:02:22.778  6795  6795 I libpersona: KNOX_SDCARD checking this for 10125
09-09 22:02:22.778  6795  6795 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:22.778  6795  6795 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:22.778  1014  1558 I ActivityManager: Killing 6110:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-09 22:02:22.778  6795  6795 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:22.788  6795  6795 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:22.798  6795  6795 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:22.798  6795  6795 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:22.818  6795  6795 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 22:02:22.818  6795  6795 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 22:02:22.818  6795  6795 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:22.838  6795  6795 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:22.838  6795  6795 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-09 22:02:22.838  6795  6795 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-09 22:02:22.838  1014  3239 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
09-09 22:02:22.838  1014  3239 I ActivityManager: Killing 6132:com.samsung.helphub/1000 (adj 15): empty #31
,09-09 22:02:22.848  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:22.848  1014  3233 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:22.848  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:22.848  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:22.848  1014  3233 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:22.848  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:22.858  1327  1327 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:22.858  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:22.858  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:22.858  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 22:02:22.868  1014  1492 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-09 22:02:22.868  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.868  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.868  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:22.868  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:22.878  6817  6817 E Zygote  : MountEmulatedStorage(),
09-09 22:02:22.878  6817  6817 E Zygote  : v2
09-09 22:02:22.878  6817  6817 I libpersona: KNOX_SDCARD checking this for 1002
09-09 22:02:22.878  6817  6817 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:22.878  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:22.878  1014  1492 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6817 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-09 22:02:22.888  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:22.888  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:22.898   320   320 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 728us total 22.158ms
,09-09 22:02:22.908  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-09 22:02:22.908  6817  6817 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:22.918   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.475ms
,09-09 22:02:22.928  6817  6817 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-09 22:02:22.928  6817  6817 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:22.938   320   320 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 609us total 16.805ms
,09-09 22:02:22.948  6817  6817 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding GattService
,09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding HeadsetService
09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding A2dpService
,09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding HidService
09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding HealthService
09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding PanService
09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding SapService
09-09 22:02:22.978  6817  6817 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-09 22:02:22.988  6817  6817 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-09 22:02:22.988  6817  6817 D BtSettings.ProfileConfig: Adding SapClientService
,09-09 22:02:22.988  6817  6817 D BtSettings.ProfileConfig: Adding HidDevService
09-09 22:02:22.988  6817  6817 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-09 22:02:22.988  1014  3233 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-09 22:02:22.988  1014  3233 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  3233 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:22.988  1014  3233 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  3233 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  3233 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  3233 D SettingsProvider: ret = -1
,09-09 22:02:22.988  1014  3033 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-09 22:02:22.988  1014  3033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  3033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  3033 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  3033 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  3033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  3033 D SettingsProvider: ret = -1,
09-09 22:02:22.988  1014  1371 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-09 22:02:22.988  1014  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 22:02:22.988  1014  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  1371 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  1371 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:22.988  1014  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  1371 D SettingsProvider: ret = -1
09-09 22:02:22.988  1014  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-09 22:02:22.988  1014  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  1137 D SettingsProvider: selectionArgs: false
,09-09 22:02:22.988  1014  1137 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  1137 D SettingsProvider: ret = -1
09-09 22:02:22.988  1014  1557 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-09 22:02:22.988  1014  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  1557 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  1557 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  1557 D SettingsProvider: ret = -1
09-09 22:02:22.988  1014  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-09 22:02:22.988  1014  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  1322 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  1322 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  1322 D SettingsProvider: ret = -1
09-09 22:02:22.988  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-09 22:02:22.988  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.988  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.988  1014  1558 D SettingsProvider: selectionArgs: false
09-09 22:02:22.988  1014  1558 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.988  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.988  1014  1558 D SettingsProvider: ret = -1
,09-09 22:02:22.988  1014  2992 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-09 22:02:22.988  1014  2992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 22:02:22.988  1014  2992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.998  1014  2992 D SettingsProvider: selectionArgs: false
09-09 22:02:22.998  1014  2992 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.998  1014  2992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:22.998  1014  2992 D SettingsProvider: ret = -1
,09-09 22:02:22.998  1014  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:22.998  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.998  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.998  1014  1345 D SettingsProvider: selectionArgs: false
09-09 22:02:22.998  1014  1345 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.998  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.998  1014  1345 D SettingsProvider: ret = -1
,09-09 22:02:22.998  1014  3239 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:22.998  1014  3239 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.998  1014  3239 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:22.998  1014  3239 D SettingsProvider: selectionArgs: false
09-09 22:02:22.998  1014  3239 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.998  1014  3239 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.998  1014  3239 D SettingsProvider: ret = -1
,09-09 22:02:22.998  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-09 22:02:22.998  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.998  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:22.998  1014  1492 D SettingsProvider: selectionArgs: false
09-09 22:02:22.998  1014  1492 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:22.998  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.998  1014  1492 D SettingsProvider: ret = -1
09-09 22:02:22.998  1014  2991 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-09 22:02:22.998  1014  2991 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:22.998  1014  2991 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:22.998  1014  2991 D SettingsProvider: selectionArgs: false
09-09 22:02:22.998  1014  2991 D SettingsProvider: selectionArgs: 1002
09-09 22:02:22.998  1014  2991 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:22.998  1014  2991 D SettingsProvider: ret = -1
,09-09 22:02:23.008  1014  1026 I ActivityManager: Killing 5479:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
,09-09 22:02:23.008  1014  1041 D Tethering: interfaceAdded wlan0
,09-09 22:02:23.008  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.008  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.008  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:23.018  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:23.018  1014  1371 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:23.018  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-09 22:02:23.018  1014  1128 E Tethering: No numeric data
,09-09 22:02:23.018   281   943 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 22:02:23.018   281   943 D SoftapController: Softap fwReload - Ok
09-09 22:02:23.018  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.018  1014  1041 D Tethering: interfaceAdded p2p0
09-09 22:02:23.018  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:23.018  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:23.018   281   943 D CommandListener: Setting iface cfg
09-09 22:02:23.018   281   943 D CommandListener: Trying to bring down wlan0
,09-09 22:02:23.018  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
09-09 22:02:23.028   281   943 D CommandListener: Clearing all IP addresses on wlan0
09-09 22:02:23.028  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 22:02:23.028  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:23.028  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:23.028  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 22:02:23.028  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 22:02:23.028  1014  1128 D Tethering: clearTetheredNotification()
09-09 22:02:23.028  1014  1128 D Tethering: InitialState.processMessage what=4
,09-09 22:02:23.038  1014  1128 E Tethering: No numeric data
,09-09 22:02:23.038  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.038  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:23.038  1910  6834 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-09 22:02:23.038  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:23.038  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:23.038  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 22:02:23.038  1178  1178 D HotspotTile: updateTetherState():false, false
09-09 22:02:23.038  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:23.038  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:23.038  1014  1128 D Tethering: clearTetheredNotification()
,09-09 22:02:23.038  1014  1371 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 22:02:23.038  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 22:02:23.038  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.048  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.048  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:23.048  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:23.048  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 22:02:23.048  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:23.048  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.048  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:23.058  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:23.058  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:23.058  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.058  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.058  1014  3033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:23.058  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:23.058  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.058  1014  1122 V NetworkStats: performPollLocked() took 8ms
,09-09 22:02:23.058  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.058  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.058  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.058  3679  3679 I Hs20UtilService: Starting #11
,09-09 22:02:23.068  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:23.068  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:23.068  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:23.068  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:23.068  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:23.068  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:23.068  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:23.078  1014  3239 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:23.078  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.078  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:23.078  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:23.078  6835  6835 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-09 22:02:23.078  6835  6835 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 22:02:23.078  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 22:02:23.088  1910  6834 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 22:02:23.098  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-09 22:02:23.098   383   383 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6835
09-09 22:02:23.098   383   383 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-09 22:02:23.098  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 22:02:23.098  6835  6835 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:23.098  6835  6835 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 22:02:23.098  6835  6835 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 22:02:23.098   383   383 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6835
09-09 22:02:23.098   383   383 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-09 22:02:23.128  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-09 22:02:23.128  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.128  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:23.128  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.128  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.128  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.138  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,09-09 22:02:23.128  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.138  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.138  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.138  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 22:02:23.138  1178  1178 D HotspotTile: onReceive : 2, 0
09-09 22:02:23.138  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.138  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:23.138  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:23.148  1014  1492 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:23.148  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:23.148  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.148  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.148  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.148  3679  3679 I Hs20UtilService: Starting #12
,09-09 22:02:23.148  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:23.148  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:23.148  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:23.148  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-09 22:02:23.148  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:23.248   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,09-09 22:02:23.258  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-09 22:02:23.318  6835  6835 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-09 22:02:23.318  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 22:02:23.328  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 22:02:23.328   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835,
09-09 22:02:23.328   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 22:02:23.328  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,09-09 22:02:23.328  6835  6835 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:23.328  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:23.338  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:23.338  6835  6835 E wpa_supplicant: SIM READ ERROR
09-09 22:02:23.338  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:23.338  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-09 22:02:23.338  6835  6835 E wpa_supplicant: SIM READ ERROR
09-09 22:02:23.338  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:23.338  6835  6835 I wpa_supplicant: wpa_default_ap_write_once,
09-09 22:02:23.338  6835  6835 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:23.338  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 22:02:23.338  6835  6835 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 22:02:23.338  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 22:02:23.338  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:23.338  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 22:02:23.338  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:23.338  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:23.338  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:23.438  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 22:02:23.718  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 22:02:23.718  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-09 22:02:23.728  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-09 22:02:23.728   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835
09-09 22:02:23.728   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-09 22:02:23.738  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 22:02:23.738  6835  6835 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:23.738  6835  6835 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-09 22:02:23.738  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-09 22:02:23.748  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-09 22:02:23.748   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6835
09-09 22:02:23.748   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-09 22:02:23.748  6835  6835 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-09 22:02:23.748  6835  6835 I wpa_supplicant: ssSupport state is = 1,
09-09 22:02:23.748  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:23.748  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:23.748  6835  6835 E wpa_supplicant: SIM READ ERROR
09-09 22:02:23.748  6835  6835 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:23.748  6835  6835 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:23.748  6835  6835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 22:02:23.748  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:23.748  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 22:02:23.748  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 22:02:23.758  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:23.758  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-09 22:02:23.758  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:23.798  6835  6835 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 22:02:23.798  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 22:02:23.888  6835  6835 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-09 22:02:23.888  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 22:02:23.888  6835  6835 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-09 22:02:23.898  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-09 22:02:23.898  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:23.898  6835  6835 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-09 22:02:23.898  6835  6835 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-09 22:02:23.908  6835  6835 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:23.908  6835  6835 E wpa_supplicant: SIM READ ERROR
09-09 22:02:23.908  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:23.928  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-09 22:02:23.938  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210],
09-09 22:02:23.938  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:23.938  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-09 22:02:23.938  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:23.938  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.938  1178  1178 D HotspotTile: onReceive : 3, 0
09-09 22:02:23.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.938  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:23.938  6835  6835 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 22:02:23.938  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.938  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 22:02:23.938  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-09 22:02:23.948  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:23.948  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:23.948  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.948  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:23.948  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:23.948  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:23.948  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:23.948  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:23.948  1014  3233 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:23.948  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:23.948  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:23.948  1014  3233 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:23.948  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:23.948  3679  3679 I Hs20UtilService: Starting #13
,09-09 22:02:23.948  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:23.958  1014  1125 E WifiConfigStore: Not a HS20,
,09-09 22:02:23.958  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 22:02:23.958  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 22:02:23.958  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:23.958  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:23.958  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:23.958  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:23.958  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 22:02:23.958  6835  6835 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 22:02:23.958  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:23.958  6835  6835 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:23.958  6835  6835 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:23.958  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 22:02:23.958  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 22:02:23.958  6835  6835 I wpa_supplicant: First Scan Start
09-09 22:02:23.958  6835  6835 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 22:02:23.968  6490  6490 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:23.968  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
,09-09 22:02:23.968  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 22:02:23.968  1014  1125 I WifiNative-HAL: startHal
09-09 22:02:23.968  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9cb6988c
09-09 22:02:23.968  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 22:02:23.978  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:23.978  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-09 22:02:23.978  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 22:02:23.978  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-09 22:02:23.978  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:23.978  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:23.978  1014  1125 E WifiNative-wlan0: invaild command id : 215
,09-09 22:02:23.978  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:23.978  1014  1149 I WifiNative-HAL: startHal
09-09 22:02:23.978  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dd1b9bc
09-09 22:02:23.978  1014  1149 I WifiNative-HAL: Could not start hal
09-09 22:02:23.978  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:23.978  1014  1149 E WifiScanningService: could not start HAL
09-09 22:02:23.978  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:23.978  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 22:02:23.978  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-09 22:02:23.978  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-09 22:02:23.988   281   943 D CommandListener: Setting iface cfg
09-09 22:02:23.988   281   943 D CommandListener: Trying to bring up p2p0
09-09 22:02:23.988  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:23.988  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 22:02:23.988  1014  1124 D WifiP2pService: P2pEnablingState
09-09 22:02:23.988  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 22:02:23.988  1014  1124 D WifiP2pService: P2p socket connection successful
09-09 22:02:23.988  1014  1124 D WifiP2pService: P2pEnabledState
09-09 22:02:23.988  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:23.988  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-09 22:02:23.988  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:23.988  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-09 22:02:23.988  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 22:02:23.988  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 22:02:23.988  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:23.988  1014  1044 D WifiDisplayController: disconnect
09-09 22:02:23.988  1014  1044 D WifiDisplayController: updateConnection
09-09 22:02:23.988  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:23.988  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:23.988  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-09 22:02:23.988  1014  1492 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:23.998  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:23.998  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:23.998  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:23.998  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:23.998  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:23.998  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:23.998  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 22:02:23.998  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 22:02:23.998  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,09-09 22:02:23.998  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-09 22:02:23.998  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 22:02:23.998  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:23.998  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:23.998  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  secondary type: null
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  wps: 0
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  grpcapab: 0
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  devcapab: 0
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  status: 3
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  wfdInfo: null
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-09 22:02:23.998  1014  1044 D WifiDisplayController:  SConnectInfo : null
09-09 22:02:23.998  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:24.008  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:24.008  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:24.008  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:24.008  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:24.008  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:24.008  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:24.008  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:24.008  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:24.008  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:24.008  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 22:02:24.008  6455  6455 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:24.018  6471  6471 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:24.038  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-09 22:02:24.038  1014  1124 D WifiP2pService: InactiveState
09-09 22:02:24.038  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 22:02:24.038  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:24.038  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:24.038  1014  1124 D WifiP2pService: InactiveState{ what=143376 },
09-09 22:02:24.038  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:24.268   291   291 E SMD     : DCD OFF,
,09-09 22:02:25.158  6835  6835 I wpa_supplicant: nl80211: Received scan results (33 BSSes),
,09-09 22:02:25.158  6835  6835 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:25.168  1014  6840 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-09 22:02:25.168  6835  6835 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-09 22:02:25.168  6835  6835 I wpa_supplicant: Trying to associate with  'G700'
,09-09 22:02:25.168  6835  6835 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,09-09 22:02:25.168  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-09 22:02:25.188  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:25.188  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.278  6835  6835 E wpa_supplicant: Cmd 35605 not handled
,09-09 22:02:25.278  6835  6835 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:25.278  6835  6835 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,09-09 22:02:25.278  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:25.278  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:25.278  6835  6835 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 22:02:25.278  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:25.278  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 22:02:25.278  6835  6835 I wpa_supplicant: Associated with F4.99.3E
09-09 22:02:25.278  6835  6835 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:25.278  6835  6835 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,09-09 22:02:25.278  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:25.278  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:25.278  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:25.278  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:25.278  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true,
09-09 22:02:25.278  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:25.278  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:25.278  1014  1128 E Tethering: No numeric data
,09-09 22:02:25.288  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 22:02:25.288  1014  1128 D Tethering: clearTetheredNotification()
,09-09 22:02:25.288  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:25.288  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
,09-09 22:02:25.288  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 22:02:25.288  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:25.288  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-09 22:02:25.288  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:25.288  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:25.288  1014  1122 V NetworkStats: performPollLocked() took 3ms
,09-09 22:02:25.288  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 22:02:25.288  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:25.288  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 22:02:25.288  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.298  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:25.298  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.298  6835  6835 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:25.298  6835  6835 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 22:02:25.298  6835  6835 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 22:02:25.298  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:25.298  6835  6835 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 22:02:25.298  6835  6835 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-09 22:02:25.298  6835  6835 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-09 22:02:25.308  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:25.308  6835  6835 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 22:02:25.308  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:25.308  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:25.308  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:25.308  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 22:02:25.308  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 22:02:25.308  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:25.308  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:25.308  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.308  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.308  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.308  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.318  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 22:02:25.318  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-09 22:02:25.318  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:25.318  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:25.318  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 22:02:25.318  1014  2991 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:25.318  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,09-09 22:02:25.318  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:25.318  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:25.318  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:25.328  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:25.328  3679  3679 I Hs20UtilService: Starting #14,
09-09 22:02:25.328  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:25.328  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:25.328  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:25.328  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:25.328  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:25.328  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:25.328  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:25.338   281   943 D CommandListener: Setting iface cfg
,09-09 22:02:25.338  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:25.348  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-09 22:02:25.348  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:25.348  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.358  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:25.358  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:25.358  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.358  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.358  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.358  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.358  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-09 22:02:25.358  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.358  1014  1125 E WifiNative-wlan0: do suspend false
,09-09 22:02:25.368  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-09 22:02:25.368  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:25.588  6846  6846 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:25.588  6846  6846 I dhcpcd  : version 5.5.6 starting
,09-09 22:02:25.598  6846  6846 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:25.628  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-09 22:02:25.628  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:25.628  1014  1027 D SecContentProvider2: mCursor = null
,09-09 22:02:25.638  1014  1027 D WifiService: setWifiEnabled: false pid=6249, uid=10155
09-09 22:02:25.638  1014  1027 D SettingsProvider: name = wifi_on
,09-09 22:02:25.648  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:25.658  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:25.668  6846  6846 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 22:02:25.668  6846  6846 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-09 22:02:25.678  6846  6846 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
,09-09 22:02:25.678  6846  6846 I dhcpcd  : bssid match
09-09 22:02:25.678  6846  6846 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 22:02:25.678  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 22:02:25.678  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:25.678   281   943 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:25.688  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-09 22:02:25.688  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:25.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-09 22:02:25.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.688  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.688  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:25.688  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:25.688  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-09 22:02:25.688  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:25.688   281   943 E Netd    : no such netId 503
09-09 22:02:25.688  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 22:02:25.688  1014  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-09 22:02:25.688  1014  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-09 22:02:25.688  1014  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-09 22:02:25.688  1014  6844 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:25.688  1014  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-09 22:02:25.688  1014  1127 D ConnectivityService: nai.networkMonitor.doQuit()
09-09 22:02:25.688  1014  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-09 22:02:25.688  1014  6844 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,09-09 22:02:25.698  1014  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost,
09-09 22:02:25.698  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:25.698  1014  1124 D WifiP2pService: InactiveState{ what=131204 }
,09-09 22:02:25.698  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:25.698  1014  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-09 22:02:25.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.698  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.698  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-09 22:02:25.698  1014  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:25.698  1014  1345 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:25.698  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:25.698  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-09 22:02:25.698  1014  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:25.698  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:25.698  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:25.698  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:25.698  3679  3679 I Hs20UtilService: Starting #15
,09-09 22:02:25.698  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:25.698  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-09 22:02:25.708  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:25.708  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:25.708  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:25.708  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:25.708  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: FAILED
09-09 22:02:25.708  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:25.708  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:25.708  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:25.708  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-09 22:02:25.708  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:25.708  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:25.708  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 22:02:25.718  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-09 22:02:25.718  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-09 22:02:25.718  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:25.718  1014  1044 D WifiDisplayController: disconnect
09-09 22:02:25.718  1014  1044 D WifiDisplayController: updateConnection
09-09 22:02:25.718  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:25.718  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:25.718  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 22:02:25.718  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:25.718  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:25.718  1014  3239 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 22:02:25.718  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:25.718  1014  1124 D WifiP2pService: P2pDisablingState
09-09 22:02:25.718  1014  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-09 22:02:25.718  1014  1124 D WifiP2pService: p2p socket connection lost
09-09 22:02:25.718  1014  1124 D WifiP2pService: P2pDisabledState
09-09 22:02:25.718  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:25.718  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-09 22:02:25.718  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:25.718  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:25.718  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-09 22:02:25.728  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 22:02:25.728  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:25.728  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:25.728  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:25.728  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:25.728  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:25.728  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:25.728  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:25.728  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-09 22:02:25.728  6455  6455 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:25.738  6471  6471 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:25.748  1014  1124 D WifiP2pService: P2pDisabledState{ what=143375 },
09-09 22:02:25.748  1014  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-09 22:02:25.758   281   943 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:25.758  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:25.758  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:25.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.758  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.758  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-09 22:02:25.768  6835  6835 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-09 22:02:25.768  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:25.768  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:25.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.768  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.778  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:25.778  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:25.778  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:25.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:25.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:25.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:25.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:25.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-09 22:02:25.778  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:25.778  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:25.778  1178  1178 D HotspotTile: onReceive : 0, 0
,09-09 22:02:25.788  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:25.788  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:25.788  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:25.788  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:25.788  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:25.788  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:25.788  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:25.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:25.788  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:25.788  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:25.788  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:25.788  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:25.788  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:25.788  3679  3679 I Hs20UtilService: Starting #16
,09-09 22:02:25.798  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:25.798  6846  6846 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-09 22:02:25.798  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:25.798  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-09 22:02:25.798  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:25.798  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:25.798  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:25.798  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:25.798  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:25.808  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:25.808  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:25.808  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:25.808  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:25.808  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:25.808  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:25.808  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:25.808  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:25.818  3679  3679 I Hs20UtilService: Starting #17
09-09 22:02:25.818  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:25.818  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:25.918  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:25.958  6846  6846 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-09 22:02:26.018  6835  6835 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-09 22:02:26.018  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:26.018  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:26.018  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:26.038  6835  6835 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-09 22:02:26.048  6835  6835 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-09 22:02:26.048  6835  6835 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-09 22:02:26.048  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.048  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.048  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:26.048  6835  6835 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:26.048  6835  6835 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-09 22:02:26.048  1014  1128 D Tethering: InitialState.processMessage what=4
,09-09 22:02:26.048  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.048  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.048  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:26.048  1014  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 ,
,09-09 22:02:26.048  1014  1128 E Tethering: No numeric data
09-09 22:02:26.048  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.048  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-09 22:02:26.048  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:26.048  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:26.048  1014  1128 D Tethering: clearTetheredNotification()
,09-09 22:02:26.058  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:26.058  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:26.058  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-09 22:02:26.058  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:26.058  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:26.058  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:26.058  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 22:02:26.058  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:26.058  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:26.058  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:26.268  1014  1322 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:26.268  1014  1322 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3930, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 22:02:26.278  1014  1322 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-09 22:02:26.278  1014  1322 D BatteryService: stay LED for charging
09-09 22:02:26.278  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.278  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-09 22:02:26.278  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:26.278  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-09 22:02:26.278  1014  1014 I MotionRecognitionService: Plugged
09-09 22:02:26.278  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:26.288  6835  6835 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:26.288  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
09-09 22:02:26.288  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
09-09 22:02:26.288  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-09 22:02:26.288  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,09-09 22:02:26.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:26.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:26.318  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:26.398  6835  6835 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-09 22:02:26.398  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.398  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:26.398  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:26.408  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-09 22:02:26.408  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:26.408  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1,
,09-09 22:02:26.408  6490  6490 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 22:02:26.418  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:26.418  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-09 22:02:26.418  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:26.418  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:26.418  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:26.418  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:26.418  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:26.418  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-09 22:02:26.418  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:26.418  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:26.418  1178  1178 D HotspotTile: onReceive : 1, 0
,09-09 22:02:26.428  1910  2123 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 22:02:26.428  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:26.428  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.428  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:26.428  1014  2991 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:26.438  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
09-09 22:02:26.438  1014  2991 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:26.438  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:26.438  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:26.438  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:26.448  3679  3679 I Hs20UtilService: Starting #18
09-09 22:02:26.448  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 22:02:26.448  3679  3696 I Hs20UtilService: Message received 5011
09-09 22:02:26.448  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:26.448  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:26.838  1014  2992 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-09 22:02:26.838  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0,
,09-09 22:02:26.838  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:26.838  1014  2992 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:26.838  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 22:02:26.848  6639  6696 I GAV4    : Thread[GAThread,5,main]: No campaign data found.,
,09-09 22:02:26.968  1014  2768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:27.018  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.018  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:27.018  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.028  1014  1371 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 22:02:27.028  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-09 22:02:27.028  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.028  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:27.028  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.038  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.048  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:27.048  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.048  1014  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:27.058  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-09 22:02:27.058  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.058  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.058  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-09 22:02:27.058  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-09 22:02:27.058  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
09-09 22:02:27.058  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.068  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.068  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.068  1014  3033 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:27.068  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 22:02:27.068  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.068  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.068  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.088  1014  3240 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-09 22:02:27.088  1014  3240 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-09 22:02:27.088  1014  3240 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.088  1014  3240 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.088  1014  3240 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.108  1014  1557 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:27.108  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.108  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:27.118  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-09 22:02:27.118  1910  1910 D WearableService: callingUid 10012, callindPid: 1910
,09-09 22:02:27.138  1014  1557 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-09 22:02:27.138  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-09 22:02:27.138  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:27.138  1014  1557 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:27.138  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-09 22:02:27.168   281   935 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-09 22:02:27.168  1014  1041 D Tethering: interfaceRemoved wlan0
09-09 22:02:27.168  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-09 22:02:27.188  6549  6549 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 22:02:27.188  6549  6883 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-09 22:02:27.198  6549  6878 I MusicLeanback: Conditions not met for autocaching.
,09-09 22:02:27.198  6549  6878 I MusicLeanback: Stop autocaching.
,09-09 22:02:27.278   291   291 E SMD     : DCD OFF
,09-09 22:02:27.328  1014  1041 D Tethering: interfaceRemoved p2p0
,09-09 22:02:27.328  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-09 22:02:28.178  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-09 22:02:28.608  1014  1306 E Watchdog: !@Sync 4
,09-09 22:02:28.648  6249  6301 D BluetoothAdapter: enable()
,09-09 22:02:28.648  1014  1345 W ActivityManager: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:28.648  1014  1345 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 22:02:28.648  1014  1345 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:28.648  1014  1345 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:28.648  1014  1345 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:28.658  1014  1345 D SettingsProvider: name = bluetooth_on
,09-09 22:02:28.658  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:28.658  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-09 22:02:28.658  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-09 22:02:28.658  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-09 22:02:28.688  6817  6817 D BluetoothAdapterState: make
,09-09 22:02:28.698  6817  6817 I bluedroid: init
,09-09 22:02:28.698  6817  6886 I BluetoothAdapterState: Entering OffState
09-09 22:02:28.698  6817  6817 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 22:02:28.698  6817  6817 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 22:02:28.698  6817  6817 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 22:02:28.698  6817  6817 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 22:02:28.698  6817  6817 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-09 22:02:28.698  6817  6817 I bluedroid: get_profile_interface socket
09-09 22:02:28.698  6817  6817 I bluedroid: get_profile_interface map_client
09-09 22:02:28.698  6817  6889 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-09 22:02:28.708  6817  6817 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-09 22:02:28.708  6817  6889 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 22:02:28.708  6817  6889 E BluetoothServiceJni: populateRssiValuesNative
09-09 22:02:28.708  6817  6889 I bluedroid: getModelRssiValues
,09-09 22:02:28.708  6817  6889 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 22:02:28.708  6817  6889 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:28.708  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 22:02:28.708  6817  6889 D BluetoothAdapterProperties: Name is: A5-1
,09-09 22:02:28.718  6817  6817 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,09-09 22:02:28.718  1014  3240 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 22:02:28.718  1014  3240 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.718  1014  3240 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.718  1014  3240 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:28.718  1014  3240 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,09-09 22:02:28.718  6817  6825 I bluedroid: config_hci_snoop_log
,09-09 22:02:28.728  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-09 22:02:28.728  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-09 22:02:28.728  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-09 22:02:28.728  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-09 22:02:28.728  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 22:02:28.738  6817  6817 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-09 22:02:28.738  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 22:02:28.738  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:28.738  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 22:02:28.738  6817  6886 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 22:02:28.738  6817  6886 D BluetoothAdapterProperties: Setting state to 11
,09-09 22:02:28.738  6817  6886 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 22:02:28.738  6817  6886 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:28.738  6817  6886 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 22:02:28.748  6817  6886 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:28.748  6817  6886 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 22:02:28.748  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:28.748  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-09 22:02:28.758  1789  1789 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:28.758  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:28.758  6817  6886 D BluetoothSecureManager: getInstant: null
09-09 22:02:28.758  6817  6886 D BluetoothSecureManager: calling getMethod for getService
,09-09 22:02:28.758  6817  6886 D BluetoothSecureManager: calling getService
,09-09 22:02:28.758  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:28.758  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-09 22:02:28.758  6817  6886 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1ef79319
,09-09 22:02:28.768  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:28.768  1014  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:28.768  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:28.768  1014  3240 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:28.768  1014  3240 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.768  1014  1557 D BluetoothSecureManagerService: isSecureModeEnabled
09-09 22:02:28.768  1014  1557 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-09 22:02:28.768  6817  6886 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:28.768  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 22:02:28.768  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
09-09 22:02:28.768  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 22:02:28.768  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-09 22:02:28.768  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-09 22:02:28.768  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:28.768  1014  1472 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-09 22:02:28.768  1014  3240 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.768  1014  3240 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:28.768  1014  3240 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:28.778  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-09 22:02:28.778  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-09 22:02:28.778  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:28.778  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:28.778  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:28.778  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-09 22:02:28.778  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:28.778  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-09 22:02:28.778  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:28.778  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-09 22:02:28.778  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 22:02:28.788  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:28.788  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:28.788  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 22:02:28.788  6817  6886 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-09 22:02:28.788  6817  6886 D BluetoothBondStateMachine: make
,09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:28.798  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 22:02:28.798  1014  3233 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.798  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-09 22:02:28.798  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.798  1014  3233 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.798  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:28.798  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:28.798  6817  6892 I BluetoothBondStateMachine: StableState(): Entering Off State
09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:28.798  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.798  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.798  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.798  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.798  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.798  6817  6817 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 22:02:28.798  6817  6817 D BtGatt.GattService: Received start request. Starting profile...
,09-09 22:02:28.798  6817  6817 D BtGatt.GattService: start()
09-09 22:02:28.798  6817  6817 D BtGatt.GattService: start()
09-09 22:02:28.798  6817  6817 I bluedroid: get_profile_interface gatt
,09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:28.798  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:28.798  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:28.798  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
09-09 22:02:28.798  6817  6817 D BtGatt.AdvertiseManager: advertise manager created
,09-09 22:02:28.808  1014  3033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.808  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.808  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.808  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.808  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.808  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-09 22:02:28.808  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:28.808  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:28.808  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:28.818  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.818  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:28.818  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.818  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.818  6817  6817 D BtGatt.GattService: mStartError = false
09-09 22:02:28.818  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.818  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:28.818  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:28.818  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-09 22:02:28.818  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.818  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.818  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.818  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.818  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.818  6817  6817 D HeadsetService: Received start request. Starting profile...
09-09 22:02:28.818  6817  6817 D HeadsetService: start()
,09-09 22:02:28.818  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:28.818  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:28.818  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:28.818  6817  6817 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 22:02:28.818  1014  2991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.818  6817  6817 D HeadsetStateMachine: make
09-09 22:02:28.818  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 22:02:28.818  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.818  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:28.818  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.828  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:28.828  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:28.828  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:28.828  1014  3033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:28.828  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.828  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:28.828  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.828  6817  6817 E HeadsetStateMachine: # of Max HF connection is 2
09-09 22:02:28.828  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.828  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-09 22:02:28.828  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:28.828  6817  6886 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:28.828  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:28.828  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.828  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:28.828  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.828  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:28.838  1014  1492 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-09 22:02:28.838  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:28.838  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:28.838  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.838  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.838  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:28.838  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:28.838  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:28.838  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:28.838  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:28.838  6817  6886 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-09 22:02:28.838  1014  1322 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-09 22:02:28.838  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0,
09-09 22:02:28.838  1014  1322 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:28.838  1014  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:28.838  1014  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:28.838  6817  6817 I bluedroid: get_profile_interface handsfree
,09-09 22:02:28.858  6817  6817 I DualScoManager: Instantiating Dual Sco Manager
,09-09 22:02:28.858  6817  6817 I DualScoManager: Set HeadsetServiceHelper
,09-09 22:02:28.858  6817  6817 D BluetoothAtMessage: createCMTIContentObservers
,09-09 22:02:28.858  1014  2992 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 22:02:28.858  1014  2992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:28.858  1014  2992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:28.858  1014  2992 D SettingsProvider: selectionArgs: false
09-09 22:02:28.858  1014  2992 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:28.858  1014  2992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:28.858  1014  2992 D SettingsProvider: ret = -1
,09-09 22:02:28.858  6817  6817 D HeadsetService: mStartError = false
09-09 22:02:28.858  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.858  6817  6896 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 22:02:28.868  6817  6817 D A2dpService: Received start request. Starting profile...
09-09 22:02:28.868  6817  6817 D A2dpService: start()
,09-09 22:02:28.868  6817  6896 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-09 22:02:28.868  6817  6896 D HeadsetStateMachine: map size, before remove : 0
,09-09 22:02:28.868  6817  6896 D HeadsetStateMachine: map size, after remove: 0
,09-09 22:02:28.868  6817  6817 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 22:02:28.868  6817  6817 I bluedroid: get_profile_interface avrcp
,09-09 22:02:28.878  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:28.878  6817  6817 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 22:02:28.878  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:28.898  6817  6817 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 22:02:28.898  6817  6899 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
09-09 22:02:28.898  6817  6817 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 22:02:28.898  6817  6817 D A2dpStateMachine: make
,09-09 22:02:28.898  6817  6817 I bluedroid: get_profile_interface a2dp
,09-09 22:02:28.898  6817  6901 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-09 22:02:28.898  6817  6817 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 22:02:28.898  6817  6817 D A2dpService: mStartError = false
09-09 22:02:28.898  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.898  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 22:02:28.908  6817  6817 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 22:02:28.908  6817  6900 D A2dpStateMachine: Enter Disconnected: -2
09-09 22:02:28.908  6817  6817 D HidService: Received start request. Starting profile...
09-09 22:02:28.908  6817  6817 D HidService: start()
09-09 22:02:28.908  6817  6817 I bluedroid: get_profile_interface hidhost
,09-09 22:02:28.908  6817  6817 D HidService: setHidService(): set to: null
09-09 22:02:28.908  6817  6817 D HidService: mStartError = false
09-09 22:02:28.908  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.908  6817  6817 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 22:02:28.908  6817  6817 D HealthService: Received start request. Starting profile...
09-09 22:02:28.908  6817  6817 D HealthService: start()
,09-09 22:02:28.908  6817  6899 D BluetoothMediaBrowser: no now playing list
,09-09 22:02:28.908  6817  6899 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 22:02:28.908  6817  6817 I bluedroid: get_profile_interface health
,09-09 22:02:28.908  6817  6817 D HealthService: mStartError = false
09-09 22:02:28.908  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.908  6817  6817 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 22:02:28.918  6817  6817 D PanService: Received start request. Starting profile...
,09-09 22:02:28.918  6817  6817 D PanService: start()
,09-09 22:02:28.918  6817  6817 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 22:02:28.918  6817  6817 I bluedroid: get_profile_interface pan
,09-09 22:02:28.918  6817  6817 D PanService: mStartError = false
,09-09 22:02:28.918  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.928  6817  6817 D BluetoothMapService: Received start request. Starting profile...
,09-09 22:02:28.928  6817  6817 D BluetoothMapService: start()
,09-09 22:02:28.928  6817  6817 D BluetoothMapService: mStartError = false
,09-09 22:02:28.928  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:28.928  6817  6817 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-09 22:02:28.928  6817  6817 D SapService: Received start request. Starting profile...
,09-09 22:02:28.928  6817  6817 D SapService: start()
09-09 22:02:28.928  6817  6817 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 22:02:28.928  6817  6817 I bluedroid: get_profile_interface sap
,09-09 22:02:28.928  6817  6817 D SapService: mStartError = false
09-09 22:02:28.928  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
09-09 22:02:28.928  6817  6817 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 22:02:28.938  1430  1448 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 22:02:28.938  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-09 22:02:28.938  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:28.938  1430  1448 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 22:02:28.938  6817  6817 D HeadsetStateMachine: Proxy object connected
,09-09 22:02:28.938  6817  6817 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 22:02:28.938  6817  6817 D HeadsetPhoneState: sendDeviceDataStateChanged
09-09 22:02:28.938  6817  6896 D HeadsetStateMachine: Disconnected process message: 11
09-09 22:02:28.938  6817  6817 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 22:02:28.938  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-09 22:02:28.938  6817  6817 D BluetoothA2dp: Proxy object connected
09-09 22:02:28.938  6817  6896 D HeadsetStateMachine: Disconnected process message: 18
09-09 22:02:28.938  6817  6817 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-09 22:02:28.938  6817  6817 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-09 22:02:28.938  6817  6896 D HeadsetStateMachine: Disconnected process message: 10
09-09 22:02:28.938  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 22:02:28.938  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-09 22:02:28.948  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-09 22:02:28.948  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-09 22:02:28.948  6817  6896 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,09-09 22:02:28.948  6817  6896 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:28.968  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 22:02:28.968  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 22:02:28.978  6817  6886 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-09 22:02:28.978  6817  6886 I bluedroid: enable
,09-09 22:02:28.978  6817  6886 I bt_hci_bdroid: init
,09-09 22:02:28.978  6817  6905 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 22:02:28.978  6817  6886 I bt_vendor: bt-vendor : init
,09-09 22:02:28.978  6817  6886 I bt_vendor: bt-vendor : get_bt_soc_type
,09-09 22:02:28.978  6817  6886 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 22:02:28.978  6817  6886 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
,09-09 22:02:28.978  6817  6886 D bt_userial_mct: userial_init
,09-09 22:02:28.978  6817  6886 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 22:02:28.988  6817  6886 I bt_vendor: Starting hciattach daemon
09-09 22:02:28.988  6817  6886 I bt_vendor: try to set false
,09-09 22:02:28.988  6817  6886 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-09 22:02:28.988  6817  6886 I bt_vendor: Starting hciattach daemon
09-09 22:02:28.988  6817  6886 I bt_vendor: try to set true
,09-09 22:02:29.008  6909  6909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-09 22:02:29.058  6915  6915 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 22:02:29.058  6916  6916 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 22:02:29.068  1014  2729 D SSRM:n  : SIOP:: AP = 340,
,09-09 22:02:29.078  6918  6918 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 22:02:29.088  6919  6919 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 22:02:29.098  6920  6920 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 22:02:29.108  6921  6921 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 22:02:29.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:29.358  6924  6924 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-09 22:02:29.368  6925  6925 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 22:02:29.398  6817  6886 I bt_vendor: bluetooth satus is on,
09-09 22:02:29.398  6817  6907 D bt_userial_mct: userial_open(port:0)
09-09 22:02:29.398  6817  6907 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-09 22:02:29.398  6817  6907 I bt_vendor: Done intiailizing UART,
,09-09 22:02:29.398  6817  6907 I bt_vendor: Done intiailizing UART,
09-09 22:02:29.398  6817  6907 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-09 22:02:29.398  6817  6907 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-09 22:02:29.408  6817  6927 D bt_userial_mct: Entering userial_read_thread()
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_A2D
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_BTM
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_PAN
,09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 22:02:29.408  6817  6905 I         : BTE_InitTraceLevels -- TRC_GATT
,09-09 22:02:29.418  6817  6905 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 22:02:29.418  6817  6905 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 22:02:29.418  6817  6905 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-09 22:02:29.418  6817  6905 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 22:02:29.508  6817  6905 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 22:02:29.518  6817  6905 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40606e9 
,09-09 22:02:29.518  6817  6905 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40606e9 
,09-09 22:02:29.538  6817  6889 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 22:02:29.538  6817  6889 E bt-btif : Calling BTA_HhEnable
,09-09 22:02:29.538  6817  6889 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 22:02:29.548  6817  6889 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB,
09-09 22:02:29.548  6817  6889 E BluetoothServiceJni: populateRssiValuesNative,
09-09 22:02:29.548  6817  6889 I bluedroid: getModelRssiValues
09-09 22:02:29.548  6817  6889 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 22:02:29.548  6817  6889 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:29.548  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 22:02:29.548  6817  6889 D BluetoothAdapterProperties: Name is: A5-1,
,09-09 22:02:29.558  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.558  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.558  6817  6889 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 22:02:29.558  6817  6889 D BluetoothAdapterProperties: Scan Mode:20
,09-09 22:02:29.558  6817  6889 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:29.558  6817  6889 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-09 22:02:29.558  6817  6889 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-09 22:02:29.568  6817  6889 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-09 22:02:29.568  6817  6889 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-09 22:02:29.568  6817  6889 E bt-btif : btif_sock_init: !vhci_init
09-09 22:02:29.568  6817  6889 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-09 22:02:29.568  6817  6889 D IOP_DB_BT: db_open: db_open : handle 3028537360l, read 13894 bytes onto local cache
09-09 22:02:29.568  6817  6889 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-09 22:02:29.568  6817  6889 D IOP_DB_BT: db_query: result 1
09-09 22:02:29.568  6817  6889 I         : iop_db_open: iop_db_open status 0
,09-09 22:02:29.568  6817  6889 D bte_conf: Device ID record 1 : primary
09-09 22:02:29.568  6817  6889 D bte_conf:   vendorId            = 0075
09-09 22:02:29.568  6817  6889 D bte_conf:   vendorIdSource      = 0001
09-09 22:02:29.568  6817  6889 D bte_conf:   product             = 0100
09-09 22:02:29.568  6817  6889 D bte_conf:   version             = 0200
09-09 22:02:29.568  6817  6889 D bte_conf:   clientExecutableURL = 
09-09 22:02:29.568  6817  6889 D bte_conf:   serviceDescription  = 
09-09 22:02:29.568  6817  6889 D bte_conf:   documentationURL    = 
09-09 22:02:29.568  6817  6889 D bte_conf: bte_load_did_conf no section named DID2.
,09-09 22:02:29.568  6817  6886 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 22:02:29.568  6817  6886 D BluetoothAdapterProperties: ScanMode =  20
09-09 22:02:29.568  6817  6886 D BluetoothAdapterProperties: State =  11
,09-09 22:02:29.568  1014  1371 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-09 22:02:29.568  6817  6889 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 22:02:29.568  6817  6927 E bt_mct  : hci lib postload completed
,09-09 22:02:29.578  6817  6889 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:29.578  6817  6889 D BluetoothAdapterProperties: Scan Mode:21
09-09 22:02:29.578  6817  6886 D BluetoothAdapterProperties: Setting state to 12
09-09 22:02:29.578  6817  6886 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 22:02:29.578  6817  6889 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:29.578  1014  1026 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 22:02:29.578  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 22:02:29.578  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:29.578  1014  1026 D SettingsProvider: selectionArgs: false
,09-09 22:02:29.578  1014  1026 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:29.578  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:29.578  1014  1026 D SettingsProvider: ret = -1
,09-09 22:02:29.588  6817  6886 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-09 22:02:29.588  6817  6886 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 22:02:29.588  1014  3033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.588  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.588  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.588  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.588  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.598  6817  6886 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:29.598  6817  6886 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 22:02:29.598  6817  6886 D BluetoothAdapterService: starting service from this receiver
,09-09 22:02:29.598  1014  2991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:29.598  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.598  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:29.598  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.598  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:29.598  1327  1338 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 22:02:29.598  6817  6886 I BluetoothAdapterState: Entering On State from state = 11
,09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:29.608  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:29.608  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 22:02:29.608  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.618  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:29.618  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.618  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.618  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.618  6817  6825 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:29.618  6817  6817 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 22:02:29.618  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:29.628  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.628  1430  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.628  1430  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.628  6817  6828 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.628  6817  6828 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:29.628  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:29.628  2856  2875 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.628  2856  2875 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.628  1438  1449 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.628  1438  1449 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.628  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:29.628  1450  1687 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.638  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:29.638  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-09 22:02:29.638  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.638  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.638  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.638  1450  1687 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.638  1327  6453 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:29.638  1327  1327 D BluetoothMap: Proxy object connected
09-09 22:02:29.638  1327  6453 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.638  1327  1327 D MapProfile: Bluetooth service connected
,09-09 22:02:29.638  1327  1327 D BluetoothMap: getConnectedDevices()
09-09 22:02:29.638  6817  6817 I BluetoothPbapService: Handler(): got msg=1
09-09 22:02:29.638  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:29.638  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.638  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.638  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.638  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.648  1014  2991 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:29.648  1430  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.648  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:29.648  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.648  1327  1327 D BluetoothA2dp: Proxy object connected
09-09 22:02:29.648  1327  1327 D A2dpProfile: Bluetooth service connected
09-09 22:02:29.648  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.648  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.648  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.648  1430  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.648  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:29.648  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.648  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:29.648  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.648  1014  1014 D BluetoothA2dp: Proxy object connected
,09-09 22:02:29.658  1430  1448 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.658  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:29.658  6817  6931 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 22:02:29.658  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.658  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.658  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.658  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.658  1430  1448 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.658  6414  6422 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.658  6414  6422 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.658  1178  2696 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.668  1178  2696 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.668  2856  2873 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:29.668  2856  2873 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.668  6817  6931 D BluetoothSocket: bindListen(): myUserId = 0
09-09 22:02:29.668  6817  6931 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:29.668  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:29.668  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.668  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 22:02:29.668  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.668  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-09 22:02:29.668  6817  6931 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-09 22:02:29.668  6817  6931 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:29.668  6817  6931 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:29.668  6817  6931 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@311b984
09-09 22:02:29.668  6817  6931 D BluetoothSocket: channel: 19
09-09 22:02:29.668  6817  6931 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 22:02:29.668  1450  1469 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.668  1450  1469 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:29.668  2856  2856 D BluetoothA2dp: Proxy object connected
,09-09 22:02:29.668  1327  1339 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:29.668  1327  1339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.668  1327  6453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.678  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:29.678  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.678  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.678  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.678  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.678  1327  1327 D HeadsetProfile: Bluetooth service connected
,09-09 22:02:29.678  1327  6453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.678  1910  2115 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:29.678  1910  2115 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.678  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:29.678  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:29.678  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 22:02:29.678  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.678  6249  6703 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:29.678  6249  6703 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:29.678  1327  1339 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 22:02:29.848  1014  1043 I art     : Explicit concurrent mark sweep GC freed 64647(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 2.400ms total 161.052ms
09-09 22:02:29.848  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-09 22:02:29.848  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.848  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.848  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.848  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.848  1327  1327 D BluetoothPbap: Proxy object connected
09-09 22:02:29.848  2856  2873 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:29.848  1327  1327 D PbapServerProfile: Bluetooth service connected
,09-09 22:02:29.848  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:29.848  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.848  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.848  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.848  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.848  2856  2873 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.848  1327  6453 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 22:02:29.858  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-09 22:02:29.858  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.858  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.858  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.858  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.858  1327  1338 D Bluetoothsap: onBluetoothStateChange: up=true
09-09 22:02:29.858  1327  1338 D Bluetoothsap: Binding service...
,09-09 22:02:29.858  1327  1327 D BluetoothInputDevice: Proxy object connected
,09-09 22:02:29.858  1327  1338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 22:02:29.858  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 22:02:29.858  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.858  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.858  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.858  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.858  1327  1338 D Bluetoothsap: bindService called to Bluetooth SAP Service
09-09 22:02:29.868  1014  1043 D BluetoothPan: Binding service...
,09-09 22:02:29.868  1327  1327 D HidProfile: Bluetooth service connected
09-09 22:02:29.868  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 22:02:29.868  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.868  1327  1339 D BluetoothPan: Binding service...
,09-09 22:02:29.888  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:29.888  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-09 22:02:29.888  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-09 22:02:29.888  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.888  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.888  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.888  1430  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:29.888  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:29.888  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:29.888  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.888  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.888  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:29.888  1430  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:29.888  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-09 22:02:29.888  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 22:02:29.898  1327  1327 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-09 22:02:29.898  1327  1327 D SapProfile: Bluetooth service connected
09-09 22:02:29.898  1327  1327 D Bluetoothsap: getConnectedDevices()
,09-09 22:02:29.898  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.898  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,09-09 22:02:29.898  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:29.898  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3e574243, true
,09-09 22:02:29.898  1327  1327 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 22:02:29.898  1327  1327 D PanProfile: Bluetooth service connected
,09-09 22:02:29.898  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:29.908  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:29.908  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.908  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-09 22:02:29.908  1430  1430 D BluetoothHeadset: registerMessageListener
,09-09 22:02:29.908  1789  1789 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:29.908  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:29.908  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.918  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:29.918  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:29.918  1014  1322 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:29.918  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:29.918  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.918  1014  2992 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 22:02:29.918  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:29.918  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:29.918  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:29.918  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:29.928  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:29.928  6817  6828 D HeadsetService: registerMessageListener
,09-09 22:02:29.928  6817  6828 D HeadsetService: registerMessageListener
,09-09 22:02:29.928  6817  6896 D HeadsetStateMachine: Disconnected process message: 70
09-09 22:02:29.928  6817  6896 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@352a656d
,09-09 22:02:29.928  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 22:02:29.928  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:29.928  6817  6934 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 22:02:29.928  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 22:02:29.928  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 22:02:29.928  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 22:02:29.928  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:29.928  6817  6934 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:29.938  6817  6934 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:29.938  6817  6896 D HeadsetStateMachine: Disconnected process message: 9
,09-09 22:02:29.938  6817  6896 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 22:02:29.938  6817  6934 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-09 22:02:29.938  6817  6934 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:29.938  6817  6934 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:29.938  6817  6934 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d4295a2
09-09 22:02:29.938  1327  1327 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 22:02:29.938  1327  1327 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 22:02:29.938  1327  1327 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 22:02:29.938  1327  1327 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 22:02:29.938   286   703 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-09 22:02:29.938   286   703 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 22:02:29.938   286   703 V voice   : voice_set_parameters: exit with code(-2)
,09-09 22:02:29.938   286   703 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 22:02:29.938   286   703 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 22:02:29.948   286   703 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,09-09 22:02:29.948   286   703 V audio_hw_primary: adev_set_parameters: exit
,09-09 22:02:29.948  6817  6934 D BluetoothSocket: channel: 5
09-09 22:02:29.948  6817  6896 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 22:02:29.958  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:29.958  1014  3033 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:29.958  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.958  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.958  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:29.958  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:29.968  1327  1327 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:29.968  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:29.978  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:29.978  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 22:02:29.978  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:29.978  6817  6817 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 22:02:29.978  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:29.988  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 22:02:29.988  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:29.988  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:29.988  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:30.008  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:30.008  1014  2991 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:30.008  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:30.008  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:30.008  1014  2991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:30.008  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:30.008  1014  1371 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:30.018  1910  6942 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 22:02:30.018  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:30.018  1014  1492 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:30.028  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:30.028  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:30.028  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:30.028  6817  6944 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:30.028  6817  6944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:30.028  6817  6944 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
,09-09 22:02:30.028  6817  6944 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:30.028  6817  6944 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:30.028  6817  6944 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd869ee
09-09 22:02:30.028  6817  6944 D BluetoothSocket: channel: 12
09-09 22:02:30.028  6817  6944 I BtOppRfcommListener: Accept thread started.
,09-09 22:02:30.118  1910  2103 I art     : Explicit concurrent mark sweep GC freed 63554(3MB) AllocSpace objects, 66(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.452ms total 80.474ms
,09-09 22:02:30.118  1014  1345 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:30.128  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:30.128  1014  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:30.128  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:30.128  1910  6942 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 22:02:30.268   291   291 E SMD     : DCD OFF,
,09-09 22:02:30.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:31.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:31.668  6249  6301 D BluetoothAdapter: disable()
,09-09 22:02:31.668  1014  1027 D SettingsProvider: name = bluetooth_on
,09-09 22:02:31.678  6817  6886 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-09 22:02:31.678  6817  6886 D BluetoothAdapterProperties: Setting state to 13,
09-09 22:02:31.678  6817  6886 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,09-09 22:02:31.678  1014  3240 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:31.678  6817  6886 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 22:02:31.678  1014  3240 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-09 22:02:31.678  6817  6886 D BluetoothAdapterService: updateAdapterState state is 13
09-09 22:02:31.678  1014  3240 W ActivityManager: userId = 0, bbcId = -10000,
09-09 22:02:31.678  1014  3240 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:31.678  1014  3240 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:31.688  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-09 22:02:31.678  6817  6817 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-09 22:02:31.678  6817  6886 D BluetoothAdapterService: Autoconnection is available 
,09-09 22:02:31.678  6817  6886 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-09 22:02:31.678  6817  6886 D BluetoothAdapterService: terminating service from this receiver,
09-09 22:02:31.688  6817  6817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@217fce8f, channel: 19, state: LISTENING,
09-09 22:02:31.688  6817  6817 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@217fce8f, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@311b984, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@5f4b51cmSocket: android.net.LocalSocket@807d525 impl:android.net.LocalSocketImpl@de536fa fd:FileDescriptor[75]
09-09 22:02:31.688  6817  6817 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@807d525 impl:android.net.LocalSocketImpl@de536fa fd:FileDescriptor[75]
,09-09 22:02:31.688  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:31.688  1014  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:31.688  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:31.688  6817  6886 D BluetoothAdapterProperties: onBluetoothDisable()
09-09 22:02:31.688  6817  6886 D BluetoothAdapterProperties: mDiscovering is false
,09-09 22:02:31.688  1014  1026 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:31.688  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:31.688  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-09 22:02:31.698  6817  6886 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-09 22:02:31.698  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:31.698  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:31.698  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:31.698  1178  1178 D BluetoothTile:  getBluetoothState : 13
,09-09 22:02:31.708  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:31.708  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:31.708  1789  1789 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:31.708  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-09 22:02:31.708  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:31.718  1014  1345 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:31.718  1014  1557 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:31.718  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:31.718  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:31.718  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 22:02:31.718  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:31.728  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:31.728  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:31.728  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:31.728  6817  6889 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 22:02:31.728  6817  6889 D BluetoothAdapterProperties: Scan Mode:20,
09-09 22:02:31.738  1014  1492 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 22:02:31.738  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:31.738  6249  6249 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-09 22:02:31.738  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
09-09 22:02:31.738  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 22:02:31.738  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:31.738  1014  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:31.738  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:31.738  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:31.748  6817  6886 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-09 22:02:31.748  6817  6886 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-09 22:02:31.748  6817  6886 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-09 22:02:31.748  6817  6886 E bt-btif : cmd socket is not created
,09-09 22:02:31.748  1014  3033 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-09 22:02:31.748  6817  6944 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 22:02:31.748  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-09 22:02:31.748  6817  6886 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:31.748  6817  6905 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-09 22:02:31.748  6817  6905 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 22:02:31.748  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:31.748  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:31.748  6817  6905 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:31.748  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:31.748  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:31.748  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:31.758  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:31.768  1327  1327 D BluetoothPbap: Proxy object disconnected
09-09 22:02:31.768  1327  1327 D PbapServerProfile: Bluetooth service disconnected
,09-09 22:02:31.778  6817  6817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b4c4ab, channel: 5, state: LISTENING
,09-09 22:02:31.778  6817  6817 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b4c4ab, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d4295a2, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@28260708mSocket: android.net.LocalSocket@26859ea1 impl:android.net.LocalSocketImpl@2ebfc8c6 fd:FileDescriptor[77]
09-09 22:02:31.778  6817  6817 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26859ea1 impl:android.net.LocalSocketImpl@2ebfc8c6 fd:FileDescriptor[77],
,09-09 22:02:31.778  6817  6817 I BtOppRfcommListener: stopping Accept Thread
09-09 22:02:31.778  6817  6817 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25f90087, channel: 12, state: LISTENING
09-09 22:02:31.778  6817  6817 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25f90087, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd869ee, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@38988bb4mSocket: android.net.LocalSocket@14bc83dd impl:android.net.LocalSocketImpl@1e5fab52 fd:FileDescriptor[80]
09-09 22:02:31.778  6817  6817 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14bc83dd impl:android.net.LocalSocketImpl@1e5fab52 fd:FileDescriptor[80]
09-09 22:02:31.778  6817  6944 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 22:02:31.788  6817  6817 V BluetoothOppManager: cleanUp...
,09-09 22:02:31.788  1327  1327 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:31.788  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:31.798  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:31.798  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-09 22:02:31.818  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:31.818  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 22:02:31.948  6817  6905 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration,
09-09 22:02:31.948  6817  6905 W bt-btif : ag scb idx 1 not allocated,
09-09 22:02:31.948  6817  6905 W bt-btif : ag scb idx 2 not allocated
,09-09 22:02:31.948  6817  6905 E bt-btif : BTA AG is already disabled, ignoring ...
09-09 22:02:31.948  6817  6927 I bt_userial_mct: exiting userial_read_thread
,09-09 22:02:31.948  6817  6927 D bt_userial_mct: Leaving userial_evt_read_thread()
09-09 22:02:31.948  6817  6889 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-09 22:02:31.948  6817  6907 I bt_vendor: hw_epilog_process
09-09 22:02:31.948  6817  6889 D bt_userial_mct: userial_close
,09-09 22:02:31.948  6817  6889 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-09 22:02:32.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...,
,09-09 22:02:32.598  6817  6889 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-09 22:02:32.598  6817  6889 I bt_vendor: bluetooth satus is on
,09-09 22:02:32.598  6817  6889 I bt_vendor: bt-vendor : resetting BT status
,09-09 22:02:32.598  6817  6889 I bt_vendor: Starting hciattach daemon
,09-09 22:02:32.598  6817  6889 I bt_vendor: try to set false
,09-09 22:02:32.608  6817  6889 I bt_vendor: Starting hciattach daemon,
09-09 22:02:32.608  6817  6889 I bt_vendor: try to set false,
,09-09 22:02:32.608  6817  6889 I bt_vendor: cleanup
09-09 22:02:32.618  1014  2992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-09 22:02:32.608  6817  6905 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
09-09 22:02:32.618  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
09-09 22:02:32.608  6817  6889 I GKI_LINUX: GKI_exit_task 0 done
,09-09 22:02:32.618  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.608  6817  6889 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
09-09 22:02:32.618  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.608  6817  6886 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-09 22:02:32.628  1014  2991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.608  6817  6886 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:32.628  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 22:02:32.608  6817  6886 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-09 22:02:32.608  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:32.608  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 22:02:32.618  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-09 22:02:32.618  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.618  1014  2992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.618  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:32.618  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:32.618  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:32.618  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-09 22:02:32.618  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.618  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.618  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:32.618  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:32.618  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:32.618  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-09 22:02:32.628  6817  6817 D BtGatt.DebugUtils: handleDebugAction() action=null
09-09 22:02:32.628  6817  6817 D BtGatt.GattService: Received stop request...Stopping profile...,
09-09 22:02:32.628  6817  6817 D BtGatt.GattService: stop()
,09-09 22:02:32.628  6817  6817 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 22:02:32.628  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:32.628  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:32.628  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.628  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.628  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:32.628  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
09-09 22:02:32.628  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-09 22:02:32.628  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:32.628  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-09 22:02:32.628  6817  6817 D HeadsetService: Received stop request...Stopping profile...
,09-09 22:02:32.628  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.628  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:32.638  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-09 22:02:32.638  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
09-09 22:02:32.638  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-09 22:02:32.638  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-09 22:02:32.638  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 22:02:32.638  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-09 22:02:32.638  1014  1137 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.638  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.638  1327  1327 D HeadsetProfile: Bluetooth service disconnected
,09-09 22:02:32.638  6817  6817 D A2dpService: Received stop request...Stopping profile...
,09-09 22:02:32.638  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.638  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.638  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:32.638  6817  6900 D A2dpStateMachine: Exit Disconnected: -1
09-09 22:02:32.638  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:32.638  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:32.638  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-09 22:02:32.648  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.648  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.648  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.648  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.648  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:32.648  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.648  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.648  6817  6886 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:32.648  1014  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.648  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.648  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.648  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.648  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:32.648  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.648  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-09 22:02:32.648  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:32.648  6817  6886 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:32.648  1014  1959 V SAMP_SPCM_test: CSC File load.. 
,09-09 22:02:32.658  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:32.658  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-09 22:02:32.658  1327  1327 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:32.658  1327  1327 D A2dpProfile: Bluetooth service disconnected
09-09 22:02:32.658  2856  2856 D BluetoothA2dp: Proxy object disconnected
,09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-09 22:02:32.668  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
,09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 22:02:32.698  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control,
,09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-09 22:02:32.718  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-09 22:02:32.718  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0,
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-09 22:02:32.708  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
,09-09 22:02:32.718  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-09 22:02:32.718  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,09-09 22:02:32.718  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-09 22:02:32.718  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-09 22:02:32.718  1014  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-09 22:02:32.718  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.718  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.718  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:32.718  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:32.718  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-09 22:02:32.718  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-09 22:02:32.718  6817  6886 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 22:02:32.718  6817  6886 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-09 22:02:32.718  6817  6886 D BluetoothAdapterState: Stopping profile services that were post enabled
09-09 22:02:32.718  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-09 22:02:32.718  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-09 22:02:32.718  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:32.718  6817  6817 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-09 22:02:32.718  6817  6817 D HidService: Received stop request...Stopping profile...
09-09 22:02:32.718  6817  6817 D HidService: Stopping Bluetooth HidService
09-09 22:02:32.718  6817  6817 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 22:02:32.718  6817  6817 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-09 22:02:32.718  6817  6817 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 22:02:32.718  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.728  1327  1327 D BluetoothInputDevice: Proxy object disconnected
09-09 22:02:32.728  1327  1327 D HidProfile: Bluetooth service disconnected
,09-09 22:02:32.728  6817  6817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
09-09 22:02:32.728  6817  6817 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 22:02:32.728  6817  6817 D HealthService: Received stop request...Stopping profile...
09-09 22:02:32.728  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.728  6817  6817 D PanService: Received stop request...Stopping profile...
09-09 22:02:32.728  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.728  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 22:02:32.738  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-09 22:02:32.738  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:32.738  6817  6817 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-09 22:02:32.738  1327  1327 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 22:02:32.738  6817  6817 D BluetoothMapService: Received stop request...Stopping profile...
09-09 22:02:32.738  1014  1959 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-09 22:02:32.738  1327  1327 D PanProfile: Bluetooth service disconnected
,09-09 22:02:32.738  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.738  6817  6817 D BluetoothA2dp: Proxy object disconnected
09-09 22:02:32.738  6817  6817 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-09 22:02:32.738  6817  6901 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-09 22:02:32.738  6817  6817 I GKI_LINUX: GKI_exit_task 2 done
09-09 22:02:32.738  6817  6817 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-09 22:02:32.738  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-09 22:02:32.738  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.738  6817  6817 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:32.748  1327  1327 D BluetoothMap: Proxy object disconnected
09-09 22:02:32.748  1327  1327 D MapProfile: Bluetooth service disconnected
,09-09 22:02:32.748  6817  6817 D SapService: Received stop request...Stopping profile...
09-09 22:02:32.748  6817  6817 D SapService: Stopping Bluetooth SapService
09-09 22:02:32.748  6817  6817 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@314ab4eb
,09-09 22:02:32.748  1327  1327 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-09 22:02:32.748  1327  1327 D SapProfile: Bluetooth service disconnected
,09-09 22:02:32.748  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-09 22:02:32.748  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.748  6817  6817 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.748  6817  6817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 22:02:32.748  6817  6817 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 22:02:32.748  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-09 22:02:32.748  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.748  6817  6817 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:32.748  6817  6817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 22:02:32.748  6817  6817 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-09 22:02:32.748  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-09 22:02:32.748  6817  6817 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:32.748  6817  6817 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-09 22:02:32.748  6817  6817 E BluetoothAdapterService(826979563): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-09 22:02:32.758  6817  6817 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-09 22:02:32.758  6817  6817 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-09 22:02:32.758  6817  6886 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-09 22:02:32.758  6817  6886 D BluetoothAdapterProperties: Setting state to 10
,09-09 22:02:32.758  6817  6886 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,09-09 22:02:32.758  6817  6886 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-09 22:02:32.758  6817  6886 D BluetoothAdapterService: updateAdapterState state is 10
,09-09 22:02:32.758  6817  6886 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:32.758  1327  1339 D BluetoothMap: onBluetoothStateChange: up=false
09-09 22:02:32.758  6817  6886 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-09 22:02:32.758  6817  6886 I BluetoothAdapterState: Entering OffState
09-09 22:02:32.758  6817  6890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 22:02:32.758  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:32.758  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:32.758  1430  2725 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:32.758  1430  2725 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:32.758  6817  6932 D BluetoothAdapter: onBluetoothStateChange: up=false
09-09 22:02:32.758  6817  6932 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:32.758  2856  2873 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  2856  2873 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.768  1438  1449 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1438  1449 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.768  1327  6453 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:32.768  6414  6427 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  6414  6427 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:32.768  1178  1196 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1178  1196 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.768  2856  2875 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1450  1687 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1450  1687 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.768  1327  1338 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.768  1327  1338 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.778  1910  2112 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.778  1910  2112 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-09 22:02:32.778  6249  6259 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-09 22:02:32.778  6249  6259 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-09 22:02:32.778  6249  6259 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-09 22:02:32.778  6249  6259 D BluetoothLeAdvertiser: Exit stop advertising
,09-09 22:02:32.778  6249  6259 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-09 22:02:32.778  6249  6259 D BluetoothLeScanner: Exiting stopAllScan
,09-09 22:02:32.778  1327  6453 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 22:02:32.778  1327  1338 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-09 22:02:32.778  1327  1339 D Bluetoothsap: onBluetoothStateChange: up=false
,09-09 22:02:32.778  1327  1339 D Bluetoothsap: Unbinding service...
,09-09 22:02:32.778  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-09 22:02:32.788  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 22:02:32.788  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:32.788  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,09-09 22:02:32.788  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:32.798  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.798  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:32.798  1178  1738 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.798  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:32.798  1178  1178 D BluetoothTile:  getBluetoothState : 10
,09-09 22:02:32.798  1178  1738 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.798  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.798  1178  1178 D BluetoothAdapter: 708215514: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.798  1014  1345 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:32.808  1014  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:32.808  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:32.808  1910  2123 D BluetoothAdapter: 1011791344: getState() :  mService = null. Returning STATE_OFF
09-09 22:02:32.808  1910  2123 D BluetoothAdapter: 1011791344: getState() :  mService = null. Returning STATE_OFF
,09-09 22:02:32.808  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:32.808  1789  1789 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:32.808  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:32.808  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:32.808  1014  1371 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:32.808  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.808  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.808  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:32.808  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:32.818  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:32.818  1014  1492 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:32.818  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.818  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:32.818  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:32.818  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:32.818  6817  6889 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-09 22:02:32.828  6817  6817 I GKI_LINUX: GKI_exit_task 1 done
09-09 22:02:32.828  6817  6817 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-09 22:02:32.828  6817  6817 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 22:02:32.828  1327  1327 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:32.828  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:32.838  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:32.838  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-09 22:02:32.838  6817  6817 I art     : System.exit called, status: 0
09-09 22:02:32.838  6817  6817 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 22:02:32.918  1014  1492 I ActivityManager: Process com.android.bluetooth (pid 6817)(adj 0) has died(59,1083)
,09-09 22:02:32.928  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:32.928  1014  3033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:32.928  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:32.928  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:32.928  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:32.928  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:32.938  1910  6962 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 22:02:32.938  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:32.948  1014  1371 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:32.948  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:32.948  1014  1371 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:32.948  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:32.958  1910  6962 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-09 22:02:33.278   291   291 E SMD     : DCD OFF
,09-09 22:02:33.278   336   336 I ServiceManager: Waiting for service AtCmdFwd...
,09-09 22:02:34.278   336   336 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-09 22:02:34.678  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 22:02:34.678  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:36.268   291   291 E SMD     : DCD OFF,
,09-09 22:02:36.338  1014  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-09 22:02:36.338  1014  1137 D BatteryService: level:65, scale:100, status:2, health:2, present:true, voltage: 3948, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-09 22:02:36.338  1014  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-09 22:02:36.338  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-09 22:02:36.348  1014  1014 I MotionRecognitionService: Plugged
09-09 22:02:36.348  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-09 22:02:36.348  1014  1137 D BatteryService: stay LED for charging,
09-09 22:02:36.348  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-09 22:02:36.348  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-09 22:02:36.348  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-09 22:02:36.348  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 65
,09-09 22:02:36.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:36.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:36.368  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:65 status:2 health:2
,09-09 22:02:37.688  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:37.688  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d349abb added. We now have 6 listener(s)
,09-09 22:02:37.688  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:37.688  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:37.688  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2e2d0bd8 added. We now have 7 listener(s)
,09-09 22:02:37.688  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:37.688  6249  6301 I System.out: IsBluetoothEnabled
,09-09 22:02:37.688  6249  6301 D BluetoothAdapter: disable()
,09-09 22:02:37.688  1014  2991 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-09 22:02:37.688  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:37.688  6249  6301 D BluetoothAdapter: enable()
,09-09 22:02:37.698  1014  3233 W ActivityManager: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:37.698  1014  3233 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-09 22:02:37.698  1014  3233 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:37.698  1014  3233 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:37.698  1014  3233 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:37.698  1014  3233 D SettingsProvider: name = bluetooth_on
,09-09 22:02:37.708  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:37.708  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:37.708  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-09 22:02:37.708  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,09-09 22:02:37.718  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 22:02:37.718  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:37.718  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:37.718  1014  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 22:02:37.728  1014  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6968 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-09 22:02:37.738  6968  6968 E Zygote  : MountEmulatedStorage(),
09-09 22:02:37.738  6968  6968 I libpersona: KNOX_SDCARD checking this for 1002
09-09 22:02:37.738  6968  6968 E Zygote  : v2
,09-09 22:02:37.738  6968  6968 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:37.738  6968  6968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:37.738  6968  6968 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-09 22:02:37.748  6968  6968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-09 22:02:37.778  6968  6968 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:37.778  6968  6968 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:37.788  6968  6968 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-09 22:02:37.798  6968  6968 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:37.818  6968  6968 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding GattService
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding HeadsetService
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding A2dpService
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding HidService
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding HealthService
,09-09 22:02:37.858  6968  6968 D BtSettings.ProfileConfig: Adding PanService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding SapService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding SapClientService
,09-09 22:02:37.868  6968  6968 D BtSettings.ProfileConfig: Adding HidDevService
,09-09 22:02:37.868  6968  6968 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-09 22:02:37.868  1014  1472 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-09 22:02:37.868  1014  1472 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 22:02:37.868  1014  1472 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:37.868  1014  1472 D SettingsProvider: selectionArgs: false
,09-09 22:02:37.868  1014  1472 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:37.878  1014  1472 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:37.878  1014  1472 D SettingsProvider: ret = -1
,09-09 22:02:37.878  1014  3240 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:37.878  1014  3240 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.878  1014  3240 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:37.878  1014  3240 D SettingsProvider: selectionArgs: false
,09-09 22:02:37.878  1014  3240 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:37.878  1014  3240 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:37.878  1014  3240 D SettingsProvider: ret = -1
,09-09 22:02:37.878  1014  1492 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:37.878  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-09 22:02:37.878  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:37.878  1014  1492 D SettingsProvider: selectionArgs: false
09-09 22:02:37.878  1014  1492 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:37.888  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-09 22:02:37.888  1014  1492 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  2992 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-09 22:02:37.888  1014  2992 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  2992 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.888  1014  2992 D SettingsProvider: selectionArgs: false
09-09 22:02:37.888  1014  2992 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  2992 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:37.888  1014  2992 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  1558 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-09 22:02:37.888  1014  1558 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  1558 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:37.888  1014  1558 D SettingsProvider: selectionArgs: false
09-09 22:02:37.888  1014  1558 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  1558 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  1558 D SettingsProvider: ret = -1
,09-09 22:02:37.888  1014  3033 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
,09-09 22:02:37.888  1014  3033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  3033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-09 22:02:37.888  1014  3033 D SettingsProvider: selectionArgs: false,
,09-09 22:02:37.888  1014  3033 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  3033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  3033 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  1371 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:37.888  1014  1371 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  1371 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.888  1014  1371 D SettingsProvider: selectionArgs: false
09-09 22:02:37.888  1014  1371 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  1371 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-09 22:02:37.888  1014  1371 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  1345 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-09 22:02:37.888  1014  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:37.888  1014  1345 D SettingsProvider: selectionArgs: false,
09-09 22:02:37.888  1014  1345 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  1345 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  3239 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:37.888  1014  3239 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  3239 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.888  1014  3239 D SettingsProvider: selectionArgs: false
09-09 22:02:37.888  1014  3239 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  3239 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  3239 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  2991 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:37.888  1014  2991 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  2991 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.888  1014  2991 D SettingsProvider: selectionArgs: false
,09-09 22:02:37.888  1014  2991 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  2991 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  2991 D SettingsProvider: ret = -1
09-09 22:02:37.888  1014  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-09 22:02:37.888  1014  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.888  1014  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.888  1014  1322 D SettingsProvider: selectionArgs: false
09-09 22:02:37.888  1014  1322 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.888  1014  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.888  1014  1322 D SettingsProvider: ret = -1
09-09 22:02:37.898  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-09 22:02:37.898  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:37.898  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:37.898  1014  1026 D SettingsProvider: selectionArgs: false
09-09 22:02:37.898  1014  1026 D SettingsProvider: selectionArgs: 1002
09-09 22:02:37.898  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:37.898  1014  1026 D SettingsProvider: ret = -1
,09-09 22:02:37.918  6968  6968 D BluetoothAdapterState: make
,09-09 22:02:37.918  6968  6968 I bluedroid: init
09-09 22:02:37.918  6968  6983 I BluetoothAdapterState: Entering OffState
,09-09 22:02:37.928  6968  6968 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 22:02:37.928  6968  6968 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-09 22:02:37.928  6968  6968 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 22:02:37.928  6968  6968 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-09 22:02:37.928  6968  6968 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-09 22:02:37.928  6968  6968 I bluedroid: get_profile_interface socket
09-09 22:02:37.928  6968  6968 I bluedroid: get_profile_interface map_client,
,09-09 22:02:37.928  6968  6986 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-09 22:02:37.928  6968  6968 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-09 22:02:37.938  6968  6986 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 22:02:37.938  6968  6986 E BluetoothServiceJni: populateRssiValuesNative
09-09 22:02:37.938  6968  6986 I bluedroid: getModelRssiValues
09-09 22:02:37.938  6968  6986 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-09 22:02:37.938  6968  6986 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:37.948  6968  6986 D BluetoothAdapterProperties: Name is: A5-1
,09-09 22:02:37.948  6968  6968 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:37.948  1014  1345 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:37.948  1014  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:37.948  1014  1345 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:37.948  1014  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:37.948  1014  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:37.948  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 22:02:37.948  6968  6976 I bluedroid: config_hci_snoop_log
,09-09 22:02:37.958  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-09 22:02:37.968  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-09 22:02:37.968  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-09 22:02:37.968  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 22:02:37.968  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-09 22:02:37.968  6968  6968 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-09 22:02:37.978  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-09 22:02:37.978  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-09 22:02:37.978  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-09 22:02:37.978  6968  6983 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-09 22:02:37.988  6968  6983 D BluetoothAdapterProperties: Setting state to 11
09-09 22:02:37.988  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-09 22:02:37.988  6968  6983 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-09 22:02:37.988  6968  6983 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:37.988  6968  6983 D BluetoothAdapterService: updateAdapterState state is 11
,09-09 22:02:37.988  6968  6983 D BluetoothAdapterService: Autoconnection is available 
,09-09 22:02:37.988  6968  6983 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-09 22:02:37.988  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:37.988  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-09 22:02:37.988  6968  6983 D BluetoothSecureManager: getInstant: null
09-09 22:02:37.988  6968  6983 D BluetoothSecureManager: calling getMethod for getService
09-09 22:02:37.988  6968  6983 D BluetoothSecureManager: calling getService
,09-09 22:02:37.988  6968  6983 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2b721c92
09-09 22:02:37.988  1014  3240 D BluetoothSecureManagerService: isSecureModeEnabled
09-09 22:02:37.988  1014  3240 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-09 22:02:37.988  6968  6983 D BtConfig.SecureMode: isSecureModeOn:false
09-09 22:02:37.988  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-09 22:02:37.988  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-09 22:02:37.988  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:37.998  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-09 22:02:37.998  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:37.998  1178  1178 D BluetoothTile:  getBluetoothState : 11
,09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:37.998  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-09 22:02:37.998  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-09 22:02:37.998  1014  1558 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:38.008  6968  6983 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-09 22:02:38.008  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:38.008  1789  1789 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:38.008  1014  3033 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-09 22:02:38.008  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-09 22:02:38.008  6968  6983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:38.008  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:38.008  6968  6983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService,
09-09 22:02:38.008  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:38.008  6968  6983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:38.008  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:38.008  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-09 22:02:38.008  6968  6983 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-09 22:02:38.008  1014  2991 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:38.018  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.028  6968  6983 D BluetoothBondStateMachine: make
,09-09 22:02:38.028  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.028  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:38.028  1014  2991 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:38.028  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:38.028  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-09 22:02:38.028  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:38.028  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-09 22:02:38.028  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-09 22:02:38.028  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-09 22:02:38.028  6968  6988 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 22:02:38.028  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:38.028  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.038  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.038  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.038  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:38.038  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-09 22:02:38.038  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-09 22:02:38.038  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-09 22:02:38.038  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-09 22:02:38.038  6968  6968 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 22:02:38.038  6968  6968 D BtGatt.GattService: Received start request. Starting profile...
09-09 22:02:38.038  6968  6968 D BtGatt.GattService: start()
09-09 22:02:38.038  6968  6968 D BtGatt.GattService: start()
09-09 22:02:38.038  6968  6968 I bluedroid: get_profile_interface gatt
,09-09 22:02:38.038  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:38.038  6968  6968 D BtGatt.AdvertiseManager: advertise manager created
,09-09 22:02:38.038  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:38.048  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-09 22:02:38.048  1014  3033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:38.048  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.048  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.048  1014  3033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.048  6968  6968 D BtGatt.GattService: mStartError = false
,09-09 22:02:38.048  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.048  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.058  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-09 22:02:38.058  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-09 22:02:38.058  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-09 22:02:38.058  1014  1558 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.058  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.058  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.058  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.058  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.068  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-09 22:02:38.068  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-09 22:02:38.068  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-09 22:02:38.068  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.068  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.068  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.078  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.078  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.078  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-09 22:02:38.078  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-09 22:02:38.078  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-09 22:02:38.078  1014  3239 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.078  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.078  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.078  1014  3239 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.078  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-09 22:02:38.088  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-09 22:02:38.088  1014  2991 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.088  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.088  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.088  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.088  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-09 22:02:38.088  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-09 22:02:38.088  1014  2992 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-09 22:02:38.088  1014  2992 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.088  1014  2992 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.088  1014  2992 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.088  1014  2992 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-09 22:02:38.088  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-09 22:02:38.088  6968  6983 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-09 22:02:38.088  1014  1492 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.088  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.088  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.088  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:38.088  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:38.098  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:38.098  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-09 22:02:38.098  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,09-09 22:02:38.098  6968  6983 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-09 22:02:38.098  6968  6983 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,09-09 22:02:38.098  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-09 22:02:38.098  6968  6968 D HeadsetService: Received start request. Starting profile...
,09-09 22:02:38.098  6968  6968 D HeadsetService: start()
,09-09 22:02:38.108  6968  6983 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-09 22:02:38.108  6968  6968 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-09 22:02:38.108  6968  6968 D HeadsetStateMachine: make
,09-09 22:02:38.108  6968  6968 E HeadsetStateMachine: # of Max HF connection is 2
,09-09 22:02:38.108  1014  1558 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-09 22:02:38.108  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.118  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.118  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.118  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:38.118  1014  1137 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-09 22:02:38.118  1014  1137 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.118  1014  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.118  1014  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.118  1014  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-09 22:02:38.118  6968  6968 I bluedroid: get_profile_interface handsfree
,09-09 22:02:38.138  6968  6968 I DualScoManager: Instantiating Dual Sco Manager
,09-09 22:02:38.138  6968  6968 I DualScoManager: Set HeadsetServiceHelper
,09-09 22:02:38.138  6968  6968 D BluetoothAtMessage: createCMTIContentObservers
,09-09 22:02:38.138  1014  1557 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-09 22:02:38.138  1014  1557 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:38.138  1014  1557 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 22:02:38.138  1014  1557 D SettingsProvider: selectionArgs: false
09-09 22:02:38.138  1014  1557 D SettingsProvider: selectionArgs: 1002
,09-09 22:02:38.138  1014  1557 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:38.138  1014  1557 D SettingsProvider: ret = -1
,09-09 22:02:38.138  6968  6968 D HeadsetService: mStartError = false,
09-09 22:02:38.138  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:38.138  6968  6995 D HeadsetStateMachine: Enter Disconnected: -2
,09-09 22:02:38.148  6968  6995 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-09 22:02:38.148  6968  6995 D HeadsetStateMachine: map size, before remove : 0
09-09 22:02:38.148  6968  6995 D HeadsetStateMachine: map size, after remove: 0
,09-09 22:02:38.148  6968  6968 D A2dpService: Received start request. Starting profile...
09-09 22:02:38.148  6968  6968 D A2dpService: start()
,09-09 22:02:38.148  6968  6968 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 22:02:38.148  6968  6968 I bluedroid: get_profile_interface avrcp
,09-09 22:02:38.158  6968  6968 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 22:02:38.168  6968  6968 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-09 22:02:38.168  6968  6996 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-09 22:02:38.168  6968  6968 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 22:02:38.168  6968  6968 D A2dpStateMachine: make
,09-09 22:02:38.178  6968  6968 I bluedroid: get_profile_interface a2dp
,09-09 22:02:38.178  6968  6998 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-09 22:02:38.178  6968  6968 E bt-btif : warning : media task started media_task_refcnt 1 
,09-09 22:02:38.178  6968  6968 D A2dpService: mStartError = false
09-09 22:02:38.178  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.178  6968  6997 D A2dpStateMachine: Enter Disconnected: -2
,09-09 22:02:38.178  6968  6968 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 22:02:38.178  6968  6968 D HidService: Received start request. Starting profile...
09-09 22:02:38.178  6968  6968 D HidService: start()
09-09 22:02:38.178  6968  6968 I bluedroid: get_profile_interface hidhost
09-09 22:02:38.178  6968  6968 D HidService: setHidService(): set to: null
09-09 22:02:38.178  6968  6968 D HidService: mStartError = false
09-09 22:02:38.178  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.178  6968  6968 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 22:02:38.188  6968  6968 D HealthService: Received start request. Starting profile...
09-09 22:02:38.188  6968  6968 D HealthService: start()
,09-09 22:02:38.188  6968  6968 I bluedroid: get_profile_interface health
,09-09 22:02:38.188  6968  6968 D HealthService: mStartError = false
09-09 22:02:38.188  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.188  6968  6968 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 22:02:38.188  6968  6968 D PanService: Received start request. Starting profile...
09-09 22:02:38.188  6968  6968 D PanService: start()
09-09 22:02:38.188  6968  6968 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 22:02:38.188  6968  6968 I bluedroid: get_profile_interface pan
,09-09 22:02:38.188  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:38.188  6968  6968 D PanService: mStartError = false
09-09 22:02:38.188  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.198  6968  6968 D BluetoothMapService: Received start request. Starting profile...
09-09 22:02:38.198  6968  6968 D BluetoothMapService: start()
,09-09 22:02:38.198  6968  6996 D BluetoothMediaBrowser: no now playing list
,09-09 22:02:38.198  6968  6996 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-09 22:02:38.198  6968  6968 D BluetoothMapService: mStartError = false
09-09 22:02:38.198  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:38.198  6968  6968 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-09 22:02:38.198  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:38.198  6968  6968 D SapService: Received start request. Starting profile...
,09-09 22:02:38.198  6968  6968 D SapService: start()
09-09 22:02:38.198  6968  6968 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-09 22:02:38.198  6968  6968 I bluedroid: get_profile_interface sap
09-09 22:02:38.198  6968  6968 D SapService: mStartError = false
09-09 22:02:38.198  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:38.208  6968  6968 D HeadsetStateMachine: Try to query the phonestate on bind
,09-09 22:02:38.208  1430  2725 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 22:02:38.208  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-09 22:02:38.208  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-09 22:02:38.208  1430  2725 I Telecom : BluetoothPhoneService: Result of Message : true
,09-09 22:02:38.208  6968  6968 D HeadsetStateMachine: Proxy object connected
,09-09 22:02:38.208  6968  6968 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-09 22:02:38.208  6968  6968 D HeadsetPhoneState: sendDeviceDataStateChanged,
09-09 22:02:38.208  6968  6995 D HeadsetStateMachine: Disconnected process message: 11
09-09 22:02:38.208  6968  6995 D HeadsetStateMachine: Disconnected process message: 18
09-09 22:02:38.208  6968  6968 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-09 22:02:38.208  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,09-09 22:02:38.208  6968  6968 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-09 22:02:38.208  6968  6968 D BluetoothA2dp: Proxy object connected
09-09 22:02:38.208  6968  6968 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-09 22:02:38.208  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-09 22:02:38.208  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-09 22:02:38.208  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-09 22:02:38.208  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-09 22:02:38.208  6968  6995 D HeadsetStateMachine: Disconnected process message: 10
09-09 22:02:38.208  6968  6995 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
09-09 22:02:38.208  6968  6995 D HeadsetStateMachine: Disconnected process message: 11
,09-09 22:02:38.238  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-09 22:02:38.238  6968  6968 E BluetoothAdapterService(385203045): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-09 22:02:38.238  6968  6983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-09 22:02:38.238  6968  6983 I bluedroid: enable
,09-09 22:02:38.238  6968  6983 I bt_hci_bdroid: init
,09-09 22:02:38.238  6968  6983 I bt_vendor: bt-vendor : init
09-09 22:02:38.238  6968  6983 I bt_vendor: bt-vendor : get_bt_soc_type
09-09 22:02:38.238  6968  6983 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-09 22:02:38.238  6968  6983 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-09 22:02:38.238  6968  6983 D bt_userial_mct: userial_init
,09-09 22:02:38.238  6968  6983 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-09 22:02:38.238  6968  6983 I bt_vendor: Starting hciattach daemon
09-09 22:02:38.238  6968  6983 I bt_vendor: try to set false
,09-09 22:02:38.238  6968  6983 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-09 22:02:38.238  6968  6983 I bt_vendor: Starting hciattach daemon
09-09 22:02:38.238  6968  6983 I bt_vendor: try to set true
09-09 22:02:38.238  6968  7003 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-09 22:02:38.258  7007  7007 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-09 22:02:38.298  7013  7013 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-09 22:02:38.308  7014  7014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 22:02:38.328  7016  7016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 22:02:38.328  7017  7017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-09 22:02:38.338  7018  7018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-09 22:02:38.348  7019  7019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-09 22:02:38.548  7022  7022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-09 22:02:38.558  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-09 22:02:38.588  6968  6983 I bt_vendor: bluetooth satus is on
,09-09 22:02:38.588  6968  7005 D bt_userial_mct: userial_open(port:0)
09-09 22:02:38.588  6968  7005 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-09 22:02:38.598  6968  7005 I bt_vendor: Done intiailizing UART,
,09-09 22:02:38.598  6968  7005 I bt_vendor: Done intiailizing UART
09-09 22:02:38.598  6968  7005 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-09 22:02:38.598  6968  7005 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-09 22:02:38.608  6968  7025 D bt_userial_mct: Entering userial_read_thread()
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_SAP
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_SDP
,09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 22:02:38.608  6968  7003 I         : BTE_InitTraceLevels -- TRC_SMP
,09-09 22:02:38.618  6968  7003 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 22:02:38.618  6968  7003 I         : BTE_InitTraceLevels -- TRC_BTIF
09-09 22:02:38.618  6968  7003 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-09 22:02:38.708  6968  7003 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-09 22:02:38.718  6968  7003 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40606e9 
,09-09 22:02:38.718  6968  7003 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40606e9 
,09-09 22:02:38.728  6968  6986 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-09 22:02:38.738  6968  6986 E bt-btif : Calling BTA_HhEnable
,09-09 22:02:38.738  6968  6986 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-09 22:02:38.738  6968  6986 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-09 22:02:38.738  6968  6986 E BluetoothServiceJni: populateRssiValuesNative
,09-09 22:02:38.738  6968  6986 I bluedroid: getModelRssiValues
09-09 22:02:38.738  6968  6986 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-09 22:02:38.738  6968  6986 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-09 22:02:38.748  6968  6986 D BluetoothAdapterProperties: Name is: A5-1,
09-09 22:02:38.748  1014  1014 D SettingsProvider: name = bluetooth_name
,09-09 22:02:38.748  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-09 22:02:38.758  6968  6986 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-09 22:02:38.758  6968  6986 D BluetoothAdapterProperties: Scan Mode:20
,09-09 22:02:38.758  6968  6986 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:38.758  6968  6986 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-09 22:02:38.758  6968  6986 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-09 22:02:38.758  6968  6986 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-09 22:02:38.758  6968  6986 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-09 22:02:38.758  6968  6986 E bt-btif : btif_sock_init: !vhci_init
,09-09 22:02:38.758  6968  6986 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-09 22:02:38.758  6968  7025 E bt_mct  : hci lib postload completed
,09-09 22:02:38.758  6968  6986 D IOP_DB_BT: db_open: db_open : handle 3028635664l, read 13894 bytes onto local cache
,09-09 22:02:38.758  6968  6986 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-09 22:02:38.768  6968  6986 D IOP_DB_BT: db_query: result 1
09-09 22:02:38.768  6968  6986 I         : iop_db_open: iop_db_open status 0
,09-09 22:02:38.768  6968  6986 D bte_conf: Device ID record 1 : primary
09-09 22:02:38.768  6968  6986 D bte_conf:   vendorId            = 0075
09-09 22:02:38.768  6968  6986 D bte_conf:   vendorIdSource      = 0001
09-09 22:02:38.768  6968  6986 D bte_conf:   product             = 0100
09-09 22:02:38.768  6968  6986 D bte_conf:   version             = 0200
09-09 22:02:38.768  6968  6986 D bte_conf:   clientExecutableURL = 
09-09 22:02:38.768  6968  6986 D bte_conf:   serviceDescription  = 
09-09 22:02:38.768  6968  6986 D bte_conf:   documentationURL    = 
09-09 22:02:38.768  6968  6986 D bte_conf: bte_load_did_conf no section named DID2.
,09-09 22:02:38.768  6968  6986 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 22:02:38.768  6968  6983 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-09 22:02:38.768  6968  6983 D BluetoothAdapterProperties: ScanMode =  20
09-09 22:02:38.768  6968  6983 D BluetoothAdapterProperties: State =  11
,09-09 22:02:38.768  1014  1557 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-09 22:02:38.768  6968  6986 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-09 22:02:38.768  6968  6986 D BluetoothAdapterProperties: Scan Mode:21
09-09 22:02:38.768  6968  6983 D BluetoothAdapterProperties: Setting state to 12
09-09 22:02:38.768  6968  6983 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 22:02:38.768  6968  6986 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 22:02:38.778  1014  1492 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-09 22:02:38.778  1014  1492 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 22:02:38.778  1014  1492 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-09 22:02:38.778  1014  1492 D SettingsProvider: selectionArgs: false
09-09 22:02:38.778  1014  1492 D SettingsProvider: selectionArgs: 1002
09-09 22:02:38.778  1014  1492 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 22:02:38.778  1014  1492 D SettingsProvider: ret = -1
,09-09 22:02:38.778  6968  6983 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-09 22:02:38.778  6968  6983 D BluetoothAdapterService: updateAdapterState state is 12
,09-09 22:02:38.778  1014  1472 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.778  1014  1472 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.778  1014  1472 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.788  1014  1472 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-09 22:02:38.788  1014  1472 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.788  6968  6983 D BluetoothAdapterService: Autoconnection is available 
09-09 22:02:38.788  6968  6983 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-09 22:02:38.788  6968  6983 D BluetoothAdapterService: starting service from this receiver
,09-09 22:02:38.788  1327  1338 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:38.788  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 22:02:38.788  1014  3239 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:38.788  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.788  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.798  1014  3239 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.798  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.798  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-09 22:02:38.798  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.798  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.798  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.798  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.798  6968  6983 I BluetoothAdapterState: Entering On State from state = 11
,09-09 22:02:38.798  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.808  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.808  1430  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.808  1430  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.808  2856  2929 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.808  2856  2929 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.808  1438  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:38.808  1438  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.808  1450  1687 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.818  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:38.818  6968  6968 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-09 22:02:38.818  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:38.818  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.818  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.818  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.818  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.818  1450  1687 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.828  1327  1339 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:38.828  1327  1339 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.828  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-09 22:02:38.828  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.828  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.828  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:38.828  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.828  1327  1327 D BluetoothA2dp: Proxy object connected
,09-09 22:02:38.828  1327  1327 D A2dpProfile: Bluetooth service connected
,09-09 22:02:38.828  1430  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.838  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:38.838  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.838  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.838  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.838  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.838  1430  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.838  6968  6968 I BluetoothPbapService: Handler(): got msg=1
09-09 22:02:38.838  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 22:02:38.838  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.838  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:38.838  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 22:02:38.838  1014  1014 D BluetoothA2dp: Proxy object connected
,09-09 22:02:38.838  1014  1137 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:38.838  1430  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.838  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:38.838  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.848  1327  1327 D BluetoothMap: Proxy object connected
09-09 22:02:38.848  1327  1327 D MapProfile: Bluetooth service connected
09-09 22:02:38.848  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.848  1327  1327 D BluetoothMap: getConnectedDevices()
09-09 22:02:38.848  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.848  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-09 22:02:38.848  1430  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.848  6414  6422 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.848  6414  6422 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.848  1178  2721 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:38.848  1178  2721 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.848  2856  2873 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:38.848  2856  2873 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.848  6968  7029 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-09 22:02:38.848  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-09 22:02:38.848  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-09 22:02:38.848  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.848  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.848  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.858  1450  3241 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:38.858  1450  3241 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.858  1327  6453 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.858  1327  6453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:38.858  2856  2856 D BluetoothA2dp: Proxy object connected
,09-09 22:02:38.858  1327  1339 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.858  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:38.858  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.858  6968  7029 D BluetoothSocket: bindListen(): myUserId = 0
09-09 22:02:38.858  6968  7029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:38.868  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.868  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.868  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.868  1327  1327 D HeadsetProfile: Bluetooth service connected
,09-09 22:02:38.868  1327  1339 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.868  6968  7029 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-09 22:02:38.868  6968  7029 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:38.868  6968  7029 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:38.868  6968  7029 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2ae1ae16
,09-09 22:02:38.868  1910  1929 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:38.868  1910  1929 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.868  6968  7029 D BluetoothSocket: channel: 19
09-09 22:02:38.868  6968  7029 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-09 22:02:38.868  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-09 22:02:38.868  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-09 22:02:38.868  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.868  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-09 22:02:38.868  6249  6257 D BluetoothAdapter: onBluetoothStateChange: up=true
09-09 22:02:38.868  6249  6257 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-09 22:02:38.868  1327  6453 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 22:02:38.878  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-09 22:02:38.878  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.878  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.878  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.878  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.878  1327  1327 D BluetoothPbap: Proxy object connected
09-09 22:02:38.878  1327  1327 D PbapServerProfile: Bluetooth service connected
,09-09 22:02:38.878  2856  2929 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.878  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:38.878  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.878  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.888  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.888  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.888  2856  2929 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.888  6968  6976 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 22:02:38.888  1327  6453 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 22:02:38.888  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-09 22:02:38.888  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.888  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.888  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.888  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.888  1327  1338 D Bluetoothsap: onBluetoothStateChange: up=true
,09-09 22:02:38.888  1327  1338 D Bluetoothsap: Binding service...
,09-09 22:02:38.898  1327  1327 D BluetoothInputDevice: Proxy object connected
,09-09 22:02:38.898  1327  1327 D HidProfile: Bluetooth service connected
09-09 22:02:38.898  1327  1338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-09 22:02:38.898  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-09 22:02:38.898  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.898  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.898  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.898  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.898  1327  1338 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-09 22:02:38.898  6968  6978 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-09 22:02:38.898  6968  6978 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-09 22:02:38.898  1014  1043 D BluetoothPan: Binding service...
09-09 22:02:38.898  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan,
09-09 22:02:38.898  1327  6453 D BluetoothPan: Binding service...
09-09 22:02:38.898  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.898  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:38.898  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-09 22:02:38.898  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
09-09 22:02:38.898  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.898  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.898  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-09 22:02:38.908  1327  1327 D Bluetoothsap: BluetoothSAP Proxy object connected
,09-09 22:02:38.908  1327  1327 D SapProfile: Bluetooth service connected
09-09 22:02:38.908  1327  1327 D Bluetoothsap: getConnectedDevices()
,09-09 22:02:38.908  1430  2725 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-09 22:02:38.908  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-09 22:02:38.908  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-09 22:02:38.908  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.908  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:38.908  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:38.908  1430  2725 E BluetoothHeadset: BluetoothHeadset service is binded
,09-09 22:02:38.908  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-09 22:02:38.908  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
09-09 22:02:38.908  1327  1327 D BluetoothPan: BluetoothPAN Proxy object connected
,09-09 22:02:38.908  1327  1327 D PanProfile: Bluetooth service connected
,09-09 22:02:38.908  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:38.908  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-09 22:02:38.908  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-09 22:02:38.918  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,09-09 22:02:38.918  1430  1430 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2429d0c0, true
,09-09 22:02:38.918  1430  1430 D BluetoothHeadset: registerMessageListener
,09-09 22:02:38.918  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:38.918  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-09 22:02:38.918  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-09 22:02:38.928  1178  1178 D BluetoothTile:  getBluetoothState : 12
,09-09 22:02:38.928  1789  1789 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-09 22:02:38.928  1014  2991 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:38.928  1014  1557 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-09 22:02:38.928  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:38.938  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-09 22:02:38.938  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
,09-09 22:02:38.938  1014  3033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:38.938  6968  6987 D HeadsetService: registerMessageListener
,09-09 22:02:38.938  1014  3033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.938  6968  6987 D HeadsetService: registerMessageListener
,09-09 22:02:38.938  6968  6995 D HeadsetStateMachine: Disconnected process message: 70
,09-09 22:02:38.938  6968  6995 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@260397
09-09 22:02:38.938  1430  1430 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-09 22:02:38.938  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-09 22:02:38.948  1014  3033 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:38.948  1014  3033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:38.948  1014  3033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:38.948  1178  1738 D BluetoothTile:  handleUpdatestate:false name:null
09-09 22:02:38.948  1327  1327 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:38.948  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-09 22:02:38.948  1430  1430 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-09 22:02:38.948  1430  1430 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-09 22:02:38.948  1327  1327 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-09 22:02:38.948  1327  1327 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-09 22:02:38.948  1327  1327 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-09 22:02:38.948  1327  1327 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-09 22:02:38.948  6968  7032 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-09 22:02:38.958  6968  6995 D HeadsetStateMachine: Disconnected process message: 9
,09-09 22:02:38.958  6968  6995 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-09 22:02:38.958  1327  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 22:02:38.958  6968  7032 D BluetoothSocket: bindListen(): myUserId = 0
,09-09 22:02:38.968   286   286 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-09 22:02:38.968   286   286 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-09 22:02:38.968  6968  7032 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 22:02:38.968   286   286 V voice   : voice_set_parameters: exit with code(-2)
09-09 22:02:38.968   286   286 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-09 22:02:38.968   286   286 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-09 22:02:38.968   286   286 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-09 22:02:38.968   286   286 V audio_hw_primary: adev_set_parameters: exit
09-09 22:02:38.968  6968  6995 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-09 22:02:38.968  1014  1322 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-09 22:02:38.968  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-09 22:02:38.968  1014  1322 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:38.968  1014  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:38.968  1014  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-09 22:02:38.978  6968  7032 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-09 22:02:38.978  6968  7032 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:38.978  6968  7032 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:38.978  6968  7032 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@311b984
,09-09 22:02:38.978  6968  7032 D BluetoothSocket: channel: 5
,09-09 22:02:38.978  1327  1327 D DockEventReceiver: finishStartingService: stopping service
,09-09 22:02:38.978  1327  1327 D BluetoothNotiBroadcastReceiver: onReceive
,09-09 22:02:38.988  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-09 22:02:38.988  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-09 22:02:38.998  6968  6968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
09-09 22:02:38.998  6968  6968 D BtConfig.SecureMode: isSecureModeOn:false
,09-09 22:02:39.008  1014  1557 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-09 22:02:39.008  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-09 22:02:39.008  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:39.008  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:39.008  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-09 22:02:39.018  1910  1910 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-09 22:02:39.018  1014  3239 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 22:02:39.028  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:39.028  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:39.028  1014  3239 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 22:02:39.028  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:39.038  1910  7038 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-09 22:02:39.038  1014  1558 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-09 22:02:39.038  1910  1910 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-09 22:02:39.048  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:39.048  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:39.048  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:39.048  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:39.058  6968  7042 D BluetoothSocket: bindListen(): myUserId = 0
09-09 22:02:39.058  6968  7042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 22:02:39.058  6968  7042 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-09 22:02:39.058  6968  7042 D BluetoothSocket: bindListen(), new LocalSocket 
09-09 22:02:39.058  6968  7042 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-09 22:02:39.058  6968  7042 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3dd869ee
,09-09 22:02:39.058  6968  7042 D BluetoothSocket: channel: 12
,09-09 22:02:39.058  6968  7042 I BtOppRfcommListener: Accept thread started.
,09-09 22:02:39.068  1014  1558 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 22:02:39.068  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:39.068  1014  1558 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 22:02:39.068  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 22:02:39.078  1910  7038 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-09 22:02:39.088  1014  2729 D SSRM:n  : SIOP:: AP = 330
,09-09 22:02:39.278   291   291 E SMD     : DCD OFF
,09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:39.718  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:39.728  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:39.728  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:39.728  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23da0b31 added. We now have 8 listener(s)
,09-09 22:02:39.728  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:39.728  1014  2991 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 22:02:39.728  1014  2991 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,09-09 22:02:39.728  1014  2991 D SecContentProvider2: mCursor = null
,09-09 22:02:39.738  1014  2991 D WifiService: setWifiEnabled: false pid=6249, uid=10155
,09-09 22:02:39.738  1014  2991 D SettingsProvider: name = wifi_on
,09-09 22:02:39.738  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:39.738  1014  1371 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-09 22:02:39.738  1014  1371 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-09 22:02:39.738  1014  1371 D SecContentProvider2: mCursor = null
,09-09 22:02:39.738  1014  1371 D WifiService: setWifiEnabled: true pid=6249, uid=10155
,09-09 22:02:39.748  1014  1371 W ActivityManager: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-09 22:02:39.748  1014  1371 W WifiService: Failed getting userId using ActivityManagerNative
09-09 22:02:39.748  1014  1371 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6249, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-09 22:02:39.748  1014  1371 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-09 22:02:39.748  1014  1371 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-09 22:02:39.748  1014  1371 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-09 22:02:39.748  1014  1371 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-09 22:02:39.748  1014  1371 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-09 22:02:39.748  1014  1371 D SettingsProvider: name = wifi_on
09-09 22:02:39.748  1014  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-09 22:02:40.108  1014  1041 D Tethering: interfaceAdded wlan0
,09-09 22:02:40.108  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:40.108  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:40.108  1014  1128 E Tethering: No numeric data
,09-09 22:02:40.118  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:40.108  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:40.108  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-09 22:02:40.108  1014  1128 D Tethering: clearTetheredNotification()
09-09 22:02:40.108  1014  1128 D Tethering: InitialState.processMessage what=4
09-09 22:02:40.118  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.118  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:40.118  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:40.118  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-09 22:02:40.118  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:40.118  1014  1122 V NetworkStats: performPollLocked() took 7ms
09-09 22:02:40.118  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.128  1014  1128 E Tethering: No numeric data
,09-09 22:02:40.128  1014  1041 D Tethering: interfaceAdded p2p0
,09-09 22:02:40.128  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-09 22:02:40.128  1014  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-09 22:02:40.128  1014  1128 D Tethering: clearTetheredNotification()
09-09 22:02:40.128  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-09 22:02:40.128  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:40.128  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
09-09 22:02:40.128  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:40.128  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.138  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:40.138  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:40.138  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:40.138  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:40.138  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 22:02:40.138  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:40.138   281   943 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-09 22:02:40.138   281   943 D SoftapController: Softap fwReload - Ok
,09-09 22:02:40.148   281   943 D CommandListener: Setting iface cfg
09-09 22:02:40.148  1014  1122 V NetworkStats: performPollLocked() took 12ms
09-09 22:02:40.148  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-09 22:02:40.148   281   943 D CommandListener: Trying to bring down wlan0
,09-09 22:02:40.148   281   943 D CommandListener: Clearing all IP addresses on wlan0
,09-09 22:02:40.148  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.148  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:40.158  1014  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-09 22:02:40.168  1014  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-09 22:02:40.168  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:40.168  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-09 22:02:40.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:40.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:40.178  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:40.178  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:40.178  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-09 22:02:40.178  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:40.178  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:40.178  1178  1178 D HotspotTile: onReceive : 2, 0
,09-09 22:02:40.178  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:40.178  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:40.188  1014  1558 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:40.188  1014  1558 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:40.188  1014  1558 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:40.188  1014  1558 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:40.188  1014  1558 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:40.188  3679  3679 I Hs20UtilService: Starting #19
,09-09 22:02:40.188  3679  3696 I Hs20UtilService: Message received 5011
09-09 22:02:40.188  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-09 22:02:40.188  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-09 22:02:40.188  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
09-09 22:02:40.188  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:40.208  7054  7054 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-09 22:02:40.208  7054  7054 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-09 22:02:40.218  7054  7054 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-09 22:02:40.228  7054  7054 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-09 22:02:40.228   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7054
09-09 22:02:40.228   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,09-09 22:02:40.228  7054  7054 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-09 22:02:40.228  7054  7054 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:40.228  7054  7054 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-09 22:02:40.228  7054  7054 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-09 22:02:40.228   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7054
09-09 22:02:40.228   383   383 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-09 22:02:40.368   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-09 22:02:40.378  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-09 22:02:40.448  7054  7054 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 22:02:40.448  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 22:02:40.458  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 22:02:40.458   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7054
09-09 22:02:40.458   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,09-09 22:02:40.458  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 22:02:40.458  7054  7054 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:40.458  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:40.458  7054  7054 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:40.458  7054  7054 E wpa_supplicant: SIM READ ERROR,
09-09 22:02:40.458  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:40.458  7054  7054 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:40.458  7054  7054 E wpa_supplicant: SIM READ ERROR
09-09 22:02:40.458  7054  7054 I wpa_supplicant: Blacklist: Clear (all) 
09-09 22:02:40.458  7054  7054 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:40.458  7054  7054 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
09-09 22:02:40.458  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:40.458  7054  7054 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-09 22:02:40.458  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:40.458  7054  7054 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-09 22:02:40.458  7054  7054 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-09 22:02:40.458  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-09 22:02:40.458  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:40.458  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:40.498  7054  7054 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-09 22:02:41.218  7054  7054 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-09 22:02:41.218  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 22:02:41.228  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 22:02:41.228   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7054
09-09 22:02:41.228   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 22:02:41.238  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
,09-09 22:02:41.238  7054  7054 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:41.238  7054  7054 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-09 22:02:41.238  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-09 22:02:41.248  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-09 22:02:41.248   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7054
09-09 22:02:41.248   383   383 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-09 22:02:41.248  7054  7054 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-09 22:02:41.248  7054  7054 I wpa_supplicant: ssSupport state is = 1
09-09 22:02:41.248  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-09 22:02:41.248  7054  7054 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:41.248  7054  7054 E wpa_supplicant: SIM READ ERROR
09-09 22:02:41.248  7054  7054 I wpa_supplicant: wpa_default_ap_write_once
09-09 22:02:41.248  7054  7054 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-09 22:02:41.248  7054  7054 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-09 22:02:41.248  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-09 22:02:41.248  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-09 22:02:41.248  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-09 22:02:41.308  7054  7054 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-09 22:02:41.318  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-09 22:02:41.388  7054  7054 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-09 22:02:41.388  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-09 22:02:41.388  7054  7054 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 22:02:41.398  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-09 22:02:41.398  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-09 22:02:41.398  7054  7054 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-09 22:02:41.398  7054  7054 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-09 22:02:41.398  7054  7054 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-09 22:02:41.398  7054  7054 E wpa_supplicant: SIM READ ERROR
09-09 22:02:41.398  7054  7054 I wpa_supplicant: Blacklist: Clear (all) 
,09-09 22:02:41.418  7054  7054 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-09 22:02:41.428  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
09-09 22:02:41.428  7054  7054 I wpa_supplicant: Skip scan - bUseNetwork false
,09-09 22:02:41.428  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:41.428  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:41.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:41.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:41.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:41.438  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:41.438  1014  1125 D WifiConfigStore: Loading config and enabling all networks 
09-09 22:02:41.438  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-09 22:02:41.438  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-09 22:02:41.438  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:41.438  1178  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-09 22:02:41.438  1178  1178 D HotspotTile: onReceive : 3, 0
,09-09 22:02:41.438  1327  1327 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-09 22:02:41.448  1014  1322 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-09 22:02:41.448  1014  1125 E WifiConfigStore: Not a HS20
,09-09 22:02:41.458  1014  1322 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-09 22:02:41.458  1014  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 22:02:41.458  1014  1322 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:41.458  1014  1322 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 22:02:41.458  1014  1322 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:41.458  6249  6249 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:41.458  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-09 22:02:41.458  1014  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-09 22:02:41.458  7054  7054 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-09 22:02:41.458  7054  7054 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:41.458  7054  7054 I wpa_supplicant: reset timer : RESET_TIMER 0
09-09 22:02:41.458  7054  7054 I wpa_supplicant: P2P: Current p2p state = IDLE
09-09 22:02:41.458  7054  7054 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-09 22:02:41.458  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-09 22:02:41.458  7054  7054 I wpa_supplicant: First Scan Start
,09-09 22:02:41.458  7054  7054 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-09 22:02:41.468  3679  3679 I Hs20UtilService: Starting #20
09-09 22:02:41.468  3679  3696 I Hs20UtilService: Message received 5011
,09-09 22:02:41.468  6249  6249 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:41.468  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-09 22:02:41.468  6515  6515 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-09 22:02:41.468  6515  6515 D SecurityLogAgent: StateMachine : Current State = 1
,09-09 22:02:41.468  1014  1125 D WifiNative-wlan0: Setting external_sim to 1
09-09 22:02:41.468  1014  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-09 22:02:41.468  1014  1125 I WifiNative-HAL: startHal
09-09 22:02:41.468  1014  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9cb6988c
09-09 22:02:41.468  1014  1125 I WifiNative-HAL: Could not start hal
,09-09 22:02:41.468  6515  6515 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-09 22:02:41.478  6490  6490 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 22:02:41.478  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:41.478  1014  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-09 22:02:41.478   281   943 D CommandListener: Setting iface cfg
,09-09 22:02:41.478   281   943 D CommandListener: Trying to bring up p2p0
,09-09 22:02:41.478  1014  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-09 22:02:41.478  1014  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 22:02:41.478  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-09 22:02:41.478  1014  1124 D WifiP2pService: P2pEnablingState
09-09 22:02:41.478  1014  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-09 22:02:41.488  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:41.478  1014  1124 D WifiP2pService: P2p socket connection successful
09-09 22:02:41.488  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:41.478  1014  1124 D WifiP2pService: P2pEnabledState
09-09 22:02:41.488  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 22:02:41.488  1014  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-09 22:02:41.488  1014  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-09 22:02:41.488  1014  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-09 22:02:41.488  1014  1125 E WifiNative-wlan0: invaild command id : 215
09-09 22:02:41.488  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:41.488  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-09 22:02:41.488  1014  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:41.488  1014  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:41.488  1014  1149 I WifiNative-HAL: startHal
09-09 22:02:41.488  7054  7054 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 22:02:41.488  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-09 22:02:41.488  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-09 22:02:41.488  7054  7054 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-09 22:02:41.488  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,09-09 22:02:41.488  1014  1044 D WifiDisplayController: disconnect
09-09 22:02:41.488  1014  1044 D WifiDisplayController: updateConnection
09-09 22:02:41.488  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-09 22:02:41.488  1014  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9dd1b9bc
09-09 22:02:41.488  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:41.488  1014  1149 I WifiNative-HAL: Could not start hal
09-09 22:02:41.488  1014  1149 E WifiScanningService: could not start HAL
09-09 22:02:41.498  7054  7054 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-09 22:02:41.498  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-09 22:02:41.498  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-09 22:02:41.498  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-09 22:02:41.498  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-09 22:02:41.498  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:41.498  1014  1125 D SecContentProvider2: mCursor = null
09-09 22:02:41.498  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-09 22:02:41.498  1014  1322 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 22:02:41.498  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-09 22:02:41.498  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-09 22:02:41.498  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:41.508  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-09 22:02:41.508  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,09-09 22:02:41.508  1014  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-09 22:02:41.508  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:41.508  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:41.508  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-09 22:02:41.508  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:41.508  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:41.508  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:41.508  1014  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
,09-09 22:02:41.508  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  secondary type: null
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  wps: 0
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  grpcapab: 0
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  devcapab: 0
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  status: 3
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  wfdInfo: null
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-09 22:02:41.508  1014  1044 D WifiDisplayController:  SConnectInfo : null
,09-09 22:02:41.518  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:41.518  6455  6455 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-09 22:02:41.518  6455  6455 D FileShare-Client: Outbound.stopDelayTimer - 
,09-09 22:02:41.518  6471  6471 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-09 22:02:41.528  1014  1124 D WifiP2pService: sending p2p persistent groups changed broadcast,
,09-09 22:02:41.528  1014  1124 D WifiP2pService: InactiveState
09-09 22:02:41.528  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-09 22:02:41.528  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:41.528  7054  7054 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-09 22:02:41.528  1014  1124 D WifiP2pService: InactiveState{ what=143376 }
09-09 22:02:41.528  1014  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:41.768  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:41.768  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:41.778  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 22:02:41.778  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 22:02:41.778  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@276547d5 Bundle[{}]
,09-09 22:02:41.778  6249  6301 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 22:02:41.778  6249  6301 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 22:02:41.778  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 22:02:41.788  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 22:02:41.788  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-09 22:02:41.788  6249  6301 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 22:02:41.788  6249  6301 I System.out: Running OutgoingSocketThread
,09-09 22:02:41.798  6249  7062 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1173)
,09-09 22:02:41.798  6249  7062 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50089
,09-09 22:02:41.798  6249  7062 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 22:02:42.278   291   291 E SMD     : DCD OFF
,09-09 22:02:42.678  7054  7054 I wpa_supplicant: nl80211: Received scan results (28 BSSes),
,09-09 22:02:42.678  7054  7054 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-09 22:02:42.688  1014  7060 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
09-09 22:02:42.688  7054  7054 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-09 22:02:42.688  7054  7054 I wpa_supplicant: Trying to associate with  'G700'
,09-09 22:02:42.688  7054  7054 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-09 22:02:42.688  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,09-09 22:02:42.708  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
09-09 22:02:42.708  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:42.798  6249  6301 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1174),
09-09 22:02:42.798  6249  6301 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1174)
09-09 22:02:42.798  6249  6301 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
09-09 22:02:42.798  6249  6301 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...,
09-09 22:02:42.798  6249  6301 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1180)
09-09 22:02:42.798  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:42.798  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25e216 added. We now have 2 listener(s),
,09-09 22:02:42.808  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 22:02:42.808  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:42.808  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 22:02:42.808  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:42.808  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a082797 added. We now have 9 listener(s)
09-09 22:02:42.808  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:42.808  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:42.808  7054  7054 E wpa_supplicant: Cmd 35605 not handled
,09-09 22:02:42.818  7054  7054 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-09 22:02:42.818  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-09 22:02:42.818  7054  7054 I wpa_supplicant: Associated with F4.99.3E
09-09 22:02:42.818  7054  7054 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:42.818  7054  7054 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-09 22:02:42.818  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-09 22:02:42.818  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:42.818  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-09 22:02:42.818  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:42.818  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-09 22:02:42.818  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-09 22:02:42.828  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:42.828  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:42.828  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:42.828  1014  1128 E Tethering: No numeric data
09-09 22:02:42.828  1014  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-09 22:02:42.828  1014  1128 D Tethering: clearTetheredNotification()
,09-09 22:02:42.828  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:42.828  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:42.828  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-09 22:02:42.828  1178  1178 D HotspotTile: updateTetherState():false, false
,09-09 22:02:42.838  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:42.838  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:42.838  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:42.838  1014  1122 V NetworkStats: performPollLocked() took 8ms
09-09 22:02:42.838  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:42.838  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:42.838  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:42.838  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:42.838  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:42.848  7054  7054 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-09 22:02:42.848  7054  7054 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-09 22:02:42.848  7054  7054 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-09 22:02:42.848  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:42.848  7054  7054 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-09 22:02:42.848  7054  7054 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-09 22:02:42.848  7054  7054 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-09 22:02:42.848  7054  7054 I wpa_supplicant: Blacklist: Clear (temp) 
09-09 22:02:42.848  7054  7054 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-09 22:02:42.848  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:42.848  1014  1125 D SecContentProvider2: mCursor = null
09-09 22:02:42.848  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-09 22:02:42.848  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-09 22:02:42.848  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-09 22:02:42.848  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:42.848  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:42.848  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:42.848  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3493296d added. We now have 3 listener(s)
,09-09 22:02:42.858  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:42.858  1014  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-09 22:02:42.858  1014  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-09 22:02:42.858  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:42.868  1014  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-09 22:02:42.868  1014  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-09 22:02:42.868  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:42.868  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:42.868  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:42.868  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309609a2 added. We now have 10 listener(s)
09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:42.868  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:42.868  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:42.868  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 22:02:42.868  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:42.868  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:42.868  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:42.868  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25e216 removed from the list
09-09 22:02:42.868  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:42.868  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a082797 removed from the list
09-09 22:02:42.868  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:42.868  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:42.868  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-09 22:02:42.878  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:42.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.878  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:42.878  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 22:02:42.878  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:42.878  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:42.878  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 22:02:42.878  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:42.878  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:42.878  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a082797 not in the list
,09-09 22:02:42.878  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:42.888  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:42.888  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:42.888  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:42.888  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
,09-09 22:02:42.888  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:42.888  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-09 22:02:42.888  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:42.888  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:42.888  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:42.888  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@309609a2 removed from the list
,09-09 22:02:42.888  1014  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 22:02:42.888  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:42.888  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:42.888  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:42.888  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:42.888  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3493296d removed from the list
,09-09 22:02:42.888  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-09 22:02:42.888  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:42.888  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:42.888  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1da633 added. We now have 2 listener(s)
09-09 22:02:42.888  3679  3679 I Hs20UtilService: Starting #21
09-09 22:02:42.888  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:42.898  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-09 22:02:42.898  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-09 22:02:42.898  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-09 22:02:42.898  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 22:02:42.898  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:42.898  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:42.898  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:42.898  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb57df0 added. We now have 9 listener(s)
09-09 22:02:42.898  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:42.898  1327  1327 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-09 22:02:42.898  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 22:02:42.898  1327  3057 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-09 22:02:42.908   281   943 D CommandListener: Setting iface cfg
,09-09 22:02:42.908  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:42.918  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:42.918  1014  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,09-09 22:02:42.918  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 22:02:42.918  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:42.918  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:42.918  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ef1dee added. We now have 3 listener(s)
,09-09 22:02:42.918  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:42.918  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:42.918  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:42.918  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 22:02:42.918  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:42.918  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:42.918  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:42.918  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1902728f added. We now have 10 listener(s)
09-09 22:02:42.918  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:42.918  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:42.918  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:42.918  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:42.918  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:42.918  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:42.928  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:42.928  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:42.928  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:42.928  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.928  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.928  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:42.928  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:42.928  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:42.928  1014  1125 E WifiNative-wlan0: do suspend false
,09-09 22:02:42.938  1014  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-09 22:02:42.938  1014  1125 D SecContentProvider2: mCursor = null
,09-09 22:02:42.938  1014  1124 D WifiP2pService: InactiveState{ what=143375 }
09-09 22:02:42.938  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:42.938  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:42.938  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:42.938  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:42.938  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-09 22:02:42.938  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:42.948  6968  6987 D BtGatt.GattService: registerClient() - UUID=bfca9268-3490-4b5e-9253-fe0cfcb7f947
,09-09 22:02:42.988  6968  6986 D BtGatt.GattService: onClientRegistered() - UUID=bfca9268-3490-4b5e-9253-fe0cfcb7f947, clientIf=6
,09-09 22:02:42.988  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:42.988  6968  7031 D BtGatt.GattService: start scan with filters
,09-09 22:02:42.998  6968  6991 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:42.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:42.998  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:42.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:42.998  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:42.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:42.998  6968  6991 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@16f5bb65
,09-09 22:02:42.998  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:42.998  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:43.008  6968  6986 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-09 22:02:43.008  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.008  6968  6991 D BtGatt.ScanManager: allow scan with filters
,09-09 22:02:43.008  6968  6991 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-09 22:02:43.008  6968  6991 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-09 22:02:43.008  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 22:02:43.018  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-09 22:02:43.018  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.018  6968  6991 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:43.018  6968  6991 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-09 22:02:43.018  6249  6301 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
09-09 22:02:43.018  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:43.018  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 22:02:43.018  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.018  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:43.018  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 22:02:43.018  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 22:02:43.018  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:43.018  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 22:02:43.018  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:43.018  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:43.018  6968  6986 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-09 22:02:43.018  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.028  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 22:02:43.028  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.028  6968  6976 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:43.038  6968  6978 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:43.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:43.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:43.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:43.038  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:43.038  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:43.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:43.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:43.048  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:43.048  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:43.048  6968  6991 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 82,
,09-09 22:02:43.058  6968  6991 D BtGatt.ScanManager: filter size is 1
09-09 22:02:43.058  6968  6991 D BtGatt.ScanManager: delete FilterIndex - 3,
,09-09 22:02:43.058  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-09 22:02:43.058  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.068  6968  6991 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:43.068  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-09 22:02:43.068  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.068  6968  6991 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:43.068  6968  6986 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:43.068  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.148  7071  7071 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-09 22:02:43.148  7071  7071 I dhcpcd  : version 5.5.6 starting
,09-09 22:02:43.158  7071  7071 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-09 22:02:43.198  7071  7071 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-09 22:02:43.198  7071  7071 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-09 22:02:43.198  7071  7071 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-09 22:02:43.198  7071  7071 I dhcpcd  : bssid match
09-09 22:02:43.198  7071  7071 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-09 22:02:43.208  1014  1371 I art     : Explicit concurrent mark sweep GC freed 57030(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 28MB/42MB, paused 2.740ms total 174.925ms
,09-09 22:02:43.208  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:43.218  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.218  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.218  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:43.218  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:43.218  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:43.218  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.218  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.218  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c1da633 removed from the list
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb57df0 removed from the list
09-09 22:02:43.218  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:43.218  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:43.218  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.218  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.218  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fb57df0 not in the list
09-09 22:02:43.218  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.218  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1902728f removed from the list
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.218  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.218  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.218  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ef1dee removed from the list
,09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:43.218  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bda8ab added. We now have 2 listener(s)
,09-09 22:02:43.228  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 22:02:43.228  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:43.228  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.228  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:43.228  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4671b08 added. We now have 9 listener(s)
09-09 22:02:43.228  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:43.228  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:43.228  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:43.228  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:43.238  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,09-09 22:02:43.238  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-09 22:02:43.238  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-09 22:02:43.238  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1378fcc6 added. We now have 3 listener(s)
09-09 22:02:43.238  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:43.248  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:43.248  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-09 22:02:43.248  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:43.248  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.248  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:43.248  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eac2487 added. We now have 10 listener(s)
09-09 22:02:43.248  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-09 22:02:43.248  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 22:02:43.248  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:43.248  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:43.248  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 22:02:43.248  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:43.248  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:43.248  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:43.258  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 22:02:43.258  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 22:02:43.258  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 22:02:43.258  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 22:02:43.258  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:43.258  6968  7030 D BtGatt.GattService: registerClient() - UUID=e38ea27f-9ff9-45fb-9c78-18b06c4eb632
,09-09 22:02:43.278  7071  7071 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-09 22:02:43.298  6968  6986 D BtGatt.GattService: onClientRegistered() - UUID=e38ea27f-9ff9-45fb-9c78-18b06c4eb632, clientIf=6
,09-09 22:02:43.308  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-09 22:02:43.308  6968  7031 D BtGatt.GattService: start scan with filters
,09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:43.308  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:43.308  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:43.308  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:43.308  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:43.308  6968  6986 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-09 22:02:43.308  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: allow scan with filters,
09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-09 22:02:43.308  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:43.308  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:43.308  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: Starting BLE batch scan
09-09 22:02:43.308  6968  6991 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-09 22:02:43.308  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:43.318  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 22:02:43.318  6968  6986 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:43.318  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.318  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-09 22:02:43.318  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-09 22:02:43.318  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.328  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 22:02:43.328  6249  6301 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 22:02:43.338  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:43.338  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:43.338  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 22:02:43.338  6968  6991 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 83
09-09 22:02:43.338  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 22:02:43.338  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@17bda8ab removed from the list
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:43.338  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4671b08 removed from the list
,09-09 22:02:43.338  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:43.338  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 22:02:43.338  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 22:02:43.338  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4671b08 not in the list
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:43.338  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:43.338  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:43.338  6968  7030 D BtGatt.GattService: stopScan() - queue size =1
,09-09 22:02:43.338  6968  7031 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:43.348  7071  7071 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
09-09 22:02:43.348  6968  6991 D BtGatt.ScanManager: filter size is 1
09-09 22:02:43.348  6968  6991 D BtGatt.ScanManager: delete FilterIndex - 4
,09-09 22:02:43.348  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 22:02:43.348  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 22:02:43.348  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 22:02:43.348  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 22:02:43.348  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:43.348  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:43.348  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.348  6968  6991 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:43.348  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 22:02:43.348  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:43.358  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.358  6968  6991 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-09 22:02:43.358  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:43.358  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 22:02:43.358  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:43.358  6968  6986 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-09 22:02:43.358  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:43.358  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.358  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.358  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.358  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2eac2487 removed from the list
09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.358  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:43.358  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.358  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.358  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1378fcc6 removed from the list
09-09 22:02:43.358  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 22:02:43.358  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331c8223 added. We now have 2 listener(s)
,09-09 22:02:43.368  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-09 22:02:43.368  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 22:02:43.368  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.368  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 22:02:43.368  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cdc4320 added. We now have 9 listener(s)
09-09 22:02:43.368  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:43.368  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:43.378  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:43.378  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:43.378  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:43.378  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 22:02:43.378  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:43.378  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d4de9e added. We now have 3 listener(s)
,09-09 22:02:43.388  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:43.388  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 22:02:43.388  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
,09-09 22:02:43.388  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:43.388  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.388  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:43.388  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ab1d7f added. We now have 10 listener(s)
,09-09 22:02:43.388  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:43.388  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:43.388  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 22:02:43.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 22:02:43.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 22:02:43.388  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 22:02:43.388  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 22:02:43.398  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 22:02:43.398  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,09-09 22:02:43.408  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 22:02:43.408  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 22:02:43.408  6249  6301 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 22:02:43.408  6968  6978 D BtGatt.GattService: registerClient() - UUID=979ef201-7c02-48ab-8a02-7d4897d7a53e
,09-09 22:02:43.448  6968  6986 D BtGatt.GattService: onClientRegistered() - UUID=979ef201-7c02-48ab-8a02-7d4897d7a53e, clientIf=6,
09-09 22:02:43.448  6249  6257 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-09 22:02:43.458  6968  6976 D BtGatt.GattService: start scan with filters
,09-09 22:02:43.458  6968  6991 D BtGatt.ScanManager: handling starting scan
,09-09 22:02:43.458  6968  6986 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-09 22:02:43.458  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.458  6968  6991 D BtGatt.ScanManager: allow scan with filters
09-09 22:02:43.458  6968  6991 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-09 22:02:43.458  6968  6991 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6,
,09-09 22:02:43.458  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 22:02:43.458  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 22:02:43.458  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 22:02:43.458  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 22:02:43.468  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-09 22:02:43.468  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.468  6968  6991 D BtGatt.ScanManager: Starting BLE batch scan,
09-09 22:02:43.468  6968  6991 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-09 22:02:43.468  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 22:02:43.468  6968  6986 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-09 22:02:43.468  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 22:02:43.468  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 22:02:43.468  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.468  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-09 22:02:43.468  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.468  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 22:02:43.478  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:43.478  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:43.478  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:43.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.478  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 22:02:43.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.478  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331c8223 removed from the list
09-09 22:02:43.478  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.478  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cdc4320 removed from the list
09-09 22:02:43.478  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop
09-09 22:02:43.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:43.478  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
09-09 22:02:43.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-09 22:02:43.478  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.478  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 22:02:43.488  6968  6991 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 84
,09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.488  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cdc4320 not in the list
09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-09 22:02:43.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 22:02:43.488  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 22:02:43.488  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 22:02:43.498  6968  7030 D BtGatt.GattService: stopScan() - queue size =1,
,09-09 22:02:43.498  6968  6987 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 22:02:43.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 22:02:43.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 22:02:43.498  6968  6991 D BtGatt.ScanManager: filter size is 1
09-09 22:02:43.498  6968  6991 D BtGatt.ScanManager: delete FilterIndex - 5
,09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:43.498  6968  6986 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-09 22:02:43.498  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.498  6968  6991 D BtGatt.ScanManager: stopping BLe Batch
,09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 22:02:43.498  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 22:02:43.498  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.508  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.508  6249  6249 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 22:02:43.508  6249  6249 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36ab1d7f removed from the list
,09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.508  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4d4de9e removed from the list
,09-09 22:02:43.508  6968  6986 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-09 22:02:43.508  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5e129b added. We now have 2 listener(s)
,09-09 22:02:43.508  6968  6991 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-09 22:02:43.508  6968  6986 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-09 22:02:43.508  6968  6986 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-09 22:02:43.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 22:02:43.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:43.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:43.508  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169b5638 added. We now have 9 listener(s)
09-09 22:02:43.508  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 22:02:43.508  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 22:02:43.518  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 22:02:43.518  6249  6301 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 22:02:43.528  6249  6301 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 22:02:43.528  6249  6301 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 22:02:43.528  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 22:02:43.528  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae02376 added. We now have 3 listener(s)
,09-09 22:02:43.538  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 22:02:43.538  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 22:02:43.538  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f813d77 added. We now have 10 listener(s)
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 22:02:43.538  6249  6301 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 22:02:43.538  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 22:02:43.538  6249  6301 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.538  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5e129b removed from the list
09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.538  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169b5638 removed from the list
,09-09 22:02:43.538  6249  6249 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 22:02:43.538  6249  6301 D io.jxcore.node.ConnectivityMonitor: stop,
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 22:02:43.538  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 22:02:43.538  6249  6301 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@169b5638 not in the list
09-09 22:02:43.538  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.538  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-09 22:02:43.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-09 22:02:43.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 22:02:43.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-09 22:02:43.548  6249  6301 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f813d77 removed from the list
09-09 22:02:43.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 22:02:43.548  6249  6301 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 22:02:43.548  6249  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-09 22:02:43.548  6249  6301 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 22:02:43.548  6249  6301 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae02376 removed from the list
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 22:02:43.548  6249  6301 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 22:02:43.558  6249  7100 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1187, name: My test thread name)
,09-09 22:02:43.558  6249  7100 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1187, thread name: My test thread name)
09-09 22:02:43.558  6249  7100 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 22:02:43.568  6249  7101 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1189, name: My test thread name)
,09-09 22:02:43.568  6249  7101 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1189, thread name: My test thread name)
09-09 22:02:43.568  6249  7101 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-09 22:02:43.578  6249  6301 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-09 22:02:43.578  6249  6301 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-09 22:02:43.578  6249  6301 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-09 22:02:43.578  6249  6301 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-09 22:02:43.578  6249  6301 D com.test.thalitest.ThaliTestRunner: Total duration: 24582 ms
,09-09 22:02:43.578  6249  6301 I jxcore-log: *Native tests were executed*
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.578  6249  6301 I jxcore-log: Total number of executed tests:  80
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.578  6249  6301 I jxcore-log: Number of passed tests:  80
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.578  6249  6301 I jxcore-log: Number of failed tests:  0
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.578  6249  6301 I jxcore-log: Number of ignored tests:  0
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.578  6249  6301 I jxcore-log: Total duration:  24582
09-09 22:02:43.578  6249  6301 I jxcore-log: 
,09-09 22:02:43.588  6249  6301 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-09 22:02:43.588  6249  6301 I jxcore-log: 
,09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
09-09 22:02:43.598  6249  6249 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
,09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
,09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
,09-09 22:02:43.598  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.598  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
09-09 22:02:43.608  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
,09-09 22:02:43.608  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.608  6249  6301 I jxcore-log: 
09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
,09-09 22:02:43.618  6249  6301 I jxcore-log: 
09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.618  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 22:02:43.618  6249  6301 I jxcore-log: 
,09-09 22:02:43.718  6249  6249 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 22:02:43.718  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:43.718  6249  6301 I jxcore-log: 
,09-09 22:02:43.748  1014  1125 E WifiNative-wlan0: do suspend true
,09-09 22:02:43.778  1014  1124 D WifiP2pService: InactiveState{ what=143375 },
09-09 22:02:43.778  1014  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-09 22:02:43.778  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:43.778  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:43.778  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.788  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.788  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.788  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:43.788  1014  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-09 22:02:43.788  1014  1125 E WifiStateMachine: VerifyingLinkState enter
,09-09 22:02:43.788  1014  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-09 22:02:43.788  1014  1127 E ConnectivityService: updateNetworkInfo()
,09-09 22:02:43.788  1014  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-09 22:02:43.788  1014  1127 D ConnectivityService: Adding iface wlan0 to network 504
,09-09 22:02:43.798  1014  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
09-09 22:02:43.798  1014  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:43.798  1014  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:43.798  1014  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:43.798  1014  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-09 22:02:43.808  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:43.808  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-09 22:02:43.808  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.808  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:43.808  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.808  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:43.808  1014  1371 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:43.808  1014  1371 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:43.808  1014  1371 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:43.808  1014  1371 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:43.808  1014  1371 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:43.808  3679  3679 I Hs20UtilService: Starting #22
,09-09 22:02:43.808  3679  3696 I Hs20UtilService: Message received 5007
,09-09 22:02:43.818  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:43.818  1327  1327 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 22:02:43.828  1014  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-09 22:02:43.838  1014  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504,
09-09 22:02:43.838  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,09-09 22:02:43.838  1014  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-09 22:02:43.838  1014  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-09 22:02:43.838  1014  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0,
09-09 22:02:43.838  1014  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-09 22:02:43.838  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:43.838  1014  1127 D ConnectivityService: LTETest block dns file not exists
,09-09 22:02:43.838  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-09 22:02:43.838  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.848  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.848  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.848  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.848  1014  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-09 22:02:43.848  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:43.848  1014  1127 E ConnectivityService: updateNetworkInfo()
09-09 22:02:43.848  1014  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-09 22:02:43.848  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 22:02:43.848  1014  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-09 22:02:43.848  1014  7064 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:43.848  1014  7064 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-09 22:02:43.848  1014  7064 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-09 22:02:43.848  1014  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-09 22:02:43.848  1014  7064 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-09 22:02:43.848  1014  7064 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 22:02:43.848  1014  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-09 22:02:43.848  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-09 22:02:43.848  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-09 22:02:43.848  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
09-09 22:02:43.848   281   939 D EnterpriseController: uids 1000
09-09 22:02:43.848   281   939 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-09 22:02:43.848   281   939 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-09 22:02:43.848  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-09 22:02:43.858  1014  1127 D ConnectivityService:    accepting network in place of null,
09-09 22:02:43.858  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-09 22:02:43.858  1450  1450 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-09 22:02:43.858  1014  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true,
09-09 22:02:43.858  1014  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-09 22:02:43.858  1014  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-09 22:02:43.858  1014  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-09 22:02:43.858  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-09 22:02:43.858  6249  6249 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-09 22:02:43.858  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:43.858  6249  6301 I jxcore-log: 
,09-09 22:02:43.868  1014  3233 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:43.868  1014  3233 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:43.868  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:43.868  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 22:02:43.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.868  1014  3233 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:43.868  1014  3233 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:43.868  1014  3233 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:43.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.868  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:43.868  3679  3679 I Hs20UtilService: Starting #23
09-09 22:02:43.868  1014  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-09 22:02:43.868  1014  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-09 22:02:43.878  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-09 22:02:43.878  1014  1128 D Tethering: MasterInitialState.processMessage what=3
,09-09 22:02:43.878  3679  3696 I Hs20UtilService: Message received 5007
09-09 22:02:43.878  1014  1122 V NetworkStats: updateIfacesLocked()
09-09 22:02:43.878  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.878  1014  1122 V NetworkStats: performPollLocked(flags=0x1)
09-09 22:02:43.878  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-09 22:02:43.878  1178  1712 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-09 22:02:43.878  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:43.878  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-09 22:02:43.878  3839  6307 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-09 22:02:43.888  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:43.888  1014  1122 V NetworkStats: performPollLocked() took 6ms
09-09 22:02:43.888  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.888  1014  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.888  1327  1327 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:43.888  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-09 22:02:43.888  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
09-09 22:02:43.888  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-09 22:02:43.888  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-09 22:02:43.888  1178  1178 D StatusBar.NetworkController: updateDataNetType()
09-09 22:02:43.888  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-09 22:02:43.888  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:43.888  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:43.888  7103  7103 D AndroidRuntime: 
09-09 22:02:43.888  7103  7103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 22:02:43.888  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-09 22:02:43.888  1327  1327 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-09 22:02:43.888  1327  1327 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 22:02:43.898  7103  7103 D AndroidRuntime: CheckJNI is OFF
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-09 22:02:43.898  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-09 22:02:43.898  7103  7103 D AndroidRuntime: readGMSProperty: start
09-09 22:02:43.898  7103  7103 D AndroidRuntime: readGMSProperty: already setted!!
09-09 22:02:43.898  7103  7103 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 22:02:43.898  7103  7103 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 22:02:43.898  7103  7103 D AndroidRuntime: readGMSProperty: end
09-09 22:02:43.898  7103  7103 D AndroidRuntime: addProductProperty: start
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-09 22:02:43.898  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-09 22:02:43.898  1014  1557 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-09 22:02:43.898  1014  1557 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-09 22:02:43.898  1014  1557 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:43.898  1014  1557 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:43.898  1014  1557 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-09 22:02:43.908  3679  3679 I Hs20UtilService: Starting #24
,09-09 22:02:43.908  3679  3696 I Hs20UtilService: Message received 5007
09-09 22:02:43.908  1327  1327 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-09 22:02:43.908  1327  1327 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-09 22:02:43.908  1014  1472 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-09 22:02:43.918  1014  3239 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-09 22:02:43.918  1014  3239 D SecContentProvider2: mCursor = null
09-09 22:02:43.918  1014  3233 D SecContentProvider2: uri = 15 selection = getToastGravity
09-09 22:02:43.918  1014  3233 D SecContentProvider2: mCursor = null
,09-09 22:02:43.918  1014  1137 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset,
09-09 22:02:43.918  1014  1137 D SecContentProvider2: mCursor = null
09-09 22:02:43.918  1014  1345 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
09-09 22:02:43.918  1014  1345 D SecContentProvider2: mCursor = null,
,09-09 22:02:43.918  1014  1557 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-09 22:02:43.918  1014  1557 D SecContentProvider2: mCursor = null
09-09 22:02:43.918  1014  1026 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
09-09 22:02:43.918  1014  1026 D SecContentProvider2: mCursor = null
,09-09 22:02:43.948   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast,
,09-09 22:02:43.958  1014  1371 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014,
,09-09 22:02:43.968  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 22:02:44.008  6249  6249 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 22:02:44.008  6249  6301 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 22:02:44.008  6249  6301 I jxcore-log: 
,09-09 22:02:44.038  1014  1046 I PowerManagerService: [PWL] Off : 75s ago
,09-09 22:02:44.038  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-09 22:02:44.038  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-09 22:02:44.038  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=24175)
,09-09 22:02:44.048  7103  7103 E AffinityControl: AffinityControl: registerfunction enter
,09-09 22:02:44.088  7103  7103 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 22:02:44.098  1014  3240 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 22:02:44.098  1014  3240 D PackageManager: START PACKAGE DELETE: observer{1020633542}
09-09 22:02:44.098  1014  3240 D PackageManager: pkg{<packageName>}
09-09 22:02:44.098  1014  3240 D PackageManager: user{0}
09-09 22:02:44.098  1014  3240 D PackageManager: caller{2000}
,09-09 22:02:44.098  1014  3240 D PackageManager: flags{2}
09-09 22:02:44.098  1014  3240 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,09-09 22:02:44.098  1014  3240 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 22:02:44.098  1014  3240 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
09-09 22:02:44.098  1014  3240 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
09-09 22:02:44.098  1014  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 22:02:44.098  1014  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-09 22:02:44.098  1014  1053 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-09 22:02:44.098  1014  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 22:02:44.098  1014  1053 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 22:02:44.098  1014  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 22:02:44.108  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg,
09-09 22:02:44.108  1014  1039 I ActivityManager: Killing 6249:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg,
,09-09 22:02:44.118  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{1163981e u0 com.test.thalitest/.MainActivity t128}
,09-09 22:02:44.118  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,09-09 22:02:44.218   257   443 I SurfaceFlinger: id=14 Removed NainActivit (6/9),
09-09 22:02:44.218  1014  1472 I WindowState: WIN DEATH: Window{ea17d7e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 22:02:44.218   257  1095 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-09 22:02:44.218  1014  1472 D InputDispatcher: Focus left window: 6249
,09-09 22:02:44.238  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 22:02:44.238  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:44.238  1014  1053 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-09 22:02:44.238  1014  1053 I ActivityManager:   Force finishing activity ActivityRecord{1163981e u0 com.test.thalitest/.MainActivity t128 f}
,09-09 22:02:44.238  1014  1053 W ActivityManager: Duplicate finish request for ActivityRecord{1163981e u0 com.test.thalitest/.MainActivity t128 f}
,09-09 22:02:44.258  1014  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 22:02:44.268  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-09 22:02:44.268  1014  1039 D InputDispatcher: Focused application released
,09-09 22:02:44.288  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-09 22:02:44.298  5692  5692 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 683us total 30.981ms
,09-09 22:02:44.298  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 22:02:44.298  5792  5792 I art     : Explicit concurrent mark sweep GC freed 108(16KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 663us total 43.323ms
,09-09 22:02:44.298  1014  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 22:02:44.308  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-09 22:02:44.308  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-09 22:02:44.308  1910  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 22:02:44.308  1789  1789 E SamsungIME: mOCRHelper is null
,09-09 22:02:44.308  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-09 22:02:44.338  1014  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
,09-09 22:02:44.338  1014  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-09 22:02:44.338  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:44.338  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-09 22:02:44.338  1014  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 22:02:44.348  1014  1122 V NetworkStats: performPollLocked() took 9ms
09-09 22:02:44.348  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:44.358  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:44.358  3839  3839 I art     : Explicit concurrent mark sweep GC freed 23287(1397KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 15MB/20MB, paused 1.325ms total 117.994ms
,09-09 22:02:44.358  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-09 22:02:44.368  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-09 22:02:44.368  3697  3697 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 22:02:44 GMT+02:00 2016
,09-09 22:02:44.368  1014  2991 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-09 22:02:44.368  1014  2991 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 22:02:44.368  1014  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:44.368  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-09 22:02:44.388  1014  2991 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:44.388  1014  2991 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:44.388  1014  2991 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 22:02:44.398  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-09 22:02:44.408  3697  3697 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-09 22:02:44.408  1014  1492 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-09 22:02:44.408  1014  1492 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 22:02:44.418  3697  3697 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-09 22:02:44.428  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 22:02:44.428  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 22:02:44.428  1014  2992 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-09 22:02:44.428  1014  2992 D SecContentProvider2: mCursor = null
,09-09 22:02:44.438  3697  3697 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 22:02:44.438  3697  3697 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 22:02:44.448  1014  3233 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-09 22:02:44.448  1014  3233 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-09 22:02:44.448  1014  1492 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 22:02:44.458  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.458  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.458  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.458  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
09-09 22:02:44.458  1014  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.458  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-09 22:02:44.468  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
09-09 22:02:44.468  7121  7121 I libpersona: KNOX_SDCARD checking this for 10094
09-09 22:02:44.468  7121  7121 E Zygote  : MountEmulatedStorage()
09-09 22:02:44.468  7121  7121 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:44.468  7121  7121 E Zygote  : v2
09-09 22:02:44.468  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
09-09 22:02:44.468  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
09-09 22:02:44.468  7121  7121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:44.478  6549  6549 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-09 22:02:44.478  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
09-09 22:02:44.478  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-09 22:02:44.478  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 22:02:44.478  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
09-09 22:02:44.478  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-09 22:02:44.478  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 22:02:44.478  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
09-09 22:02:44.478  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-09 22:02:44.478  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 22:02:44.478  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
09-09 22:02:44.488  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created,
,09-09 22:02:44.488  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
09-09 22:02:44.478  7121  7121 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.498  7121  7121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.498  1014  1492 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7121 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-09 22:02:44.498  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
09-09 22:02:44.498  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
09-09 22:02:44.498  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
09-09 22:02:44.498  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.498  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.498  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.498  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.508  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-09 22:02:44.508  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 22:02:44.508  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 22:02:44.518  7134  7134 E Zygote  : MountEmulatedStorage()
09-09 22:02:44.518  7134  7134 I libpersona: KNOX_SDCARD checking this for 10044
09-09 22:02:44.518  7134  7134 E Zygote  : v2
09-09 22:02:44.518  7134  7134 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:44.518  7134  7134 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:44.528  7134  7134 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.528  7134  7134 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.538  7121  7121 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:44.538  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7134 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-09 22:02:44.538  7121  7121 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.538  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
09-09 22:02:44.538  1014  1038 W TextServicesManagerService: no available spell checker services found
09-09 22:02:44.538  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 22:02:44.548  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 22:02:44.548  7134  7134 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:44.548  7134  7134 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.548  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
09-09 22:02:44.548  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 22:02:44.548  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-09 22:02:44.548  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 22:02:44.548  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-09 22:02:44.558  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
09-09 22:02:44.558  1014  2729 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-09 22:02:44.558  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 22:02:44.558  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 22:02:44.558  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 22:02:44.558  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 22:02:44.558  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 22:02:44.568  1014  1053 I art     : Explicit concurrent mark sweep GC freed 39236(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/42MB, paused 10.856ms total 294.429ms
,09-09 22:02:44.568  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-09 22:02:44.578  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 22:02:44.578  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 22:02:44.578  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.578  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.578  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.578  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.588  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.598  7152  7152 E Zygote  : MountEmulatedStorage()
09-09 22:02:44.598  7152  7152 I libpersona: KNOX_SDCARD checking this for 10149
09-09 22:02:44.598  7152  7152 E Zygote  : v2
09-09 22:02:44.598  7152  7152 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:44.598  7152  7152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:44.598  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7152 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:44.598  1014  3033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 22:02:44.598  1014  3033 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 22:02:44.598  1014  3033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-09 22:02:44.598  3697  7120 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
09-09 22:02:44.598  7152  7152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.598  7152  7152 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.598  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-09 22:02:44.598  1014  1053 D PackageManager: delete codoeFile: 
,09-09 22:02:44.608  3697  7120 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-09 22:02:44.608  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-09 22:02:44.628  3697  3697 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-09 22:02:44.628   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 22:02:44.628  7134  7134 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 22:02:44.628  1014  1053 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-09 22:02:44.628  1014  1053 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
09-09 22:02:44.628  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 22:02:44.638  1014  1472 D InputDispatcher: Focus entered window: 3178
,09-09 22:02:44.638  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-09 22:02:44.638  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 22:02:44.638  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.638  7121  7121 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 22:02:44.648  1014  1053 D PackageManager: result of delete: 1{1020633542}
,09-09 22:02:44.648  3178  3178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-09 22:02:44.648  7121  7121 D elm:15183: ELMEngine.ELMEngine( context ).
,09-09 22:02:44.648  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.648  7103  7103 D AndroidRuntime: Shutting down VM
,09-09 22:02:44.658  7121  7121 D elm:15183: MDMBridge.setEnterpriseBridge()
09-09 22:02:44.658  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-09 22:02:44.658  1014  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-09 22:02:44.658  1014  3239 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-09 22:02:44.658  7152  7152 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:44.658  7152  7152 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.658  1014  3239 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-09 22:02:44.658  1014  3239 W ActivityManager: userId = 0, bbcId = -10000
,09-09 22:02:44.658  1014  3239 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:44.658  1014  3239 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-09 22:02:44.668  3178  3178 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-09 22:02:44.668  3178  3178 V ActivityThread: updateVisibility : ActivityRecord{1ae39c59 token=android.os.BinderProxy@145049e4 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-09 22:02:44.668  1014  1558 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 22:02:44.668  7121  7121 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 22:02:44.668  1014  1558 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6249 uid 10155
,09-09 22:02:44.678  1014  7169 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 22:02:44.678  1014  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 22:02:44.678  1014  1053 D PackageManager: userId{-1}
09-09 22:02:44.678  1014  1053 D PackageManager: andCode{true}
09-09 22:02:44.678  7121  7121 D elm:15183: ElmAgentService : onCreate()
,09-09 22:02:44.678  7121  7168 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 22:02:44.678  7121  7168 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-09 22:02:44.688  3391  3391 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-09 22:02:44.688  3391  3391 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-09 22:02:44.688  3391  3391 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,09-09 22:02:44.688  3391  3391 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,09-09 22:02:44.688  3391  3391 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 22:02:44.688  3391  3391 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 22:02:44.688  3391  3391 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
,09-09 22:02:44.698  1789  1789 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 22:02:44.698  5792  7151 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-09 22:02:44.698  3178  3178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@145049e4 time:154618
,09-09 22:02:44.708  3391  3391 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,09-09 22:02:44.708  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 22:02:44.708  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-09 22:02:44.708  3391  3391 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:44.708  1178  1178 D PanelView: There is/are notification(s) 
,09-09 22:02:44.708  1014  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 22:02:44.708  3391  3391 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,09-09 22:02:44.718  3391  3391 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,09-09 22:02:44.718  3391  3391 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-09 22:02:44.718  3391  3391 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
,09-09 22:02:44.718  3391  3391 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:44.718  1178  1178 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-09 22:02:44.718  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
09-09 22:02:44.718  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:44.718  1178  1178 D PanelView: There is/are notification(s) 
,09-09 22:02:44.718  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
09-09 22:02:44.718  7121  7168 D elm:15183: MDMBridge.getInstance()
09-09 22:02:44.718  7121  7168 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 22:02:44.718  1178  1178 D PersonaManager: isKioskContainerExistOnDevice
09-09 22:02:44.718  1178  1178 D PanelView: There is/are notification(s) 
09-09 22:02:44.718  1178  1178 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-09 22:02:44.728  7121  7168 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 22:02:44.728  5792  5792 I art     : Explicit concurrent mark sweep GC freed 500(29KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 800us total 68.081ms
,09-09 22:02:44.748  1014  1044 W ActivityManager: mDVFSHelper.release()
,09-09 22:02:44.748  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14563be1 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:154662
,09-09 22:02:44.758  6532  6532 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 22:02:44.758  6532  6532 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 22:02:44.758  6532  6532 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 22:02:44.758  6532  6532 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 22:02:44.758  7121  7121 D elm:15183: ElmAgentService : onDestroy().
,09-09 22:02:44.768  1014  1371 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 22:02:44.768  7152  7152 D ThemeInfoUtil: getCurrentFestivalName is [null]
09-09 22:02:44.768  7152  7152 D ThemeInfoUtil: isCurrentFestival = false
,09-09 22:02:44.768  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.768  1014  1137 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-09 22:02:44.768  1014  1137 D SecContentProvider2: mCursor = null
,09-09 22:02:44.768  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.768  5963  5985 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-09 22:02:44.768  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.768  5963  5985 D BadgeProvider: sendNotify, [notify] : null
09-09 22:02:44.768  5963  5985 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-09 22:02:44.768  5963  5985 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-09 22:02:44.768  5963  5985 D BadgeProvider: update, [UpdateCount] : 1
09-09 22:02:44.768  6968  6984 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-09 22:02:44.768  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.788  7174  7174 E Zygote  : MountEmulatedStorage()
,09-09 22:02:44.788  7174  7174 E Zygote  : v2
09-09 22:02:44.788  7174  7174 I libpersona: KNOX_SDCARD checking this for 10032
,09-09 22:02:44.788  7174  7174 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:44.788  1178  1178 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-09 22:02:44.788  7174  7174 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-09 22:02:44.788  1014  1371 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7174 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-09 22:02:44.798  7174  7174 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-09 22:02:44.798  7174  7174 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.808  1014  1371 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,09-09 22:02:44.808  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.808  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.808  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.808  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.818  7187  7187 E Zygote  : MountEmulatedStorage()
,09-09 22:02:44.818  7187  7187 E Zygote  : v2
,09-09 22:02:44.818  7187  7187 I libpersona: KNOX_SDCARD checking this for 10152
09-09 22:02:44.818  7187  7187 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:44.828  7187  7187 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:44.828  1014  1371 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7187 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
09-09 22:02:44.828  1014  1371 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-09 22:02:44.828  7187  7187 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.828  7187  7187 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.828  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.828  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.828  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.828  1014  1371 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.838  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 22:02:44.838  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:44.838  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.848  1014  1371 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-09 22:02:44.848  7174  7174 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 22:02:44.848  7174  7174 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.858  1014  1371 I ActivityManager: Killing 6185:com.google.android.gms:car/u0a12 (adj 15): empty #31
09-09 22:02:44.858  7198  7198 E Zygote  : MountEmulatedStorage()
09-09 22:02:44.858  7198  7198 I libpersona: KNOX_SDCARD checking this for 1000
09-09 22:02:44.858  7198  7198 E Zygote  : v2
09-09 22:02:44.858  7198  7198 I libpersona: KNOX_SDCARD not a persona
09-09 22:02:44.858  7103  7103 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 22:02:44.858  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:44.868  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.868  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.878  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.878  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:44.878  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 22:02:44.878  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:44.878  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:44.878  1014  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-09 22:02:44.888  7187  7187 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:44.888  7187  7187 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.898  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.898  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:44.898  7198  7198 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:44.908  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.908  7134  7134 D NearbySource: Nearby Source Create!
09-09 22:02:44.908  7134  7134 D NearbyContext: Nearby Context Create!
,09-09 22:02:44.908  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:44.908  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:44.918  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.918  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.918  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:44.918  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 22:02:44.918  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 22:02:44.928  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 22:02:44.938  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 22:02:44.938  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 22:02:44.938  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-09 22:02:44.948  7187  7187 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
,09-09 22:02:44.948  1014  1492 D PersonaManager: isKioskContainerExistOnDevice
,09-09 22:02:44.948  7187  7187 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:44.948  7187  7187 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:44.948  7187  7187 D AndroidRuntime: Shutting down, VM
09-09 22:02:44.948  7187  7187 E AndroidRuntime: FATAL EXCEPTION: main
09-09 22:02:44.948  7187  7187 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 7187
09-09 22:02:44.948  7187  7187 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
,09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
09-09 22:02:44.948  7187  7187 E AndroidRuntime: ,	... 11 more
09-09 22:02:44.958  7174  7221 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-09 22:02:44.958  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 22:02:44.968  5877  5877 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
09-09 22:02:44.968  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 22:02:44.968  5877  5877 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 22:02:44.968  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.968  5877  5877 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:44.968  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:44.968  7134  7134 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-09 22:02:44.968  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:44.968  7134  7134 D SLinkSource: Samsung link source created
09-09 22:02:44.968   256   546 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 22:02:44.968   256   546 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 22:02:44.988  7223  7223 E Zygote  : MountEmulatedStorage()
09-09 22:02:44.988  7223  7223 E Zygote  : v2
09-09 22:02:44.988  7223  7223 I libpersona: KNOX_SDCARD checking this for 10035
09-09 22:02:44.988  7223  7223 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:44.988  1014  1026 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7223 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 22:02:44.988  1014  1026 I ActivityManager: Killing 5612:com.android.vending/u0a28 (adj 15): empty #31
,09-09 22:02:44.988  7223  7223 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:44.988  1014  3239 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.shootingmodeprovider
,09-09 22:02:44.998  7223  7223 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-09 22:02:44.998  7223  7223 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 22:02:44.998  7174  7221 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
09-09 22:02:44.998  7198  7198 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 22:02:44.998  1014  1492 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 22:02:44.998  1014  1492 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 22:02:45.008  1014  1492 W ActivityManager: userId = 0, bbcId = -10000
09-09 22:02:45.008  1014  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 22:02:45.008  1014  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 22:02:45.018  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-09 22:02:45.018  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.018  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.018  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.018  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 22:02:45.018  1014  7229 E DropBoxManagerService: Can't write: system_app_crash
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop201.tmp: open failed: EROFS (Read-only file system)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 22:02:45.018  1014  7229 E DropBoxManagerService: 	... 5 more
,09-09 22:02:45.028  7223  7223 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 22:02:45.028  7174  7221 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 22:02:45.028  7223  7223 D ActivityThread: Added TimaKeyStore provider
,09-09 22:02:45.028  7241  7241 E Zygote  : MountEmulatedStorage()
09-09 22:02:45.028  7241  7241 I libpersona: KNOX_SDCARD checking this for 10156
09-09 22:02:45.028  7241  7241 E Zygote  : v2
09-09 22:02:45.028  7241  7241 I libpersona: KNOX_SDCARD not a persona
,09-09 22:02:45.028  7241  7241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-09 22:02:45.038  7198  7238 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,09-09 22:02:45.038  7241  7241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:45.038  7198  7238 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 22:02:45.038  7198  7238 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteDatabas,e.open(SQLiteDatabase.java:878)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 22:02:45.038  7198  7238 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-09 22:02:45.038  7198  7238 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 22:02:45.038  7198  7238 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 22:02:45.038  7241  7241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 22:02:45.038  1014  1039 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7241 uid=10156 gids={50156, 9997} abi=armeabi-v7a
09-09 22:02:45.038  7187  7187 I Process : Sending signal. PID: 7187 SIG: 9
09-09 22:02:45.038  1014  1558 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 22:02:45.038  7134  7134 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
09-09 22:02:45.038  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.038  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.038  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 22:02:45.038  1014  1558 E ActivityManager: checkUser: useridlist=null, currentuser=0

```
