#### Test 81492074ffbc155_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main,
08-16 17:43:26.110   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 17:43:26.110   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-16 17:43:26.370  6271  6271 D AndroidRuntime: 
08-16 17:43:26.370  6271  6271 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:43:26.370  6271  6271 D AndroidRuntime: CheckJNI is OFF
08-16 17:43:26.370  6271  6271 D AndroidRuntime: readGMSProperty: start
08-16 17:43:26.370  6271  6271 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:43:26.370  6271  6271 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:43:26.370  6271  6271 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:43:26.370  6271  6271 D AndroidRuntime: readGMSProperty: end
08-16 17:43:26.370  6271  6271 D AndroidRuntime: addProductProperty: start
08-16 17:43:26.400   286   286 E SMD     : DCD OFF
08-16 17:43:26.510  6271  6271 E AffinityControl: AffinityControl: registerfunction enter
08-16 17:43:26.540  6271  6271 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 17:43:26.550  1017  1029 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:43:26.550  1017  1029 I PersonaManagerService: PersonaId don't exist
08-16 17:43:26.550  1017  1029 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 17:43:26.550  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-16 17:43:26.570  1017  1029 W ActivityManager: mDVFSHelper.acquire()
08-16 17:43:26.580  1017  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:43:26.580  1017  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 17:43:26.580  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:26.580  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:26.580  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:26.580  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:26.600  6282  6282 E Zygote  : MountEmulatedStorage()
08-16 17:43:26.600  6282  6282 E Zygote  : v2
08-16 17:43:26.600  6282  6282 I libpersona: KNOX_SDCARD checking this for 10155
08-16 17:43:26.600  6282  6282 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:26.600  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:43:26.600  1017  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 17:43:26.600   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 17:43:26.600  1017  1029 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6282 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:43:26.600  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 17:43:26.600  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:43:26.600  6282  6282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:43:26.610  6282  6282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:43:26.610  6282  6282 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 17:43:26.630  1017  1029 D InputDispatcher: Focused application set to: xxxx
08-16 17:43:26.630  1017  1029 D InputDispatcher: Focus left window: 3189
08-16 17:43:26.630  6271  6271 D AndroidRuntime: Shutting down VM
08-16 17:43:26.630  6282  6282 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:26.630  6282  6282 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:26.640  1017  1017 V ActivityManager: Display changed displayId=0
08-16 17:43:26.650  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 17:43:26.660  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:43:26.660  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:43:26.670  1017  3104 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:43:26.710   256  1097 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-16 17:43:26.710   256   448 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-16 17:43:26.720  3189  3189 V ActivityThread: updateVisibility : ActivityRecord{33f01446 token=android.os.BinderProxy@36900f95 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-16 17:43:26.780  6282  6282 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-16 17:43:26.790  6282  6282 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 267-268)
08-16 17:43:26.790  6282  6282 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:43:26.820  6282  6282 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1fbadce2}
08-16 17:43:26.820  6282  6282 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:43:26.820  6282  6282 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:43:26.840  6271  6271 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:43:26.860  6282  6282 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 17:43:26.860  6282  6282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:43:26.860  6282  6282 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 17:43:26.880  6282  6282 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-16 17:43:26.880  6282  6282 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-16 17:43:26.880  6282  6282 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-16 17:43:26.890  6282  6282 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:26.890  6282  6282 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:26.890  6282  6282 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:26.890  6282  6282 I Adreno-EGL: Local Branch: 
08-16 17:43:26.890  6282  6282 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:26.890  6282  6282 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:26.890  6282  6282 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
08-16 17:43:27.020  6282  6309 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-16 17:43:27.070  6282  6282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:43:27.080  6282  6282 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 17:43:27.090  6282  6282 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:43:27.090  6282  6282 D PhoneWindow: *FMB* installDecor flags : -2139027200
08-16 17:43:27.100  6282  6282 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-16 17:43:27.100  6282  6282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:43:27.100  6282  6282 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 17:43:27.140  6282  6322 D OpenGLRenderer: Render dirty regions requested: true
08-16 17:43:27.150  1017  1217 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:43:27.150  1017  1217 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:43:27.150  1017  1217 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:43:27.150  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:43:27.150  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 17:43:27.160  6282  6282 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:43:27.160  6282  6282 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 17:43:27.170   256   256 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
08-16 17:43:27.190  1017  1509 D InputDispatcher: Focus entered window: 6282
08-16 17:43:27.190  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:43:27.190  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:43:27.190  6282  6282 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 17:43:27.190  6282  6322 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 17:43:27.200  6282  6322 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-16 17:43:27.200  6282  6322 D OpenGLRenderer: Enabling debug mode 0
08-16 17:43:27.250  6282  6282 V ActivityThread: updateVisibility : ActivityRecord{6f605d5 token=android.os.BinderProxy@25fd83bf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:43:27.270  1017  1217 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 17:43:27.270  1175  1175 D PanelView: There is/are notification(s) 
08-16 17:43:27.270  1017  6325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 17:43:27.280  1786  1786 I SamsungIME: getCurrentCandidateView
08-16 17:43:27.290  1017  1047 I ActivityManager: Displayed Component not be shown by security: +614ms (total +704ms)
08-16 17:43:27.290  1017  1047 W ActivityManager: mDVFSHelper.release()
08-16 17:43:27.290  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6fc512c u0 com.test.thalitest/.MainActivity t128} time:110761
08-16 17:43:27.290  6282  6282 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-16 17:43:27.290  6282  6282 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25fd83bf time:110766
08-16 17:43:27.290   256  1097 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
08-16 17:43:27.290   256   452 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
08-16 17:43:27.350  1786  1786 D SamsungIME: Dismiss ExpandCandiate
08-16 17:43:27.360  6282  6282 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6282
08-16 17:43:27.480  6282  6282 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-16 17:43:27.490  1786  1786 I SamsungIME: getDebugLevel  : 0x4f4c
08-16 17:43:27.520  1786  1786 I SamsungIME: getDebugLevel  : 0x4f4c
08-16 17:43:27.540  1786  1786 I SamsungIME: KeybaordView init() : load resources
08-16 17:43:27.570  1786  1786 I SamsungIME: getCurrentKeyboard
08-16 17:43:27.570  1786  1786 I SamsungIME: getTextKeyboard
08-16 17:43:27.580  1786  1786 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-16 17:43:27.590  6282  6327 D jxcore_app_log: JniHelper::setJavaVM(0xb835a328), pthread_self() = -1198794144
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 17:43:27.600  6282  6327 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8050e45 added. We now have 1 listener(s)
08-16 17:43:27.610  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
08-16 17:43:27.610  6282  6327 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:43:27.610  6282  6327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:27.610  6282  6327 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 17:43:27.630  6282  6327 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2eaa8 added. We now have 1 listener(s)
08-16 17:43:27.630  6282  6327 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:27.630  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:43:27.630  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 17:43:27.630  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:43:27.630  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:43:27.630  6282  6327 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 17:43:27.640  6282  6327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:27.640  6282  6327 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
08-16 17:43:27.650  6282  6327 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:27.650  6282  6327 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:27.650  6282  6327 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:43:27.650  6282  6327 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:27.650  6282  6327 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 17:43:27.650  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:27.650  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:27.690  6282  6282 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:43:28.120  6282  6335 W jxcore-log: Initializing JXcore engine
08-16 17:43:28.120  6282  6335 W jxcore-log: JXcore engine is ready
,08-16 17:43:28.120  1786  6330 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 17:43:28.170  1896  1896 E audit   : type=1400 msg=audit(1471362208.170:205): avc:  denied  { ioctl } for  pid=6335 comm="Thread-1088" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 17:43:28.170  1896  1896 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:43:28.170  1896  1896 E audit   : type=1300 msg=audit(1471362208.170:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8808f8 items=0 ppid=311 ppcomm=main pid=6335 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1088" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 17:43:28.170  1896  1896 E audit   : type=1320 msg=audit(1471362208.170:205): 
,08-16 17:43:28.180  6282  6335 W jxcore-log: Starting JXcore engine
,08-16 17:43:28.290  6282  6335 W jxcore-log: Platform android,
08-16 17:43:28.290  6282  6335 W jxcore-log: 
08-16 17:43:28.290  6282  6335 W jxcore-log: Process ARCH arm
08-16 17:43:28.290  6282  6335 W jxcore-log: 
,08-16 17:43:28.470  6282  6335 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:43:28.470  6282  6335 I jxcore-log: 
,08-16 17:43:28.470  6282  6335 W jxcore-log: JXcore engine is started
,08-16 17:43:28.480  6282  6327 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:43:28.480  6282  6282 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:43:29.400   286   286 E SMD     : DCD OFF,
,08-16 17:43:31.100   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:31.900  5454  5454 D FactoryTest: Not factory mode
,08-16 17:43:31.900  5454  5454 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 17:43:31.900  5454  5454 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-16 17:43:31.900  5454  5454 D MTPRx   : still no open session command from host, so toast
,08-16 17:43:31.900  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-16 17:43:31.900  5454  5454 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115376
08-16 17:43:31.900  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-16 17:43:31.900  1017  1481 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:43:31.900  1017  1481 I PersonaManagerService: PersonaId don't exist
08-16 17:43:31.900  1017  1481 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-16 17:43:31.910  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-16 17:43:31.910  1017  1481 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:31.910  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:31.910  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 17:43:31.910  1017  1481 W ActivityManager: mDVFSHelper.acquire()
,08-16 17:43:31.920  1017  1481 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:43:31.930  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:43:31.930  1017  1481 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:43:31.930  1017  1481 D InputDispatcher: Focused application set to: xxxx
,08-16 17:43:31.930  1017  1481 D InputDispatcher: Focus left window: 6282
,08-16 17:43:31.930  5454  5454 E MTPRx   : started activity for popup
,08-16 17:43:31.940  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:43:31.940  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:43:31.970  5454  5454 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:31.990  5454  5454 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 17:43:31.990  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:43:31.990  1017  1029 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:43:31.990  1017  1029 D InputDispatcher: Focused application set to: xxxx
,08-16 17:43:31.990  1017  1029 D InputDispatcher: Focus entered window: 6282
,08-16 17:43:31.990  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:43:32.000  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:43:32.000  1017  1481 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:43:32.000  1017  1481 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1ed981af attribute=null, token = android.os.BinderProxy@156a6abf
,08-16 17:43:32.030  5454  5454 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-16 17:43:32.040  5454  5454 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 17:43:32.040  5454  5454 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 17:43:32.060  6282  6282 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:43:32.060  6282  6282 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-16 17:43:32.060  6282  6282 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:43:32.060  6282  6282 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 17:43:32.070  1017  1509 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:43:32.070  1017  1509 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:43:32.070  1017  1509 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:43:32.070  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:43:32.070  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:43:32.080  6282  6282 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:43:32.080  6282  6282 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:43:32.080  6282  6282 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c184292 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3908982e, 16908290=android.view.AbsSavedState$1@3908982e}, android:focusedViewId=100}]}]
08-16 17:43:32.080  6282  6282 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 17:43:32.080  6282  6282 V ActivityThread: updateVisibility : ActivityRecord{6f605d5 token=android.os.BinderProxy@25fd83bf {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:43:32.080  6282  6282 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:43:32.080  6282  6282 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:43:32.080  6282  6282 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25fd83bf time:115557
,08-16 17:43:32.090  1017  1562 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:43:32.100   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:32.410   286   286 E SMD     : DCD OFF
,08-16 17:43:32.590  1017  1292 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:32.590  1017  1292 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4175, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 17:43:32.590  1017  1292 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-16 17:43:32.590  1017  1292 D BatteryService: stay LED for charging
08-16 17:43:32.590  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:32.590  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:32.590  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:43:32.590  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:43:32.600  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,08-16 17:43:32.600  1017  1017 I MotionRecognitionService: Plugged
08-16 17:43:32.600  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:32.610  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-16 17:43:32.610  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:32.620  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:43:32.620  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:43:32.620  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:43:33.100   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:33.420  1017  2765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:43:34.100   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:34.910  1017  1042 W ActivityManager: mDVFSHelper.release()
,08-16 17:43:35.100   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:43:35.410   286   286 E SMD     : DCD OFF,
,08-16 17:43:35.420  1017  2730 D SSRM:n  : SIOP:: AP = 320,
,08-16 17:43:36.100   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-16 17:43:36.530  1017  1095 V AlarmManager: waitForAlarm result :4,
,08-16 17:43:36.530  1017  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.560  1936  1936 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 17:43:36.590  1017  1805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:36.590  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.590  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:36.590  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:36.590  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:36.630  1017  1057 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-16 17:43:36.650  3772  3772 D ConnectivityManager: CallingUid : 10012, CallingPid : 3772
,08-16 17:43:36.650  1017  1804 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:43:36.660  1017  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-16 17:43:36.660  1017  1130 D ConnectivityService: apparently satisfied.  currentScore=60
,08-16 17:43:36.660  1017  1130 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-16 17:43:36.660  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:43:36.710  3772  6345 W DriveInitializer: Background init thread started
,08-16 17:43:36.730   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 17:43:36.730   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:36.740  3772  6345 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 17:43:36.790  1017  1562 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:36.790  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.HeartbeatAlarm$ConnectionInfoPersistService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.790  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:36.790  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:36.790  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:36.830  1017  3103 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:36.830  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.830  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:36.830  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:36.830  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:36.840  3772  6345 W DriveInitializer: Background init thread ended
,08-16 17:43:36.860  3772  4239 D NetworkUsageDbReporter: Started reporting usage
,08-16 17:43:36.870  1017  1509 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:43:36.870  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-16 17:43:36.870  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:36.870  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:36.870  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.080  1017  1562 I art     : Explicit concurrent mark sweep GC freed 57419(3MB) AllocSpace objects, 28(674KB) LOS objects, 33% free, 27MB/41MB, paused 2.480ms total 158.603ms
,08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1198
,08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1010
,08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 6311
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1008
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1381
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1005
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10562
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1004
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 109746
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1002
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 84827
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1001
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 346117
08-16 17:43:37.110  3772  4239 D NetworkUsageDbReporter: keeping row: 1000
,08-16 17:43:37.120  3772  4239 D NetworkUsageDbReporter: Finished reporting usage.
,08-16 17:43:37.200  1017  1805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.200  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.200  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.200  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.200  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.220  1017  1804 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-16 17:43:37.220  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.240  1017  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.240  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.240  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.240  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.240  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.270  1936  1936 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:43:37.270  3772  6357 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-16 17:43:37.270  3772  6357 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 17:43:37.310  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.310  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.310  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.370  1017  1562 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.370  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.370  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.370  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.370  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.400  1017  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:37.400  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.400  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.400  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:37.400  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.450  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.450  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.450  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.450  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.510  1017  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.520  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.520  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:37.520  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.560  1017  3103 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.560  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.560  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.560  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.570  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.570  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:37.570  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.570  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:37.580  6362  6362 E Zygote  : MountEmulatedStorage()
,08-16 17:43:37.580  6362  6362 E Zygote  : v2
08-16 17:43:37.580  6362  6362 I libpersona: KNOX_SDCARD checking this for 10012
08-16 17:43:37.580  6362  6362 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:37.580  1017  3103 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6362 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 17:43:37.590  6362  6362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:43:37.590  6362  6362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:37.590  6362  6362 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:37.610  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:37.610  6362  6362 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:37.630  6362  6362 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 17:43:37.630  6362  6362 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:43:37.670  6362  6362 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 17:43:37.670  6362  6362 I MultiDex: install
08-16 17:43:37.670  6362  6362 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 17:43:37.710  6362  6362 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 17:43:37.750  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-16 17:43:37.760  1017  1095 V AlarmManager: waitForAlarm result :4
,08-16 17:43:37.770  1017  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.770  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.770  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.770  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.770  6362  6362 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:43:37.770  6362  6362 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3887cd9f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 17:43:37.780  6362  6362 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 17:43:37.780  1017  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.780  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:37.780  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.780  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.800  6362  6362 D ChimeraCfgMgr: Reading stored module config
,08-16 17:43:37.820  1936  1936 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=ea41963a-6a10-408a-b186-06ca8d7e8e00
,08-16 17:43:37.900  1936  2120 I art     : Explicit concurrent mark sweep GC freed 65703(3MB) AllocSpace objects, 9(384KB) LOS objects, 39% free, 14MB/23MB, paused 1.622ms total 94.894ms
,08-16 17:43:37.910  6362  6382 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 17:43:37.920  1017  1219 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 17:43:37.920  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:43:37.920  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.920  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:37.920  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:37.930  1936  1936 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:43:37.930  1936  1936 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:43:37.930  6362  6362 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 17:43:37.930  6362  6362 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 17:43:37.950  1017  3103 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:37.950  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:37.950  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:37.950  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.030   281   281 D WVCdm   : Instantiating CDM.
,08-16 17:43:38.030   281   733 I WVCdm   : CdmEngine::OpenSession
,08-16 17:43:38.030   281   733 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 17:43:38.060   281   733 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 17:43:38.080   281   733 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,08-16 17:43:38.080   281   733 D DrmWidevineDash: Service_Initialize: starts!
08-16 17:43:38.080   281   733 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 17:43:38.080   281   733 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 17:43:38.080   281   733 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
,08-16 17:43:38.080   281   733 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 17:43:38.080   281   733 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 17:43:38.080   281   733 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 17:43:38.080   281   733 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-16 17:43:38.080   281   733 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 17:43:38.080   281   733 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-16 17:43:38.090   281   733 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 17:43:38.110   281   733 D QSEECOMAPI: : Loaded image: APP id = 11
,08-16 17:43:38.110   281   733 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-16 17:43:38.120   281   733 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-16 17:43:38.120   281   733 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-16 17:43:38.120   281   733 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1631000
08-16 17:43:38.120   281   733 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1631000
,08-16 17:43:38.120   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.120   431   442 D DrmLibTime: got the req here! ret=0
08-16 17:43:38.120   431   442 D DrmLibTime: command id, time_cmd_id = 770
08-16 17:43:38.120   431   442 D DrmLibTime: time_getutcsec starts!
08-16 17:43:38.120   431   442 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-16 17:43:38.120   431   442 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-16 17:43:38.120   431   442 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-16 17:43:38.120   431   442 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-16 17:43:38.120   431   442 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-16 17:43:38.120   431   442 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-16 17:43:38.120   431   442 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-16 17:43:38.120   431   442 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-16 17:43:38.120   328   556 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 17:43:38.120   328  6386 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-16 17:43:38.120   328  6386 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
,08-16 17:43:38.130   328  6386 D QC-time-services: offset is: 0 for base: 0
,08-16 17:43:38.130   431   442 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-16 17:43:38.130   431   442 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-16 17:43:38.130   431   442 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471362218,
08-16 17:43:38.130   431   442 D DrmLibTime: time_getutcsec returns 0, sec = 1471362218; nsec = 0
08-16 17:43:38.130   431   442 D DrmLibTime: time_getutcsec finished! 
08-16 17:43:38.130   431   442 D DrmLibTime: iotcl_continue_command finished! and return 0 
,08-16 17:43:38.130   431   442 D DrmLibTime: before calling ioctl to read the next time_cmd
08-16 17:43:38.130   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 17:43:38.130   328   556 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-16 17:43:38.150   281   733 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
08-16 17:43:38.150   281   733 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 17:43:38.150   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.150   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.150   281   733 D DrmWidevineDash: hlos api version =  9
08-16 17:43:38.150  1655  4284 I art     : Explicit concurrent mark sweep GC freed 1373(46KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 729us total 22.162ms
08-16 17:43:38.150   281   733 D DrmWidevineDash: tz api version =  9
08-16 17:43:38.150   281   733 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 17:43:38.150   281   733 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-16 17:43:38.150   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.160  6362  6372 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-16 17:43:38.160  6362  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:38.160  6362  6372 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 17:43:38.160  6362  6372 I System.out: (HTTPLog)-Thread-1068-193527792: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 17:43:38.160  6362  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:38.170   276   967 D EnterpriseController: uids 10012
08-16 17:43:38.170   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:43:38.170   276   967 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:43:38.170   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-16 17:43:38.170   281   733 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1757960
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-16 17:43:38.170   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.170   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb8adaf20, dataLength=8
08-16 17:43:38.170   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.170   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.170   281   733 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-16 17:43:38.180   281   733 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb8aa6880, wrapped_rsa_key_length=1280
08-16 17:43:38.180   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.180   281   733 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.180   281   733 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-16 17:43:38.180   281   733 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 17:43:38.180   281   732 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-16 17:43:38.180   281   732 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-16 17:43:38.180   281   732 I WVCdm   : CdmEngine::GenerateKeyRequest
08-16 17:43:38.180   281   732 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb8ad9ed8, idLength=0xb1857730
08-16 17:43:38.180   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1857746, maximum = 0xb1857747
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: hlos api version =  9
08-16 17:43:38.200   281   732 D DrmWidevineDash: tz api version =  9
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb18577b4
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-16 17:43:38.200   281   732 D WVCdm   : PrepareKeyRequest: nonce=3820858622
08-16 17:43:38.200   281   732 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb8aa7d08
08-16 17:43:38.200   281   732 D DrmWidevineDash: message_length=1599, signature=0xb8aa8998, signature_length=0xb1857714
08-16 17:43:38.200   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.220  6362  6372 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 17:43:38.220  6362  6372 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6362, getuid(): 10012
08-16 17:43:38.240  1936  2113 W GCoreFlp: No location to return for getLastLocation()
,08-16 17:43:38.280  1017  1562 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.280  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.280  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.280  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.280  1017  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.280  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.280  1017  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:38.280  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.290  1017  1514 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.290  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.290  1017  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.290  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.310  1936  2119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:43:38.320  3772  6358 D UdcContextInitService: registered all accounts: true
,08-16 17:43:38.320  1936  2135 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-16 17:43:38.350   281   732 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.350   281   732 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-16 17:43:38.360   281   281 I WVCdm   : CdmEngine::CloseSession
08-16 17:43:38.360   281   281 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-16 17:43:38.360   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:43:38.360   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.360   281   281 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-16 17:43:38.360   281   281 I WVCdm   : L3 Terminate.
08-16 17:43:38.360   281   281 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-16 17:43:38.360   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:43:38.360   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:43:38.360   281   281 D DrmWidevineDash: Service_Uninitialize: starts!
08-16 17:43:38.360   281   281 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-16 17:43:38.360   281   281 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-16 17:43:38.360   281   281 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-16 17:43:38.360   281   281 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-16 17:43:38.410   286   286 E SMD     : DCD OFF
,08-16 17:43:38.440  1017  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:38.440  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-16 17:43:38.450  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.450  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.450  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.490  1017  4314 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:43:38.490  6362  6372 I qtaguid : Untagging socket 33
08-16 17:43:38.490  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:43:38.490  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.490  1017  4314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.490  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.570  1017  4314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.570  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.570  1017  4314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:38.570  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.600  1017  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.610  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.610  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.610  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.650  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.650  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.650  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.650  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.650  1936  6395 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:43:38.650  1936  6393 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 17:43:38.650  1017  1562 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.650  1017  1562 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:43:38.650  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.650  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.680  1017  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.680  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.680  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.680  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.680  1936  6395 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:43:38.680  1936  6393 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 17:43:38.680  1017  4314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.680  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:38.680  1017  4314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.680  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.710  1017  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:38.710  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.710  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.710  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.710  1936  6395 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:43:38.710  1936  6393 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-16 17:43:38.710  1936  6393 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-16 17:43:38.720  1936  6393 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 17:43:38.760  1017  4314 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:43:38.800  1017  1804 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:43:38.800  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 17:43:38.800  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:38.800  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:38.800  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:38.800  1936  6393 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:38.810   276   967 D EnterpriseController: uids 10012
08-16 17:43:38.810   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:43:38.810   276   967 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:43:38.810  1936  6393 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:43:38.810  1936  6393 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:38.860  1936  6393 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:38.880  6399  6399 I dex2oat : ----------------------------------------------------
08-16 17:43:38.880  6399  6399 I dex2oat : <SS>: S T A R T I N G . . .
08-16 17:43:38.880  6399  6399 I dex2oat : <SS>: Zip is absent. Canceled.
,08-16 17:43:38.880  6399  6399 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 17:43:38.930  6399  6399 I dex2oat : dex2oat took 43.657ms (threads: 4)
,08-16 17:43:38.940  6362  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:38.940  6362  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:38.940  6362  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:38.940  6362  6372 I Adreno-EGL: Local Branch: 
08-16 17:43:38.940  6362  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:38.940  6362  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:38.940  6362  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:43:39.020  6362  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:39.020  6362  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:39.020  6362  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:39.020  6362  6372 I Adreno-EGL: Local Branch: 
08-16 17:43:39.020  6362  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:39.020  6362  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:39.020  6362  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:43:39.130  1017  1217 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:43:39.140  1936  6393 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:39.140  1936  6393 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:39.240  6362  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:39.240  6362  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:39.240  6362  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:39.240  6362  6372 I Adreno-EGL: Local Branch: 
08-16 17:43:39.240  6362  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:39.240  6362  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:39.240  6362  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:43:39.260  1017  1029 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 17:43:39.270  1936  6393 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:43:39.270  1936  6393 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:39.400  1017  1292 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:43:39.400  1936  6393 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:39.400  1936  6393 I qtaguid : Tagging socket 73 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:39.500  1936  6360 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:39.510   276   967 D EnterpriseController: uids 10012
08-16 17:43:39.510   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:43:39.510   276   967 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:43:39.510  1936  6360 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:43:39.510  1936  6360 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1936, getuid(): 10012
,08-16 17:43:39.530  1017  1292 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:43:39.540  1936  6393 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:39.540  1936  6393 I qtaguid : Tagging socket 73 with tag 1106583100000000{285628465,0} for uid -1, pid: 1936, getuid(): 10012
,08-16 17:43:39.550  1936  6360 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1936, getuid(): 10012
,08-16 17:43:39.700  1936  2135 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 17:43:39.700  1936  2135 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-16 17:43:39.700  1936  2135 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-16 17:43:38.406+0200, stopTime=2016-08-16 17:43:39.712+0200, duration=1306ms
,08-16 17:43:39.720  1936  6411 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:39.720   276   967 D EnterpriseController: uids 10012
,08-16 17:43:39.720   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:43:39.720   276   967 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:43:39.730  1936  6411 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-16 17:43:39.730  1936  6411 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1936, getuid(): 10012
,08-16 17:43:39.760  1936  6411 I qtaguid : Tagging socket 67 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1936, getuid(): 10012
,08-16 17:43:39.780  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-16 17:43:39.980  1936  6411 I qtaguid : Untagging socket 72
,08-16 17:43:39.980  1936  2135 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-16 17:43:41.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:41.410   286   286 E SMD     : DCD OFF,
,08-16 17:43:41.510  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-16 17:43:41.510  6282  6335 I jxcore-log: 
,08-16 17:43:41.510  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-16 17:43:41.510  6282  6335 I jxcore-log: 
,08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:41.520  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:41.520  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:41.520  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:43:41.520  6282  6335 I jxcore-log: 
08-16 17:43:41.520  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:43:41.520  6282  6335 I jxcore-log: 
,08-16 17:43:41.850  1936  6408 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:43:41.850  1936  6408 I qtaguid : Tagging socket 72 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1936, getuid(): 10012
,08-16 17:43:41.970  6282  6335 D ExecuteNativeTests: Running unit tests,
,08-16 17:43:42.070  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:43:42.070  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf added. We now have 2 listener(s)
,08-16 17:43:42.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:43:42.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:42.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:43:42.070  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:42.070  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c added. We now have 2 listener(s)
08-16 17:43:42.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:43:42.070  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:43:42.070  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.070  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:42.080  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:42.080  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:42.080  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:43:42.080  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:42.080  6282  6335 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 17:43:42.080  6282  6335 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:42.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:43:42.080  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.080  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.080  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.080  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:42.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf removed from the list
08-16 17:43:42.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.080  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c removed from the list
08-16 17:43:42.080  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.090  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.090  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.090  6282  6335 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:43:42.090  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.090  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.090  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.090  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.090  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.090  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.090  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.090  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.090  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.090  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.090  1936  6408 I qtaguid : Untagging socket 72
08-16 17:43:42.100  1936  2135 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:42.100  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.100  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.100  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.100  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.100  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.100  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.100  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.100  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.100  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.100  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.100  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.100  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.100  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.100  6282  6335 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:43:42.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:42.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.110  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:42.110  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.110  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:43:42.110  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:42.110  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:42.110  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:42.110  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:42.110  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:43:42.110  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:42.110  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:43:42.120  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:42.120  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:42.130  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:43:42.130  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:42.130  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:43:42.130  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:43:42.130  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:42.140  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
08-16 17:43:42.140  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:43:42.150  2656  2672 D BtGatt.GattService: registerClient() - UUID=03bab687-9aeb-43ff-9e16-e8090f9aad7a
,08-16 17:43:42.200  2656  2729 D BtGatt.GattService: onClientRegistered() - UUID=03bab687-9aeb-43ff-9e16-e8090f9aad7a, clientIf=6
,08-16 17:43:42.200  6282  6290 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:42.200  2656  2753 D BtGatt.GattService: start scan with filters
,08-16 17:43:42.210  2656  2744 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:42.210  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:43:42.210  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:43:42.210  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:43:42.210  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:42.210  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.210  2656  2744 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
,08-16 17:43:42.220  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:42.220  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.220  2656  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:43:42.220  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.220  2656  2744 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:42.220  2656  2744 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:43:42.220  2656  2744 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:43:42.220  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:43:42.220  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.230  2656  2744 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:43:42.230  2656  2744 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:42.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:42.230  2656  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:42.230  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.230  6282  6335 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:42.230  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:42.230  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.240  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.240  6282  6335 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:42.240  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.240  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:42.240  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:42.240  2656  2672 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:42.240  2656  2753 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:43:42.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:43:42.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:42.250  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.250  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.250  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.250  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:42.250  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:42.250  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.250  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.250  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.250  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.250  6282  6335 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:43:42.250  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.250  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:42.260  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:42.260  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:42.260  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.260  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.260  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:43:42.260  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:42.260  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:43:42.260  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:42.260  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:42.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:42.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:42.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:42.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:42.280  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:43:42.280  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:42.280  2656  2669 D BtGatt.GattService: registerClient() - UUID=3e079122-a76a-47e3-ae05-701bb6518b0f
,08-16 17:43:42.320  2656  2729 D BtGatt.GattService: onClientRegistered() - UUID=3e079122-a76a-47e3-ae05-701bb6518b0f, clientIf=6
,08-16 17:43:42.320  6282  6290 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:43:42.320  2656  2672 D BtGatt.GattService: start scan with filters
,08-16 17:43:42.320  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:43:42.320  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:42.320  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:43:42.320  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:42.320  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.330  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.330  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:42.330  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:42.330  6282  6335 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:42.330  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:42.330  6282  6335 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:42.330  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:42.330  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:42.330  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:42.330  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:42.340  2656  2753 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:42.340  2656  2744 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 18
,08-16 17:43:42.340  2656  2753 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:42.340  2656  2744 D BtGatt.ScanManager: filter size is 1
08-16 17:43:42.340  2656  2744 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:42.340  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:42.340  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:42.340  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:43:42.340  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.340  2656  2744 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:43:42.350  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.350  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.350  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.350  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.350  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:42.350  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.350  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.350  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.350  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.350  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.350  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:43:42.350  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:43:42.350  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.350  2656  2744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.350  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.350  6282  6335 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:43:42.350  2656  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:42.350  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.350  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:42.350  2656  2744 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:42.360  2656  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:43:42.360  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.360  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:42.360  2656  2744 D BtGatt.ScanManager: allow scan with filters
08-16 17:43:42.360  2656  2744 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:42.360  2656  2744 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:43:42.360  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:43:42.360  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.360  2656  2744 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:43:42.360  2656  2744 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:43:42.360  2656  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:43:42.360  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.360  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:42.360  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:43:42.360  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:43:42.360  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:43:42.360  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:42.360  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:43:42.360  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.370  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:43:42.370  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.370  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:43:42.370  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.370  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.380  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:43:42.380  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:43:42.380  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:43:42.380  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:43:42.380  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:43:42.380  2656  2672 D BtGatt.GattService: registerClient() - UUID=1cf908c9-438d-4fca-b80e-5cfd776c8c9f
,08-16 17:43:42.410  2656  2744 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 19
,08-16 17:43:42.410  2656  2744 D BtGatt.ScanManager: filter size is 1
,08-16 17:43:42.410  2656  2744 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 17:43:42.420  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:43:42.420  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.420  2656  2744 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:43:42.420  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:43:42.420  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.420  2656  2744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:42.420  2656  2729 D BtGatt.GattService: onClientRegistered() - UUID=1cf908c9-438d-4fca-b80e-5cfd776c8c9f, clientIf=6
,08-16 17:43:42.420  6282  6296 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:43:42.420  2656  2753 D BtGatt.GattService: start scan with filters
,08-16 17:43:42.430  2656  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:42.430  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.430  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:43:42.430  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:43:42.430  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:43:42.430  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:43:42.430  2656  2744 D BtGatt.ScanManager: handling starting scan
,08-16 17:43:42.430  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.430  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:43:42.430  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:43:42.440  2656  2729 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:43:42.440  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.440  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:43:42.440  6282  6335 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:43:42.440  2656  2744 D BtGatt.ScanManager: allow scan with filters
,08-16 17:43:42.440  2656  2744 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:43:42.440  2656  2744 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 17:43:42.450  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.450  6282  6335 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:43:42.450  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.450  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:43:42.450  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:43:42.450  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:43:42.450  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.450  2656  2744 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:43:42.450  2656  2744 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:43:42.450  2656  2672 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:43:42.450  2656  2669 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:43:42.450  2656  2729 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:43:42.450  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:43:42.450  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:43:42.450  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:43:42.450  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:43:42.460  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:43:42.460  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.460  6282  6335 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:43:42.460  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.460  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.460  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:43:42.460  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.460  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.460  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.460  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.460  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.460  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.460  6282  6335 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 17:43:42.460  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.460  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.460  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.460  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.460  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.460  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.460  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.460  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.460  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.460  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.460  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:42.460  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.460  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.470  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 17:43:42.470  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.470  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.470  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.470  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.470  6282  6335 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 17:43:42.470  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.470  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.470  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.470  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.470  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.470  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.470  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.470  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.480  6282  6335 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 17:43:42.480  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.480  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.480  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.480  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.480  2656  2744 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 20
,08-16 17:43:42.480  2656  2744 D BtGatt.ScanManager: filter size is 1
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
,08-16 17:43:42.480  2656  2744 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect,
08-16 17:43:42.480  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:42.480  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:43:42.480  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:43:42.480  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:43:42.480  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:43:42.480  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.480  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:42.480  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:43:42.480  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.480  2656  2729 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:43:42.480  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.480  2656  2744 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.480  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.480  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.480  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:42.480  6282  6335 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55,
08-16 17:43:42.480  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:42.490  2656  2729 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:43:42.490  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.490  2656  2744 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:43:42.490  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:42.490  2656  2729 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:43:42.490  2656  2729 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:43:42.490  6282  6335 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:43:42.490  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:43:42.490  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:43:42.490  6282  6335 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:42.490  6282  6335 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:43:42.490  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:42.490  6282  6335 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:42.490  6282  6335 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:43:42.490  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:42.490  6282  6335 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:43:42.490  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:43:42.500  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:43:42.500  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:43:42.500  6282  6335 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:43:42.500  6282  6335 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:43:42.500  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.500  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.500  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.500  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.500  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.500  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:43:42.500  6282  6419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1152)
08-16 17:43:42.500  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.500  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.500  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1152
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:43:42.510  6282  6335 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:42.510  6282  6335 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:43:42.510  6282  6335 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:42.510  6282  6335 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:43:42.510  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.510  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.510  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.510  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.510  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.510  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.510  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.520  6282  6419 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.520  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.520  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.520  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.520  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.520  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6419 D BluetoothSocket: connect(): myUserId = 0
08-16 17:43:42.520  6282  6419 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:43:42.520  6282  6282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:43:42.520  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.520  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:43:42.520  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.520  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.520  6282  6282 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:43:42.520  6282  6421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:43:42.520  6282  6421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:43:42.520  2656  2672 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:42.530  6282  6419 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
08-16 17:43:42.530  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.530  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:43:42.530  6282  6282 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:43:42.530  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.530  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.530  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.530  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.530  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.530  6282  6335 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:43:42.530  6282  6335 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:43:42.530  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:43:42.530  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.530  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.530  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.530  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.530  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.530  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.530  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.540  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.540  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:43:42.540  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:43:42.540  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5217abf not in the list
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:43:42.540  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:43:42.540  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:43:42.540  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1161a58c not in the list
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:42.540  6282  6335 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:42.540  6282  6335 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:43:42.540  6282  6335 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:43:42.540  6282  6335 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:43:42.550  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:42.550  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fa7c58e added. We now have 2 listener(s)
08-16 17:43:42.550  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:42.550  6282  6335 D BluetoothAdapter: enable()
08-16 17:43:42.550  6282  6335 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:43:42.550  1017  3104 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:42.550  1017  3104 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:42.550  1017  3104 D SecContentProvider2: mCursor = null
08-16 17:43:42.550  1017  3104 D WifiService: setWifiEnabled: true pid=6282, uid=10155
08-16 17:43:42.550  1017  3104 W ActivityManager: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:42.550  1017  3104 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:43:42.550  1017  3104 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:42.550  1017  3104 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:43:42.550  1017  3104 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:43:42.550  1017  3104 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:43:42.550  1017  3104 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:43:42.550  1017  3104 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:43:42.550  1017  3104 D SettingsProvider: name = wifi_on
08-16 17:43:42.550  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:42.550  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@327491af added. We now have 3 listener(s)
08-16 17:43:42.550  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:42.560  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:42.560  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1c5f89bc added. We now have 4 listener(s)
08-16 17:43:42.560  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:42.560  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:43:42.560  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@340d1d45 added. We now have 5 listener(s)
08-16 17:43:42.560  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:43:42.560  1017  1805 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:42.560  1017  1805 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:42.560  1017  1805 D SecContentProvider2: mCursor = null
08-16 17:43:42.560  1017  1805 D WifiService: setWifiEnabled: false pid=6282, uid=10155
08-16 17:43:42.560  1017  1805 D SettingsProvider: name = wifi_on
,08-16 17:43:42.580  1017  1128 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 17:43:42.580  6282  6335 D BluetoothAdapter: disable(),
08-16 17:43:42.580  2099  2099 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:43:42.580  2099  2099 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 17:43:42.580  2099  2099 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:43:42.580  1017  1509 D SettingsProvider: name = bluetooth_on
,08-16 17:43:42.580  2099  2099 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:43:42.580  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:42.600  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:43:42.610  2656  2725 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 17:43:42.610  2656  2725 D BluetoothAdapterProperties: Setting state to 13
08-16 17:43:42.610  1017  1128 E WifiNative-wlan0: do suspend true
,08-16 17:43:42.610  2656  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:43:42.610  2656  2725 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:42.610  2656  2725 D BluetoothAdapterService: updateAdapterState state is 13
08-16 17:43:42.610  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 17:43:42.610  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:42.610  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:42.610  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 17:43:42.610  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:42.610  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.610  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:42.610  2656  2656 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-16 17:43:42.610  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:43:42.610  2656  2725 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:42.610  2656  2725 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:43:42.610  2656  2725 D BluetoothAdapterService: terminating service from this receiver
08-16 17:43:42.610  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@21926f84, channel: 19, state: LISTENING
,08-16 17:43:42.610  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@21926f84, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11df12b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d6be36dmSocket: android.net.LocalSocket@9893ba2 impl:android.net.LocalSocketImpl@20e5f033 fd:FileDescriptor[76]
08-16 17:43:42.610  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9893ba2 impl:android.net.LocalSocketImpl@20e5f033 fd:FileDescriptor[76]
08-16 17:43:42.610  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:42.610  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.610  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:42.610  1017  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:42.610  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:42.610  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:43:42.610  2656  2725 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:43:42.610  2656  2725 D BluetoothAdapterProperties: mDiscovering is false
08-16 17:43:42.610  1017  1217 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 17:43:42.610  2656  2725 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:43:42.620  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:43:42.620  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:42.620  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-16 17:43:42.620  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.620  2656  2729 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:42.620  2656  2729 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:42.630  2656  2725 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 17:43:42.630  1297  1297 D BluetoothPbap: Proxy object disconnected
08-16 17:43:42.630  1297  1297 D PbapServerProfile: Bluetooth service disconnected
08-16 17:43:42.630  2656  2725 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 17:43:42.630  2656  2725 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:43:42.630  2656  2725 E bt-btif : cmd socket is not created
,08-16 17:43:42.630  2656  2725 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:43:42.630  2656  2842 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 17:43:42.630  2656  2842 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:43:42.630  6282  6419 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@208299cb, channel: -1, state: INIT
08-16 17:43:42.630  6282  6419 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@208299cb, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@207985a8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@226748c1mSocket: android.net.LocalSocket@246af866 impl:android.net.LocalSocketImpl@1e1f07a7 fd:FileDescriptor[108]
08-16 17:43:42.630  6282  6419 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@246af866 impl:android.net.LocalSocketImpl@1e1f07a7 fd:FileDescriptor[108]
08-16 17:43:42.630  6282  6419 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1152)
08-16 17:43:42.630  2656  5008 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:43:42.630  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:43:42.630  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:43:42.640  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:42.640  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:43:42.640  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:42.640  1017  1481 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-16 17:43:42.640  1017  1481 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4157, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
08-16 17:43:42.640  1017  1481 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 17:43:42.640  1017  1481 D BatteryService: stay LED for charging
08-16 17:43:42.640  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:42.650  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:42.650  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:42.650  2656  2842 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:42.650  1017  1017 I MotionRecognitionService: Plugged,
08-16 17:43:42.650  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:42.660  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:42.660  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:43:42.660  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:43:42.660  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,08-16 17:43:42.670  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:43:42.680  2656  2748 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:42.680  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:42.680  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:43:42.690  1786  1786 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:42.690  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@af04969, channel: 5, state: LISTENING
,08-16 17:43:42.690  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@af04969, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a732eec, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ee36feemSocket: android.net.LocalSocket@23055c8f impl:android.net.LocalSocketImpl@31162b1c fd:FileDescriptor[74]
08-16 17:43:42.690  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23055c8f impl:android.net.LocalSocketImpl@31162b1c fd:FileDescriptor[74]
,08-16 17:43:42.690  2656  2656 I BtOppRfcommListener: stopping Accept Thread
08-16 17:43:42.690  2656  2656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b3b1325, channel: 12, state: LISTENING
08-16 17:43:42.690  2656  2656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b3b1325, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ffd197, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@b9a9cfamSocket: android.net.LocalSocket@300532ab impl:android.net.LocalSocketImpl@22e8dd08 fd:FileDescriptor[80]
08-16 17:43:42.690  2656  2656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@300532ab impl:android.net.LocalSocketImpl@22e8dd08 fd:FileDescriptor[80]
,08-16 17:43:42.690  2656  5008 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:43:42.690  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:43:42.690  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
08-16 17:43:42.690  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
08-16 17:43:42.690  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:42.690  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:42.700  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:42.700  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:42.700  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-16 17:43:42.700  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:42.700  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:42.700  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:42.700  1017  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:42.700  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:42.700  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:42.700  1017  1805 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:43:42.700  1017  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:42.700  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:42.700  1017  1219 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:42.710  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:42.710  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:42.710  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:42.710  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:42.710  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:42.710  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 17:43:42.710  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:42.710  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:42.710  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:42.710  2656  2656 V BluetoothOppManager: cleanUp...
,08-16 17:43:42.720  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:42.720  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:42.720  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:42.720  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:43:42.730  1017  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-16 17:43:42.730  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.730  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:42.730  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:42.730  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.740  6430  6430 E Zygote  : MountEmulatedStorage(),
08-16 17:43:42.740  1017  1219 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6430 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a,
08-16 17:43:42.740  6430  6430 E Zygote  : v2
08-16 17:43:42.740  6430  6430 I libpersona: KNOX_SDCARD checking this for 10003
,08-16 17:43:42.740  6430  6430 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:43:42.740  6430  6430 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:42.750  6430  6430 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:42.750  6430  6430 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:42.770  6430  6430 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:42.770  6430  6430 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:42.800  6430  6430 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:42.830  2656  2842 W bt-btif : ag scb idx 1 not allocated
,08-16 17:43:42.830  2656  2842 W bt-btif : ag scb idx 2 not allocated
08-16 17:43:42.830  2656  2842 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:43:42.830  2656  2937 I bt_userial_mct: exiting userial_read_thread
,08-16 17:43:42.830  2656  2937 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:43:42.830  2656  2729 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-16 17:43:42.830  2656  2844 I bt_vendor: hw_epilog_process
08-16 17:43:42.830  2656  2729 D bt_userial_mct: userial_close
,08-16 17:43:42.830  2656  2729 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:43:42.840  6430  6430 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-16 17:43:42.840  6430  6430 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 17:43:42.840  6430  6430 D UserAnalysis: Create SecureDbHelper
,08-16 17:43:42.840  6430  6430 D IntelligenceServiceApplication: onCreate()
,08-16 17:43:42.850  1017  1509 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 17:43:42.850  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.850  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:42.850  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.850  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:42.850  6430  6430 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 17:43:42.870  6446  6446 E Zygote  : MountEmulatedStorage()
,08-16 17:43:42.870  6446  6446 E Zygote  : v2
08-16 17:43:42.870  6446  6446 I libpersona: KNOX_SDCARD checking this for 10107
08-16 17:43:42.870  6446  6446 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:42.870  6446  6446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:42.870  6446  6446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:43:42.870  1017  1509 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6446 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 17:43:42.870  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-16 17:43:42.870  6446  6446 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-16 17:43:42.870  6430  6430 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-16 17:43:42.880  6430  6430 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 17:43:42.890  6446  6446 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:42.890  6446  6446 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:42.930  1017  1030 I art     : Explicit concurrent mark sweep GC freed 30942(1558KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.846ms total 152.165ms
,08-16 17:43:42.940  1017  1514 I ActivityManager: Killing 5336:com.google.android.talk/u0a104 (adj 15): empty #31
,08-16 17:43:43.030  2656  2729 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:43:43.030  2656  2729 I bt_vendor: bluetooth satus is on
08-16 17:43:43.030  2656  2729 I bt_vendor: bt-vendor : resetting BT status
08-16 17:43:43.030  2656  2729 I bt_vendor: Starting hciattach daemon
,08-16 17:43:43.030  2656  2729 I bt_vendor: try to set false
,08-16 17:43:43.030  6282  6282 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:43:43.030  2656  2729 I bt_vendor: Starting hciattach daemon
08-16 17:43:43.030  2656  2729 I bt_vendor: try to set false
,08-16 17:43:43.030  2656  2729 I bt_vendor: cleanup
08-16 17:43:43.030  2656  2842 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 17:43:43.030  2656  2729 I GKI_LINUX: GKI_exit_task 0 done
,08-16 17:43:43.030  2656  2729 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:43:43.040  2656  2725 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 17:43:43.040  2656  2725 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:43.040  2656  2725 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 17:43:43.040  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:43.040  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:43.040  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:43.040  1017  1292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.040  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.040  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.040  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.040  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:43.040  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:43.040  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:43.040  2656  2656 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:43.040  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:43.040  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:43.040  2656  2656 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:43:43.040  2656  2656 D BtGatt.GattService: stop()
08-16 17:43:43.050  2656  2656 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:43:43.050  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.050  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.050  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:43.050  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:43.050  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:43.050  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:43.050  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:43.060  1017  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.060  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.060  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.060  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.060  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:43.060  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
,08-16 17:43:43.060  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
08-16 17:43:43.060  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:43.060  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:43:43.060  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:43:43.060  2656  2656 D HeadsetService: Received stop request...Stopping profile...
08-16 17:43:43.060  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 17:43:43.060  1017  1292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.060  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.070   276   972 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:43.070  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.070  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.070  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:43.070  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:43:43.070  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:43:43.070  1936  4360 V NativeCrypto: Read error: ssl=0xb8883c78: I/O error during system call, Connection timed out
08-16 17:43:43.070  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 17:43:43.070  1936  4360 V NativeCrypto: SSL shutdown failed: ssl=0xb8883c78: I/O error during system call, Broken pipe
,08-16 17:43:43.080  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:43.080  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.080  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:43:43.080  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-16 17:43:43.080  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.080  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.080  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.080  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.080  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.080  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.080  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.080  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:43.080  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:43.080  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.080  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-16 17:43:43.080  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.080  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:43:43.080  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:43:43.080  1936  4360 E GCM     : Wifi connection closed with errorCode 20
08-16 17:43:43.080  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 17:43:43.080  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:43:43.090  1017  4314 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-16 17:43:43.090  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.090  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.090  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:43:43.090  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.090  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-16 17:43:43.090  1017  2203 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:43:43.090  1017  2203 I qtaguid : Tagging socket 360 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1017, getuid(): 1000
08-16 17:43:43.100  1017  2203 I qtaguid : Untagging socket 360
08-16 17:43:43.100  1017  2203 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:43:43.100  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.100  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.100  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.110  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.110  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.110  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:43.110  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 17:43:43.110  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:43:43.110  1297  1297 D HeadsetProfile: Bluetooth service disconnected
08-16 17:43:43.110  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:43:43.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-16 17:43:43.110  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:43:43.110  1017  1017 D RttService: SCAN_AVAILABLE : 1
08-16 17:43:43.110  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.110  1017  1151 D RttService: EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.110  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 17:43:43.120  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 17:43:43.120  1017  1150 D WifiScanningService: DefaultState got{ when=-6ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:43.120  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.120  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.120  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:43.120  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:43:43.120  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.120  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.120  2656  2725 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.120  1017  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.120  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-16 17:43:43.120  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:43:43.120  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:43.130  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.130  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.130  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:43.130  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:43.130  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:43.130  2656  2725 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-16 17:43:43.130  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:43.130  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-16 17:43:43.130  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.130  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.130  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:43.130  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:43.130  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:43.140  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:43.140   276   967 D EnterpriseController: uids 1000
08-16 17:43:43.140   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:43:43.140   276   967 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:43.140  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:43.140  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:43.140  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 17:43:43.140  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:43:43.140  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:43.140  2656  2725 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:43.140  2656  2725 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:43.140  2656  2725 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:43:43.140  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-16 17:43:43.140  2656  2656 D A2dpService: Received stop request...Stopping profile...
08-16 17:43:43.140  2656  2769 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:43:43.140  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:43:43.140  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-16 17:43:43.150  1017  1130 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:43:43.150  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:43:43.150  1175  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 17:43:43.150  1017  2203 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:43:43.150  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:43.150  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:43:43.150  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:43.150  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-16 17:43:43.150  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:43:43.150  1017  1130 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 17:43:43.150  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:43:43.160  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:43.160  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:43:43.160  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:43.160  1017  1047 D WifiDisplayController: disconnect
08-16 17:43:43.160  1017  1047 D WifiDisplayController: updateConnection
08-16 17:43:43.160  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:43.160  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:43.160  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.170  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 17:43:43.170  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:43:43.170  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.170  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:43.170  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:43.170  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:43:43.170  1017  1127 D WifiP2pService: P2pDisablingState
08-16 17:43:43.170  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:43:43.170  1017  1127 D WifiP2pService: p2p socket connection lost
08-16 17:43:43.170  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 17:43:43.170  1017  1127 D WifiP2pService: P2pDisabledState
08-16 17:43:43.170  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:43:43.170  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 17:43:43.170  1017  1125 V NetworkStats: updateIfacesLocked()
08-16 17:43:43.170  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.170  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:43.170  1297  1297 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:43.170  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:43:43.170  1297  1297 D A2dpProfile: Bluetooth service disconnected
08-16 17:43:43.170  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:43.170  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:43:43.170  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:43.170  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:43:43.170  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:43.170  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:43:43.170  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-16 17:43:43.170  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:43:43.170  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:43:43.170  1017  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:43.180  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:43.180  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:43.180  2656  2656 D HidService: Received stop request...Stopping profile...
08-16 17:43:43.180  2656  2656 D HidService: Stopping Bluetooth HidService
08-16 17:43:43.180  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:43:43.180  2656  2656 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:43:43.180  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:43:43.180  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
08-16 17:43:43.180  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
08-16 17:43:43.180  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.180  1017  1017 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:43.180  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:43:43.180  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.180  1017  1125 V NetworkStats: performPollLocked() took 11ms
08-16 17:43:43.190  2892  2892 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:43.190  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:43:43.190  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.190  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.190  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:43:43.190  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.190  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 17:43:43.190  1017  1217 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:43.190  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:43:43.190   276   972 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.190  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.190  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.200  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 17:43:43.200  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:43.200  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:43.200  2656  2656 D HealthService: Received stop request...Stopping profile...
08-16 17:43:43.200  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.200  1297  1297 D BluetoothInputDevice: Proxy object disconnected
08-16 17:43:43.200  1297  1297 D HidProfile: Bluetooth service disconnected
08-16 17:43:43.200  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.200  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.200  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:43:43.200  2099  2099 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-16 17:43:43.210  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.220  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:43:43.220  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:43:43.220  2656  2656 D PanService: Received stop request...Stopping profile...
08-16 17:43:43.220  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.220  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:43.220  1017  1128 D SecContentProvider2: mCursor = null
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.220  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.220  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:43.220  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 17:43:43.220  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:43.230  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:43.230  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:43.230  1175  1175 D HotspotTile: onReceive : 0, 0
,08-16 17:43:43.230  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:43.230  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:43.230  1017  1509 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-16 17:43:43.230  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:43:43.230  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.230  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:43.230  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.230  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:43.230  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:43:43.240  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:43:43.240  2656  2656 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:43:43.240  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:43.240  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:43.240  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:43.240  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:43:43.240  1297  1297 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:43:43.240  1297  1297 D PanProfile: Bluetooth service disconnected
,08-16 17:43:43.240  6446  6446 D StrictMode: StrictMode policy violation; ~duration=298 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:43:43.240  6446  6446 D StrictMode: StrictMode policy violation; ~duration=282 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.240  6446  6446 D StrictMode: StrictMode policy violation; ~duration=240 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:43:43.240  6446  6446 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.240  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  6446  6446 D StrictMode: StrictMode policy violation; ~duration=239 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  6446  6446 D StrictMode: StrictMode policy violation; ~duration=237 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  6446  6446 D StrictMode: StrictMode policy violation; ~duration=234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  6446  6446 D StrictMode: StrictMode policy violation; ~duration=232 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.k.c(PG:583)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  6446  6446 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:43:43.250  6446  6446 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:43:43.250  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.260  1297  1297 D BluetoothMap: Proxy object disconnected
08-16 17:43:43.260  1297  1297 D MapProfile: Bluetooth service disconnected
08-16 17:43:43.260  2656  2656 D SapService: Received stop request...Stopping profile...
08-16 17:43:43.260  1017  1030 I ActivityManager: Killing 5821:com.google.android.gms:car/u0a12 (adj 15): empty #31
08-16 17:43:43.260  2656  2656 D SapService: Stopping Bluetooth SapService
08-16 17:43:43.260  2656  2656 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbadce2
08-16 17:43:43.270  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:43.270  2656  2656 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-16 17:43:43.270  2656  2770 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 17:43:43.270  2656  2656 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:43:43.270  2656  2656 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:43:43.270  1297  1297 D SapProfile: Bluetooth service disconnected
08-16 17:43:43.270  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:43:43.270  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:43.270  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:43:43.270  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:43:43.270  2099  2099 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:43.270  2656  2656 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:43:43.270  2656  2656 E BluetoothAdapterService(532339938): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-16 17:43:43.270  2656  2656 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:43:43.270  2656  2656 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-16 17:43:43.280  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-16 17:43:43.280  2656  2725 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:43:43.280  2656  2725 D BluetoothAdapterProperties: Setting state to 10
08-16 17:43:43.280  2656  2725 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:43:43.280  2656  2725 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:43.280  2656  2725 D BluetoothAdapterService: updateAdapterState state is 10
08-16 17:43:43.280  2892  2911 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:43.280  2656  2725 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:43.280  2656  2725 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:43:43.280  2656  2725 I BluetoothAdapterState: Entering OffState
,08-16 17:43:43.300  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.300  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:43.300  1297  1307 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.300  1297  1307 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:43.300  1017  1482 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:43.300  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:43.300  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.300  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:43.300  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:43.300  3709  3709 I Hs20UtilService: Starting #8
08-16 17:43:43.300  3709  3725 I Hs20UtilService: Message received 5007
08-16 17:43:43.300  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:43:43.310  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:43.310  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:43.310  2099  2099 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:43:43.310  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:43.310  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:43.310  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:43.310  2656  2672 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:43.310  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:43.310  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:43.310  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:43.310  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:43.320  1455  2442 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.320  1455  2442 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:43.330  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:43.330  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.330  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:43.330  6446  6467 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-16 17:43:43.330  2099  2099 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-16 17:43:43.330  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-16 17:43:43.330  1017  1562 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
08-16 17:43:43.330  2099  2099 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:43:43.330  2099  2099 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:43:43.330  2099  2099 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:43.330  2099  2099 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 17:43:43.330  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:43.330  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:43.330  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:43.330  1017  1562 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.330  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.330  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:43.330  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.330  1017  1128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
08-16 17:43:43.330  1017  1131 D Tethering: InitialState.processMessage what=4
,08-16 17:43:43.340  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:43:43.340  1017  1131 E Tethering: No numeric data
08-16 17:43:43.340  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:43.340  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:43.340  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:43:43.340  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:43.340  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:43.350  6481  6481 E Zygote  : MountEmulatedStorage()
08-16 17:43:43.350  6481  6481 E Zygote  : v2
08-16 17:43:43.350  6481  6481 I libpersona: KNOX_SDCARD checking this for 10104
08-16 17:43:43.350  6481  6481 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:43.350  6481  6481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:43.350  6481  6481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:43.350  6481  6481 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:43.360  1017  1562 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6481 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 17:43:43.360  1297  1322 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:43:43.360  1017  1804 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:43.360  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.360  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:43.360  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:43:43.370  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:43.370  1017  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:43.370  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:43.370  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:43.370  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:43.370  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:43.370  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:43.370  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:43.370  1175  1175 D HotspotTile: updateTetherState():false, false
,08-16 17:43:43.370  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.370  1017  1125 V NetworkStats: performPollLocked() took 4ms
,08-16 17:43:43.380  6481  6481 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:43.380  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:43.380  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:43.380  6282  6296 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.380  6282  6296 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:43.380  6282  6296 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:43:43.380  6282  6296 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:43:43.380  6282  6296 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:43:43.380  6282  6296 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:43:43.380  1936  2124 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.380  1936  2124 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:43.380  1297  1307 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:43:43.390   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb8f3d7c8
08-16 17:43:43.400  6481  6481 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:43:43.390   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-16 17:43:43.390   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 17:43:43.390   271   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1191979720)
,08-16 17:43:43.400  1297  1322 D BluetoothInputDevice: onBluetoothStateChange: up=false,
,08-16 17:43:43.410  2656  6426 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.410  2656  6426 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:43.410  1441  1465 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.410  1441  1465 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:43.410  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.410  1297  1322 D Bluetoothsap: onBluetoothStateChange: up=false,
08-16 17:43:43.410  1297  1322 D Bluetoothsap: Unbinding service...
,08-16 17:43:43.410  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:43.410  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:43.420  1175  2362 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.420  1175  2362 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan,
08-16 17:43:43.420  2892  3000 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.420  2892  3000 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:43.420  1297  1307 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:43:43.420  1429  1443 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:43.420  1429  1443 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:43.420  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
08-16 17:43:43.420  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.420  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
08-16 17:43:43.420  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:43.420  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.430  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:43.430  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:43.430  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.430  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:43.430  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:43.430  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
,08-16 17:43:43.430  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.440  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.440  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:43.440  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:43.440  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:43:43.440  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:43:43.440  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.440  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-16 17:43:43.440  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.440  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:43:43.440  1175  1726 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:43.440  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.440  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.440  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:43.440  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-16 17:43:43.440  1175  1726 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.440  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.440  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.440  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.440  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.440   271   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-16 17:43:43.440  1017  3103 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:43:43.440   271   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 17:43:43.450   271   346 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1191979720) wakelock released: 1, error no: 0
08-16 17:43:43.450   271   346 I rmt_storage: 
08-16 17:43:43.450  1017  1030 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 17:43:43.450  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.450  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.450   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb8f3d7c8
08-16 17:43:43.450  1786  1786 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:43.450  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 17:43:43.450  1936  2132 D BluetoothAdapter: 1025780903: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.450  1936  2132 D BluetoothAdapter: 1025780903: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:43.450  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:43.450  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.450  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.450  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:43.450  1017  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:43.450  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:43.450  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:43:43.450  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:43.450  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:43.450  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:43.450  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.450  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.460  2656  2729 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 17:43:43.460  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-16 17:43:43.460  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:43:43.460  2656  2656 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:43:43.460  2656  2656 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 17:43:43.460  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:43:43.470  2656  2656 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:43:43.470  2656  2656 I art     : System.exit called, status: 0
08-16 17:43:43.470  2656  2656 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:43:43.490  2099  2099 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 17:43:43.590  2099  2099 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 17:43:43.590  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:43.590  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:43.590  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:43.590  1017  1805 I ActivityManager: Process com.android.bluetooth (pid 2656)(adj 0) has died(49,1084)
,08-16 17:43:43.600  6481  6524 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 17:43:43.600  6481  6524 I Babel   : MmsConfig.loadMmsSettings
,08-16 17:43:43.610  6481  6524 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-16 17:43:43.610  6481  6524 I Babel   : MmsConfig.loadFromDatabase
,08-16 17:43:43.620  6481  6524 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 17:43:43.620  6481  6524 I Babel   : MmsConfig.loadFromResources
,08-16 17:43:43.620  6481  6524 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:43:43.620  6481  6524 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-16 17:43:43.630  1017  1509 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 17:43:43.630  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.630  1017  1509 W ActivityManager: userId = 0, bbcId = -10000,
,08-16 17:43:43.630  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:43.630  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
08-16 17:43:43.640  6481  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:43.660  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:43.670  1017  1017 I ApplicationPolicy: updateDataUsageMap
,08-16 17:43:43.680  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:43.680  3189  3189 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-16 17:43:43.690  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:43.690  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:43.690  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-16 17:43:43.690  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:43:43.690  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:43:43.690  3189  3189 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-16 17:43:43.700  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:43.700  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:43.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:43.710  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:43.710  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-16 17:43:43.710  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:43.710  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:43.710  1175  1175 D HotspotTile: onReceive : 1, 0
,08-16 17:43:43.710  1936  2132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:43.710  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:43.710  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:43.710  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:43.720  6481  6481 I Babel_StickerModule: App launched.
,08-16 17:43:43.720  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:43:43.730  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:43.730  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:43.730  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:43.730  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:43.730  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:43.730  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:43.730  1017  3103 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 17:43:43.740  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.740  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.740  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:43.740  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.740   281   281 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-16 17:43:43.740   281   281 W QCamera2Factory: getCameraInfo: X
,08-16 17:43:43.740   281   684 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,08-16 17:43:43.740   281   684 W QCamera2Factory: getCameraInfo: X
,08-16 17:43:43.750  6526  6526 E Zygote  : MountEmulatedStorage(),
,08-16 17:43:43.750  6526  6526 E Zygote  : v2
08-16 17:43:43.750  6526  6526 I libpersona: KNOX_SDCARD checking this for 10068
08-16 17:43:43.750  6526  6526 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:43.750  6526  6526 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:43.760  1017  3103 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6526 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:43.760  6526  6526 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:43.760  6526  6526 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:43.760  6481  6481 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:43:43.760  6481  6481 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:43:43.760  6481  6481 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:43:43.770  6481  6481 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 17:43:43.770  6481  6481 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 17:43:43.770  6481  6481 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 17:43:43.770  6481  6481 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 17:43:43.770  6481  6481 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:43:43.780  6481  6481 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:43:43.780  6526  6526 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:43.780  6526  6526 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:43.790  6526  6526 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:43:43.810  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:43.810  6481  6481 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:43:43.810  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:43:43.820  6481  6481 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:43:43.840  6481  6481 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 17:43:43.840  6481  6481 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:43:43.840  6481  6481 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:43:43.840  6481  6481 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 17:43:43.850  6526  6526 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:43:43.850  1017  1219 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 17:43:43.850  6481  6481 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 17:43:43.850  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.850  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:43.850  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.850  1017  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:43.860  6481  6481 W VideoCapabilities: Unsupported mime video/mp43
,08-16 17:43:43.860  6481  6481 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 17:43:43.860  6541  6541 E Zygote  : MountEmulatedStorage()
08-16 17:43:43.860  6541  6541 E Zygote  : v2
08-16 17:43:43.860  6541  6541 I libpersona: KNOX_SDCARD checking this for 10069
08-16 17:43:43.860  6541  6541 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:43.870  6541  6541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:43:43.870  1017  1219 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6541 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 17:43:43.870  1017  1219 I ActivityManager: Killing 5047:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-16 17:43:43.870  6481  6481 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 17:43:43.870  6541  6541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:43.880  6541  6541 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:43.890  6541  6541 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:43.890  6541  6541 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:43.900  6481  6481 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:43:43.920  6541  6541 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:43.930  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.930  1017  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:43.930  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:43.930  1017  1514 I ActivityManager: Killing 5602:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-16 17:43:43.940  1017  3103 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
08-16 17:43:43.940  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-16 17:43:43.950  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:43.950  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:43.950  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:43:43.950  1017  1805 I ActivityManager: Killing 5510:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-16 17:43:43.950  6481  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:44.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:44.210  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:44.210  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.210  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.210  1017  1044 D Tethering: interfaceRemoved wlan0
,08-16 17:43:44.210  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:43:44.210  1017  3103 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:44.210  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:44.210  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:44.210  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.210  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:44.220  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:44.220  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:44.220  3709  3709 I Hs20UtilService: Starting #9
,08-16 17:43:44.220  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:43:44.220  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:44.220  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:44.220  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:43:44.220  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:44.220  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:44.230  1017  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:44.230  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:44.230  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.230  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.230  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:44.240  3709  3709 I Hs20UtilService: Starting #10
,08-16 17:43:44.240  1017  4314 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-16 17:43:44.240  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:43:44.240  1017  4314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.240  1017  4314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.240  1017  4314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.240  1017  4314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.250  1017  4314 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6558 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:43:44.250  6558  6558 E Zygote  : MountEmulatedStorage()
08-16 17:43:44.250  6558  6558 E Zygote  : v2
08-16 17:43:44.250  6558  6558 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:43:44.250  6558  6558 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.250  6558  6558 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.260  6558  6558 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:44.260  6558  6558 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.280  6558  6558 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.280  6558  6558 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.310  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:43:44.310  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-16 17:43:44.310  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:43:44.320  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:44.320  1017  1509 I ActivityManager: Killing 5115:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-16 17:43:44.330  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.330  1017  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.330  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.330  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.330  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.330  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.340  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.340  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.340  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.340  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.340  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.340  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.350  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.350  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.350  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.350  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.360  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.360  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.360  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.360  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.360  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.360  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.370  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.370  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.370  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.370  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.380  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.380  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.380  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:43:44.390  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:44.390  1017  3104 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:44.390  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:44.390  1017  3104 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.390  1017  3104 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.390  1017  3104 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:44.400  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:44.400  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:44.410  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:44.410  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:43:44.410   286   286 E SMD     : DCD OFF
,08-16 17:43:44.420  1017  1292 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-16 17:43:44.420  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.420  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.420  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.420  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.430  6575  6575 E Zygote  : MountEmulatedStorage(),
08-16 17:43:44.430  6575  6575 E Zygote  : v2,
08-16 17:43:44.440  6575  6575 I libpersona: KNOX_SDCARD checking this for 1002
08-16 17:43:44.440  6575  6575 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:44.440  1017  1292 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6575 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 17:43:44.440  6575  6575 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:43:44.440  6575  6575 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:44.440  6575  6575 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.470   311   311 I art     : Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 767us total 32.651ms
,08-16 17:43:44.480  6575  6575 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:44.480  6575  6575 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.490   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 748us total 20.568ms
,08-16 17:43:44.500  6575  6575 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:43:44.500  6575  6575 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 17:43:44.500  1017  1562 I ActivityManager: Killing 5879:com.sec.pcw.device/1000 (adj 15): empty #31
,08-16 17:43:44.510   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 20.056ms
,08-16 17:43:44.530  6575  6575 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:43:44.550  1017  1044 D Tethering: interfaceRemoved p2p0
,08-16 17:43:44.550  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding GattService
,08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding HeadsetService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding A2dpService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding HidService
,08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding HealthService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding PanService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding SapService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding SapClientService
,08-16 17:43:44.560  6575  6575 D BtSettings.ProfileConfig: Adding HidDevService
08-16 17:43:44.560  6575  6575 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:43:44.560  1017  1030 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 17:43:44.570  1017  1030 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.570  1017  1030 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:44.570  1017  1030 D SettingsProvider: selectionArgs: false
08-16 17:43:44.570  1017  1030 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.570  1017  1030 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:44.570  1017  1030 D SettingsProvider: ret = -1
,08-16 17:43:44.570  1017  1482 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:44.570  1017  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.570  1017  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.570  1017  1482 D SettingsProvider: selectionArgs: false
08-16 17:43:44.570  1017  1482 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.570  1017  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.570  1017  1482 D SettingsProvider: ret = -1
,08-16 17:43:44.570  1017  3104 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:44.570  1017  3104 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.570  1017  3104 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:44.570  1017  3104 D SettingsProvider: selectionArgs: false
08-16 17:43:44.570  1017  3104 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.570  1017  3104 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:44.570  1017  3104 D SettingsProvider: ret = -1
,08-16 17:43:44.570  1017  1562 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-16 17:43:44.570  1017  1562 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:44.570  1017  1562 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.570  1017  1562 D SettingsProvider: selectionArgs: false
08-16 17:43:44.570  1017  1562 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.570  1017  1562 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.570  1017  1562 D SettingsProvider: ret = -1
,08-16 17:43:44.570  1017  1804 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-16 17:43:44.570  1017  1804 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.570  1017  1804 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.570  1017  1804 D SettingsProvider: selectionArgs: false
08-16 17:43:44.570  1017  1804 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.570  1017  1804 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.570  1017  1804 D SettingsProvider: ret = -1
08-16 17:43:44.580  1017  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:43:44.580  1017  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:44.580  1017  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  1219 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1219 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.580  1017  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:44.580  1017  1219 D SettingsProvider: ret = -1
,08-16 17:43:44.580  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 17:43:44.580  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.580  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  1029 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1029 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.580  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  1029 D SettingsProvider: ret = -1
08-16 17:43:44.580  1017  1217 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:43:44.580  1017  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.580  1017  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  1217 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1217 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.580  1017  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  1217 D SettingsProvider: ret = -1
,08-16 17:43:44.580  1017  4314 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
08-16 17:43:44.580  1017  4314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:44.580  1017  4314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  4314 D SettingsProvider: selectionArgs: false
,08-16 17:43:44.580  1017  4314 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.580  1017  4314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  4314 D SettingsProvider: ret = -1
08-16 17:43:44.580  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:44.580  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.580  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  1481 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1481 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.580  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  1481 D SettingsProvider: ret = -1
08-16 17:43:44.580  1017  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:43:44.580  1017  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.580  1017  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:44.580  1017  1509 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1509 D SettingsProvider: selectionArgs: 1002
08-16 17:43:44.580  1017  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  1509 D SettingsProvider: ret = -1
,08-16 17:43:44.580  1017  1292 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 17:43:44.580  1017  1292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:44.580  1017  1292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:44.580  1017  1292 D SettingsProvider: selectionArgs: false
08-16 17:43:44.580  1017  1292 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:44.580  1017  1292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:44.580  1017  1292 D SettingsProvider: ret = -1
,08-16 17:43:44.590  1017  1514 I ActivityManager: Killing 5895:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-16 17:43:44.590  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:44.590  1017  3104 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:44.590  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:44.600  1017  3104 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.600  1017  3104 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:44.600  1017  3104 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:44.600  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:44.600  1017  1292 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 17:43:44.600  1936  6591 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:44.600  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.600  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.600  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.600  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.620  6592  6592 E Zygote  : MountEmulatedStorage(),
08-16 17:43:44.620  6592  6592 E Zygote  : v2
08-16 17:43:44.620  6592  6592 I libpersona: KNOX_SDCARD checking this for 1000
,08-16 17:43:44.620  6592  6592 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.620  6592  6592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.620  6592  6592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:44.620  6592  6592 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.620  1017  1292 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:43:44.630  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:44.630  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.630  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:44.630  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-16 17:43:44.640  1017  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:44.640  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.640  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:44.640  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:44.650  6592  6592 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.650  6592  6592 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.650  1936  6591 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:43:44.670  6592  6592 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 17:43:44.670  6592  6592 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-16 17:43:44.680  6592  6592 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 17:43:44.690  6592  6592 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 17:43:44.690  6592  6592 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 17:43:44.690  6592  6592 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 17:43:44.690  6592  6592 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:44.690  1017  1514 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-16 17:43:44.690  1017  1514 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 17:43:44.690  1017  1514 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-16 17:43:44.690  6592  6608 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-16 17:43:44.690  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.690  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.690  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.690  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.710  6610  6610 E Zygote  : MountEmulatedStorage(),
08-16 17:43:44.710  6610  6610 E Zygote  : v2,
,08-16 17:43:44.710  6610  6610 I libpersona: KNOX_SDCARD checking this for 10111
08-16 17:43:44.710  6610  6610 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.710  6610  6610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.710  1017  1514 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6610 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:44.710  6610  6610 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:44.720  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
,08-16 17:43:44.720  6610  6610 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.720  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.720  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:43:44.720  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.720  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.740  6620  6620 E Zygote  : MountEmulatedStorage(),
08-16 17:43:44.740  6620  6620 E Zygote  : v2
,08-16 17:43:44.740  6620  6620 I libpersona: KNOX_SDCARD checking this for 10009
08-16 17:43:44.740  6620  6620 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.740  6620  6620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.750  1017  1042 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6620 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:44.750  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-16 17:43:44.750  1732  1732 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:44.750  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.750  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.750  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.750  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.750  6620  6620 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:44.760  6620  6620 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-16 17:43:44.760  6610  6610 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.760  6610  6610 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.770  6634  6634 E Zygote  : MountEmulatedStorage(),
08-16 17:43:44.780  6634  6634 E Zygote  : v2
08-16 17:43:44.780  6634  6634 I libpersona: KNOX_SDCARD checking this for 10145
,08-16 17:43:44.780  6634  6634 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.780  6634  6634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:43:44.780  6634  6634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:43:44.780  1017  1042 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6634 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-16 17:43:44.780  6634  6634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.790  6620  6620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.790  6620  6620 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:44.790  1732  1732 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-16 17:43:44.790  1732  1732 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,08-16 17:43:44.800  1732  1732 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-16 17:43:44.800  1732  1732 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:44.800  1732  1732 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:43:44.810  1732  1732 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-16 17:43:44.810  1308  1329 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,08-16 17:43:44.810  1017  1482 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 17:43:44.810  1017  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.810  1017  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.810  1017  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.810  1017  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.820  6634  6634 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:43:44.820  6634  6634 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.830  6655  6655 E Zygote  : MountEmulatedStorage()
,08-16 17:43:44.830  6655  6655 E Zygote  : v2
,08-16 17:43:44.840  6655  6655 I libpersona: KNOX_SDCARD checking this for 10081
08-16 17:43:44.840  6655  6655 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:44.840  6655  6655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.840  6655  6655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:43:44.840  1017  1482 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6655 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:43:44.840  6655  6655 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.860  1732  1732 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-16 17:43:44.870  6655  6655 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.870  6655  6655 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:44.880  6634  6634 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-16 17:43:44.880  6634  6634 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:43:44.880  6634  6634 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:43:44.880  6634  6634 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:43:44.880  6634  6634 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:43:44.900  1017  3104 I ActivityManager: Killing 5909:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-16 17:43:44.910  3727  3727 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:43:44 GMT+02:00 2016
,08-16 17:43:44.910  6610  6610 I MusicStore: Database version: 108
,08-16 17:43:44.910  1017  1509 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 17:43:44.910  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:44.910  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.910  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:44.910  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:43:44.920  3727  3727 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:43:44.920  3727  3727 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-16 17:43:44.920  1017  1292 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 17:43:44.920  3727  3727 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:43:44.930  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.930  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.930  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:44.930  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:44.930  3727  3727 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:43:44.940  6677  6677 E Zygote  : MountEmulatedStorage()
08-16 17:43:44.940  6677  6677 E Zygote  : v2
08-16 17:43:44.940  6677  6677 I libpersona: KNOX_SDCARD checking this for 10034
08-16 17:43:44.940  6677  6677 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:44.940  6677  6677 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:44.950  1017  1292 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6677 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-16 17:43:44.950  6677  6677 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:44.950  1017  4314 D RCPManagerService: exchangeData() failure , invalid userId
08-16 17:43:44.950  6677  6677 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:44.950  3727  6675 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:43:44.950  1017  1562 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 17:43:44.950  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:43:44.950  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:44.950  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:44.950  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:44.950  3727  6675 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 17:43:44.960  3727  6675 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 17:43:44.960  3727  6675 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-16 17:43:44.960  3727  3727 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 17:43:44.980  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:44.990  6677  6677 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:44.990  6677  6677 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:45.010  1017  1805 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 17:43:45.010  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.010  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.010  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.010  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.020  6697  6697 E Zygote  : MountEmulatedStorage()
,08-16 17:43:45.020  6697  6697 E Zygote  : v2
08-16 17:43:45.020  6697  6697 I libpersona: KNOX_SDCARD checking this for 10113
,08-16 17:43:45.020  6697  6697 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:45.030  6697  6697 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:45.030  6697  6697 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:45.030  1017  3103 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.030  6697  6697 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:45.030  1017  1805 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6697 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:43:45.030  1017  1805 I ActivityManager: Killing 5568:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-16 17:43:45.040  6677  6677 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 17:43:45.050  1017  1805 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.060  6697  6697 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:45.060  6697  6697 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:45.070  6610  6610 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 17:43:45.070  6610  6610 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:43:45.080  3283  6714 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-16 17:43:45.080  5962  5962 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 17:43:45.090  6146  6146 I SA      : [DM] init START
,08-16 17:43:45.090  3283  6714 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 17:43:45.090  3283  6714 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 17:43:45.100  3283  6714 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-16 17:43:45.100  3283  6714 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 17:43:45.100  1017  3103 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-16 17:43:45.100  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.100  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.100  1017  3103 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 17:43:45.100  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 17:43:45.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
08-16 17:43:45.110  6146  6146 I SA      : [DM] This device is not a Vodafone
,08-16 17:43:45.120  6146  6146 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-16 17:43:45.120  6146  6146 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-16 17:43:45.120  6610  6610 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 17:43:45.120  6146  6146 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-16 17:43:45.130  6034  6046 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-16 17:43:45.140  1017  1804 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.140  6146  6146 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-16 17:43:45.140  6146  6146 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-16 17:43:45.150  5962  6716 E SPPClientService: [[SystemStateMonitorService]] No Active Internet,
,08-16 17:43:45.150  1017  4314 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.150  6034  6046 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-16 17:43:45.150  6034  6046 D BadgeProvider: sendNotify, [notify] : null
08-16 17:43:45.150  6034  6046 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-16 17:43:45.150  6034  6046 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 17:43:45.150  6034  6046 D BadgeProvider: update, [UpdateCount] : 1
,08-16 17:43:45.150  1487  1487 D Launcher.Model: reloadBadges entered.
,08-16 17:43:45.150  6146  6146 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-16 17:43:45.150  6146  6146 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75),
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-16 17:43:45.160  6146  6146 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-16 17:43:45.170  1017  1482 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.180  6146  6146 I SA      : [SCU] isHaveSA() - false
08-16 17:43:45.180  6146  6146 I SA      : support phone number id : false
08-16 17:43:45.180  6146  6146 I SA      : [DM] Supports Ref Jpn : true
,08-16 17:43:45.180  6146  6146 I SA      : [DM] init END
,08-16 17:43:45.180  6146  6146 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-16 17:43:45.180  6146  6146 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-16 17:43:45.180  6146  6146 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 17:43:45.190  6146  6146 I SA      : [SLFUCHKMGR] constructor called
,08-16 17:43:45.190  1017  3104 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:43:45.200  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:45.200  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:45.200  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:45.200  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:45.200  1017  1292 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-16 17:43:45.200  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.200  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.200  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.200  1017  1292 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.210  6146  6146 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-16 17:43:45.210  6610  6610 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37e9f416: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 17:43:45.210  6610  6610 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 17:43:45.210  6610  6610 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 17:43:45.210  6610  6610 D AndroidMusic: GMSCore installation verified
08-16 17:43:45.210  6146  6146 I SA      : [OR] == isSIMCardReady false ==
,08-16 17:43:45.220  6723  6723 E Zygote  : MountEmulatedStorage(),
08-16 17:43:45.220  6723  6723 E Zygote  : v2
08-16 17:43:45.220  6723  6723 I libpersona: KNOX_SDCARD checking this for 10159
08-16 17:43:45.220  6723  6723 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:45.220  1017  1292 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6723 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:45.220  6723  6723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:45.220  6146  6146 I SA      : [SCU] == networkStateCheck == false
,08-16 17:43:45.220  6146  6146 I SA      : [OR] onReceive END
,08-16 17:43:45.220  6723  6723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:45.230  6723  6723 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-16 17:43:45.230  1017  1481 I ActivityManager: Killing 5534:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-16 17:43:45.230  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:45.250  6723  6723 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:45.250  6723  6723 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:45.250  1017  1514 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:45.250  1017  1514 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-16 17:43:45.260  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.260  1017  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.260  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.270  6610  6610 I ConfigStore: Config Database version: 1
,08-16 17:43:45.280  1017  1049 I PowerManagerService: [PWL] Off : 50s ago
,08-16 17:43:45.280  1017  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-16 17:43:45.280  1017  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-16 17:43:45.280  1017  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1017, ws=null) (elapsedTime=2114)
,08-16 17:43:45.290  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:43:45.290  1017  4314 I ActivityManager: Killing 5943:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-16 17:43:45.290  1017  3103 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:45.290  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.290  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.290  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.290  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:45.300  3772  3772 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:43:45.310  3772  4608 I iu.UploadsManager: num queued entries: 0
,08-16 17:43:45.310  3772  4608 I iu.UploadsManager: num updated entries: 0
,08-16 17:43:45.310  3772  4608 I iu.SyncManager: NEXT; no task
,08-16 17:43:45.360   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:43:45.360   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.360  6610  6610 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:43:45.370   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:43:45.370   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.370  6610  6610 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:43:45.370   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:43:45.370   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.370  6610  6610 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:43:45.380  1017  1805 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 17:43:45.380  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.380  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.380  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.380  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.390  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:45.390  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-16 17:43:45.400  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:45.400  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.400  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.410  1017  1292 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:45.420  1017  3104 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:45.430  1017  1219 I AudioService: getStreamVolume 3 index 0
,08-16 17:43:45.430  6610  6610 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-16 17:43:45.440  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-16 17:43:45.440  1017  3103 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 17:43:45.440  6610  6610 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-16 17:43:45.440  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.440  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.440   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:43:45.440   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.450  6697  6744 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:43:45.450  1017  2730 D SSRM:n  : SIOP:: AP = 350
,08-16 17:43:45.450   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:43:45.450   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.450  6697  6744 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:43:45.460  1017  3103 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 17:43:45.460  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:43:45.460  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.460  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.460  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.460  1017  1219 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:45.460  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.470  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.470  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.470  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.470  1017  1805 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 17:43:45.470  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.470  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.470   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:43:45.470  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.470   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:43:45.470  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.480  6697  6748 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:43:45.480  1017  1509 I ActivityManager: Killing 5861:com.android.mms/u0a46 (adj 15): empty #31
,08-16 17:43:45.480  1017  1292 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:45.490  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 17:43:45.490  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.490  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.490  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.490  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.490   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:43:45.490   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:43:45.500  6697  6748 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:43:45.510  6751  6751 E Zygote  : MountEmulatedStorage()
08-16 17:43:45.510  6751  6751 E Zygote  : v2
08-16 17:43:45.510  6751  6751 I libpersona: KNOX_SDCARD checking this for 10002
08-16 17:43:45.510  6751  6751 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:45.510  6751  6751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:45.510  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6751 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:43:45.510  6751  6751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:45.510  6751  6751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:45.520  1017  4314 D CountryDetector: No listener is left
,08-16 17:43:45.530  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-16 17:43:45.530  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 17:43:45.530  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.530  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.530  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 17:43:45.540  6610  6610 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-16 17:43:45.540  6751  6751 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:45.540  1017  1509 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:45.540  6751  6751 D ActivityThread: Added TimaKeyStore provider
08-16 17:43:45.540  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:43:45.540  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:45.540  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.540  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:45.580  1017  3104 I ActivityManager: Killing 6020:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-16 17:43:45.600  1017  1514 I ActivityManager: Killing 6077:com.wsomacp/u0a25 (adj 15): empty #31
,08-16 17:43:45.610  1017  1805 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-16 17:43:45.610  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.610  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.610  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.610  1017  1805 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.620  1017  1805 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6783 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:43:45.620  1017  1030 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:43:45.620  1017  1030 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:45.620  1017  1030 D SecContentProvider2: mCursor = null
,08-16 17:43:45.620  6783  6783 E Zygote  : MountEmulatedStorage()
08-16 17:43:45.620  6783  6783 E Zygote  : v2
08-16 17:43:45.620  6783  6783 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:43:45.620  6783  6783 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:45.620  1017  1030 D WifiService: setWifiEnabled: true pid=6282, uid=10155
08-16 17:43:45.620  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:45.620  1017  1030 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:43:45.620  1017  1030 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:45.620  1017  1030 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:43:45.620  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:43:45.620  1017  1030 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:43:45.620  1017  1030 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:43:45.620  1017  1030 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:43:45.620  6783  6783 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:43:45.620  1017  1030 D SettingsProvider: name = wifi_on
,08-16 17:43:45.630  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:43:45.630  6783  6783 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:43:45.630  6783  6783 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:45.650  1017  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:45.650  6697  6697 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-16 17:43:45.660  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:45.660  1017  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:45.660  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 17:43:45.660  6783  6783 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:45.660  6783  6783 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:45.680  6697  6697 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9151-9153)
08-16 17:43:45.680  6697  6697 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:43:45.680  6697  6697 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23055c8f}
,08-16 17:43:45.690  6697  6697 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:43:45.690  6697  6697 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:43:45.700  6783  6783 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 17:43:45.700  6697  6697 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:43:45.710  6697  6697 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:43:45.710  6697  6697 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:43:45.730  6697  6697 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 17:43:45.730  6697  6697 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-16 17:43:45.730  6697  6697 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-16 17:43:45.740  6697  6697 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:43:45.740  6697  6697 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:43:45.740  6697  6697 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:43:45.740  6697  6697 I Adreno-EGL: Local Branch: 
08-16 17:43:45.740  6697  6697 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:43:45.740  6697  6697 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:43:45.740  6697  6697 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:43:45.820  6783  6783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-16 17:43:45.830  6783  6783 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-16 17:43:45.830  6783  6783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:45.840  6783  6783 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 17:43:45.840  6783  6783 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-16 17:43:45.840  6783  6783 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 17:43:45.860  6697  6812 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 17:43:45.860  6697  6697 I NSApplication: Starting up...
,08-16 17:43:45.880  1017  1217 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 17:43:45.880  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.880  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:45.880  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.880  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:45.890  6822  6822 E Zygote  : MountEmulatedStorage(),
08-16 17:43:45.890  6822  6822 E Zygote  : v2
,08-16 17:43:45.890  6822  6822 I libpersona: KNOX_SDCARD checking this for 10120
,08-16 17:43:45.890  6822  6822 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:45.890  1017  1217 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6822 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
08-16 17:43:45.900  6822  6822 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:43:45.900  1017  1217 I ActivityManager: Killing 5989:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31,
08-16 17:43:45.900  1017  1217 I ActivityManager: Killing 6093:com.sec.android.app.soundalive/u0a53 (adj 15): empty #32,
,08-16 17:43:45.900  6822  6822 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:43:45.900  6822  6822 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:43:45.910   311   311 I art     : Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 23.107ms
08-16 17:43:45.910  6822  6822 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:45.920  6822  6822 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:45.930   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 16.904ms
,08-16 17:43:45.940  6822  6822 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:43:45.950   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 764us total 17.141ms
,08-16 17:43:46.000  1017  1044 D Tethering: interfaceAdded wlan0
,08-16 17:43:46.010  1017  1131 E Tethering: No numeric data
,08-16 17:43:46.010  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-16 17:43:46.010  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 17:43:46.010  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:46.010  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:46.010  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:46.010  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:46.010  1175  1175 D HotspotTile: updateTetherState():false, false
08-16 17:43:46.020  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:46.020  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated,
,08-16 17:43:46.020  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:43:46.020  1017  1131 D Tethering: clearTetheredNotification()
08-16 17:43:46.020  1017  1131 D Tethering: InitialState.processMessage what=4
08-16 17:43:46.020  1017  1044 D Tethering: interfaceAdded p2p0
,08-16 17:43:46.030  1017  1131 E Tethering: No numeric data
,08-16 17:43:46.030  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 17:43:46.040  1017  1125 V NetworkStats: performPollLocked() took 24ms
08-16 17:43:46.040  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:46.040  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:46.040  1017  1131 D Tethering: clearTetheredNotification()
08-16 17:43:46.040  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:46.040  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:43:46.040  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:46.040  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-16 17:43:46.040  1175  1175 D HotspotTile: updateTetherState():false, false
08-16 17:43:46.050  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:46.050   276   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 17:43:46.050  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:46.050   276   972 D SoftapController: Softap fwReload - Ok
08-16 17:43:46.050  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:46.050  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:46.050  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:46.050  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:46.060   276   972 D CommandListener: Setting iface cfg
08-16 17:43:46.060   276   972 D CommandListener: Trying to bring down wlan0
,08-16 17:43:46.060   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:46.060  1017  1125 V NetworkStats: performPollLocked() took 10ms
,08-16 17:43:46.060  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:46.060  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 17:43:46.060  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:46.060  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:46.060  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-16 17:43:46.070  1017  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-16 17:43:46.070  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:46.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 17:43:46.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:46.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:46.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:43:46.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:46.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:46.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 17:43:46.080  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:43:46.080  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:46.080  1175  1175 D HotspotTile: onReceive : 2, 0,
,08-16 17:43:46.080  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-16 17:43:46.090  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:43:46.090  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:46.110   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 17:43:46.120  6840  6840 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-16 17:43:46.120  6840  6840 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 17:43:46.120  6840  6840 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:43:46.130  6840  6840 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-16 17:43:46.140   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6840
08-16 17:43:46.140   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-16 17:43:46.140  6840  6840 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:43:46.140  6840  6840 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:46.140  6840  6840 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:43:46.140  6840  6840 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:43:46.140   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6840,
08-16 17:43:46.140   373   373 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 17:43:46.290  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 17:43:46.290  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.290  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:46.290  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.290  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:46.300   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-16 17:43:46.310  6846  6846 E Zygote  : MountEmulatedStorage()
08-16 17:43:46.310  6846  6846 E Zygote  : v2
08-16 17:43:46.310  6846  6846 I libpersona: KNOX_SDCARD checking this for 10125
08-16 17:43:46.310  6846  6846 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:46.310  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-16 17:43:46.310  1017  1029 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6846 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 17:43:46.310  1017  1029 I ActivityManager: Killing 5790:com.samsung.android.sm/1000 (adj 15): empty #31
,08-16 17:43:46.320  6846  6846 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:46.320  6846  6846 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:43:46.320  6846  6846 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:43:46.340  6846  6846 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:46.340  6846  6846 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:46.350  6846  6846 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:43:46.350  6846  6846 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:43:46.350  6846  6846 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:46.360  6846  6846 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:43:46.360  6846  6846 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-16 17:43:46.370  6846  6846 I QuickConnect: PeriphStartReceiver.onReceive - no need to start,
08-16 17:43:46.370  1017  3103 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-16 17:43:46.370  1017  3103 I ActivityManager: Killing 5927:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-16 17:43:46.380  1017  1217 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:46.380  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:46.380  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.380  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.380  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:46.380  3709  3709 I Hs20UtilService: Starting #11
08-16 17:43:46.380  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:43:46.380  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:46.380  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:46.380  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:46.380  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:46.390  6840  6840 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:43:46.390  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:43:46.400  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:46.400   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6840
08-16 17:43:46.400   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:43:46.400  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:43:46.400  6840  6840 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:46.400  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:46.400  6840  6840 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:46.400  6840  6840 E wpa_supplicant: SIM READ ERROR
08-16 17:43:46.400  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:46.400  6840  6840 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:46.400  6840  6840 E wpa_supplicant: SIM READ ERROR
08-16 17:43:46.400  6840  6840 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:43:46.400  6840  6840 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:43:46.400  6840  6840 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:43:46.400  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:43:46.400  6840  6840 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:43:46.400  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:46.400  6840  6840 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:43:46.400  1017  1029 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:46.400  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:46.400  6840  6840 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:43:46.400  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:46.400  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:46.400  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:46.400  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:46.400  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:46.410  3709  3709 I Hs20UtilService: Starting #12
,08-16 17:43:46.410  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:46.410  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:43:46.410  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
08-16 17:43:46.410  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:46.410  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:46.410  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1,
,08-16 17:43:46.520  6840  6840 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-16 17:43:46.650  6840  6840 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:43:46.650  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 17:43:46.660  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:46.660   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6840
08-16 17:43:46.660   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 17:43:46.670  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 17:43:46.670  6840  6840 I wpa_supplicant: ssSupport state is = 1
08-16 17:43:46.670  6840  6840 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:43:46.670  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:43:46.680  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:43:46.680   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6840
08-16 17:43:46.680   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:43:46.680  6840  6840 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 17:43:46.680  6840  6840 I wpa_supplicant: ssSupport state is = 1
,08-16 17:43:46.680  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:46.690  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:46.680  6840  6840 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:46.680  6840  6840 E wpa_supplicant: SIM READ ERROR
08-16 17:43:46.680  6840  6840 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:43:46.680  6840  6840 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:43:46.680  6840  6840 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:43:46.680  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:43:46.680  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:43:46.690  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:43:46.690  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:43:46.690  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:46.830  6840  6840 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:43:46.830  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:43:46.920  6840  6840 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-16 17:43:46.920  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-16 17:43:46.920  6840  6840 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:43:47.010  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:43:47.010  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:47.010  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:43:47.070  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-16 17:43:47.070  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:43:47.080  6840  6840 I wpa_supplicant: HOTSPOT20_ENABLE called
08-16 17:43:47.080  6840  6840 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:43:47.080  6840  6840 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:43:47.080  6840  6840 E wpa_supplicant: SIM READ ERROR,
08-16 17:43:47.080  6840  6840 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:47.090  6840  6840 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-16 17:43:47.110  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 17:43:47.110  6840  6840 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 17:43:47.120  1017  1128 D WifiConfigStore: Loading config and enabling all networks ,
,08-16 17:43:47.120  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:47.120  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:47.120  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:47.120  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:47.120  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:47.120  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:47.120  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:47.120  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 17:43:47.120  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:47.120  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:47.130  1175  1175 D HotspotTile: onReceive : 3, 0,
,08-16 17:43:47.130  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:47.130  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:47.130  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:47.130  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:47.130  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:47.130  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:47.130  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:47.130  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:47.140  1017  1128 E WifiConfigStore: Not a HS20
08-16 17:43:47.140  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:43:47.140  1017  1562 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:47.140  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:43:47.140  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:47.140  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:47.140  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:47.140  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
08-16 17:43:47.140  3709  3709 I Hs20UtilService: Starting #13
08-16 17:43:47.150  3709  3725 I Hs20UtilService: Message received 5011
08-16 17:43:47.150  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:43:47.150  6840  6840 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:43:47.150  6840  6840 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:43:47.150  6840  6840 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:43:47.150  6840  6840 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:43:47.150  6840  6840 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:43:47.150  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:43:47.150  6840  6840 I wpa_supplicant: First Scan Start
08-16 17:43:47.150  6840  6840 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:43:47.150  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:43:47.150  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:47.150  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:47.150  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:43:47.160  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
08-16 17:43:47.160  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:43:47.160  1017  1128 I WifiNative-HAL: startHal
08-16 17:43:47.160  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9c8d688c
08-16 17:43:47.160  1017  1128 I WifiNative-HAL: Could not start hal
08-16 17:43:47.160  6481  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:47.160  1017  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:47.160  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:43:47.160  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
08-16 17:43:47.170   276   972 D CommandListener: Setting iface cfg
08-16 17:43:47.170   276   972 D CommandListener: Trying to bring up p2p0
08-16 17:43:47.170  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:43:47.170  1017  1150 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:47.170  1017  1150 I WifiNative-HAL: startHal
08-16 17:43:47.170  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9dee19bc
08-16 17:43:47.170  1017  1150 I WifiNative-HAL: Could not start hal
08-16 17:43:47.170  1017  1150 E WifiScanningService: could not start HAL
08-16 17:43:47.170  1017  1017 D RttService: SCAN_AVAILABLE : 3
08-16 17:43:47.170  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:43:47.170  1017  1151 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:47.170  1017  1127 D WifiP2pService: P2pEnablingState
08-16 17:43:47.170  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:43:47.170  1017  1127 D WifiP2pService: P2p socket connection successful
08-16 17:43:47.170  1017  1127 D WifiP2pService: P2pEnabledState
08-16 17:43:47.170  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:47.170  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:47.170  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-16 17:43:47.170  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:43:47.170  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:47.170  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:43:47.170  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:43:47.170  1017  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:43:47.170  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:43:47.180  6840  6840 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:47.180  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:43:47.180  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:47.180  1017  1047 D WifiDisplayController: disconnect
08-16 17:43:47.180  1017  1047 D WifiDisplayController: updateConnection
08-16 17:43:47.180  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:47.180  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:47.180  6840  6840 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:43:47.180  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:43:47.180  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:47.180  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:47.180  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:43:47.180  6840  6840 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-16 17:43:47.190  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-16 17:43:47.190  1017  3103 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:43:47.190  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-16 17:43:47.190  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:47.190  1017  1128 D SecContentProvider2: mCursor = null
08-16 17:43:47.190  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 17:43:47.190  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-16 17:43:47.190  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:43:47.190  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:43:47.190  1017  1127 D WifiP2pService: DeviceAddress: 7e:96:ac
08-16 17:43:47.190  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:47.190  1017  1128 D SecContentProvider2: mCursor = null
08-16 17:43:47.200  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:43:47.200  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  secondary type: null
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  wps: 0
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  grpcapab: 0
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  devcapab: 0
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  status: 3
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  wfdInfo: null
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-16 17:43:47.200  1017  1047 D WifiDisplayController:  SConnectInfo : null
08-16 17:43:47.200  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:43:47.200  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:47.200  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:47.200  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:43:47.200  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 17:43:47.200  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:43:47.200  6526  6526 D FileShare-Client: Outbound.stopDelayTimer - 
08-16 17:43:47.210  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-16 17:43:47.210  1017  1127 D WifiP2pService: InactiveState
08-16 17:43:47.210  6541  6541 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-16 17:43:47.210  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:43:47.210  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
08-16 17:43:47.210  6840  6840 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:43:47.210  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:43:47.210  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:43:47.410   286   286 E SMD     : DCD OFF,
,08-16 17:43:48.370  6840  6840 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
,08-16 17:43:48.370  6840  6840 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-16 17:43:48.380  1017  6864 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-16 17:43:48.380  6840  6840 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-16 17:43:48.380  6840  6840 I wpa_supplicant: Trying to associate with  'G700'
,08-16 17:43:48.380  6840  6840 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-16 17:43:48.380  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-16 17:43:48.400  1017  1042 I ActivityManager: Killing 6193:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-16 17:43:48.400  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.400  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:48.490  6840  6840 E wpa_supplicant: Cmd 35605 not handled
08-16 17:43:48.490  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:48.490  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:48.490  6840  6840 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-16 17:43:48.490  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:48.490  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:43:48.490  6840  6840 I wpa_supplicant: Associated with F4.99.3E
08-16 17:43:48.490  6840  6840 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:43:48.490  6840  6840 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 17:43:48.490  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:48.500  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:48.500  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:48.500  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:48.500  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:48.500  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:48.500  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:48.500  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:43:48.500  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:43:48.500  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 17:43:48.500  1017  1131 E Tethering: No numeric data
,08-16 17:43:48.500  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:43:48.500  1017  1131 D Tethering: clearTetheredNotification()
,08-16 17:43:48.500  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:48.500  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:48.510  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:43:48.510  1175  1175 D HotspotTile: updateTetherState():false, false
08-16 17:43:48.510  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.510  1017  1128 D SecContentProvider2: mCursor = null
08-16 17:43:48.510  6840  6840 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:43:48.510  6840  6840 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-16 17:43:48.510  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:43:48.510  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:48.510  6840  6840 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 17:43:48.510  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:43:48.510  6840  6840 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:43:48.510  6840  6840 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:43:48.510  6840  6840 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:43:48.510  6840  6840 I wpa_supplicant: Blacklist: Clear (temp) 
,08-16 17:43:48.510  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:48.510  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:43:48.510  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-16 17:43:48.510  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 17:43:48.510  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.510  1017  1128 D SecContentProvider2: mCursor = null
08-16 17:43:48.510  1017  1125 V NetworkStats: performPollLocked() took 7ms
08-16 17:43:48.510  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:48.510  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:48.520  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:48.520  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:43:48.520  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-16 17:43:48.520  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:48.520  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-16 17:43:48.520  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 17:43:48.530  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:48.530  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:48.530  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:43:48.530  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.530  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.530  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.530  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.530  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:48.530  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:43:48.530  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-16 17:43:48.530  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:48.530  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:48.530  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:48.540  3709  3709 I Hs20UtilService: Starting #14
08-16 17:43:48.540  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:43:48.540  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:48.540  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,08-16 17:43:48.540  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:48.540  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:48.550  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-16 17:43:48.550  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:43:48.550  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:48.550   276   972 D CommandListener: Setting iface cfg
,08-16 17:43:48.550  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:48.550  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:43:48.560  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.560  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:48.570  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:48.570  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:43:48.570  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.570  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.570  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.570  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.570  1017  1128 E WifiNative-wlan0: do suspend false
,08-16 17:43:48.570  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:43:48.580  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.580  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:48.580  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:48.640  1017  1509 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:43:48.640  1017  1509 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:43:48.640  1017  1509 D SecContentProvider2: mCursor = null
,08-16 17:43:48.640  1017  1509 D WifiService: setWifiEnabled: false pid=6282, uid=10155
,08-16 17:43:48.640  1017  1509 D SettingsProvider: name = wifi_on
,08-16 17:43:48.640  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:43:48.660  1017  1128 E WifiNative-wlan0: do suspend true,
,08-16 17:43:48.680  1017  1127 D WifiP2pService: InactiveState{ what=143375 },
,08-16 17:43:48.680  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:43:48.690   276   972 D CommandListener: Clearing all IP addresses on wlan0,
08-16 17:43:48.690  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:48.690  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:48.690  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.690  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.690  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.690  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.690  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:48.690  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
08-16 17:43:48.690  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:48.690  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-16 17:43:48.690   276   972 E Netd    : no such netId 503
08-16 17:43:48.690  1017  1127 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:43:48.690  1017  1128 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:43:48.690  1017  1127 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:43:48.690  1017  1130 D ConnectivityService: nai.networkMonitor.doQuit()
08-16 17:43:48.690  1017  1130 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
08-16 17:43:48.690  1017  1130 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:43:48.690  1017  1130 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:43:48.690  1017  1130 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-16 17:43:48.700  1017  1130 E ConnectivityService: updateNetworkInfo()
08-16 17:43:48.690  1017  1130 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:43:48.700  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 17:43:48.700  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:43:48.700  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:48.700  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:43:48.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.700  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.710  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:43:48.710  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:43:48.710  1017  1017 D RttService: SCAN_AVAILABLE : 1
,08-16 17:43:48.710  1017  1151 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:43:48.710  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:43:48.720  1017  1804 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:48.720  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:48.720  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:48.720  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:43:48.720  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:48.720  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:48.720  1017  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:48.720  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:48.720  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:43:48.720  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:43:48.720  1017  1127 D WifiP2pService: P2pDisablingState
,08-16 17:43:48.720  1017  1127 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-16 17:43:48.720  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:43:48.720  3709  3709 I Hs20UtilService: Starting #15
08-16 17:43:48.720  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-16 17:43:48.720  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:48.720  1017  1047 D WifiDisplayController: disconnect
08-16 17:43:48.720  1017  1047 D WifiDisplayController: updateConnection
08-16 17:43:48.720  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:43:48.720  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:48.720  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:43:48.730  1017  1127 D WifiP2pService: p2p socket connection lost
,08-16 17:43:48.730  1017  1128 E WifiNative-wlan0: do suspend true
08-16 17:43:48.730  1017  1127 D WifiP2pService: P2pDisabledState
,08-16 17:43:48.730  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:43:48.730  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:43:48.730  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:43:48.730  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:43:48.730  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:43:48.730  1017  3104 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:43:48.730  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:43:48.740  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:48.740  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:48.740  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:48.740  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:48.740  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:48.740  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:48.740  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:48.750  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:43:48.750  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:48.750  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:48.750  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:43:48.750  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:48.750  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:43:48.750  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:48.760  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:48.760  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:43:48.760  6526  6526 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:43:48.760  1017  1127 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 17:43:48.760   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:43:48.770  1017  1127 D WifiP2pService: DefaultState{ what=143375 }
,08-16 17:43:48.770  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:48.770  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:48.770  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.770  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.770  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.770  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.770  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:43:48.770  6840  6840 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:43:48.780  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:48.780  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:43:48.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.780  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.790  6541  6541 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:43:48.790  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:43:48.790  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:43:48.790  6875  6875 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-16 17:43:48.790  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:43:48.790  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:48.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:48.790  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:48.790  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:48.790  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 17:43:48.790  6875  6875 I dhcpcd  : version 5.5.6 starting
,08-16 17:43:48.800  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:43:48.800  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:48.800  6875  6875 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-16 17:43:48.800  1175  1175 D HotspotTile: onReceive : 0, 0
,08-16 17:43:48.800  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:48.810  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:48.810  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:48.810  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:48.810  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:48.810  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:43:48.810  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:48.810  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:48.820  1017  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-16 17:43:48.820  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:48.820  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:48.820  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:48.820  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:43:48.820  3709  3709 I Hs20UtilService: Starting #16
08-16 17:43:48.820  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:43:48.820  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:43:48.820  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:43:48.820  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:43:48.820  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-16 17:43:48.820  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:43:48.820  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:43:48.820  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:43:48.850  1017  1219 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:48.850  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:48.850  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:48.850  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:48.850  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:48.850  3709  3709 I Hs20UtilService: Starting #17
08-16 17:43:48.850  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:43:48.850  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:43:48.850  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:48.850  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:48.850  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:48.870  6875  6875 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 17:43:48.870  6875  6875 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 17:43:48.870  6875  6875 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-16 17:43:48.870  6875  6875 I dhcpcd  : bssid match
08-16 17:43:48.870  6875  6875 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-16 17:43:48.960  6840  6840 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 17:43:48.970  6875  6875 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,08-16 17:43:49.070  6875  6875 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
08-16 17:43:49.070  6840  6840 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-16 17:43:49.070  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:43:49.070  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:43:49.070  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:43:49.100  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.100  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:49.100  1017  1131 D Tethering: InitialState.processMessage what=4
08-16 17:43:49.100  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.100  6840  6840 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-16 17:43:49.100  1017  1128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-16 17:43:49.100  1017  1131 E Tethering: No numeric data
08-16 17:43:49.100  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.100  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.100  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:43:49.100  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:49.100  1175  1175 D HotspotTile: updateTetherState():false, false
,08-16 17:43:49.100  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:43:49.100  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:43:49.100  1017  1131 D Tethering: clearTetheredNotification()
08-16 17:43:49.110  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.100  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:49.110  6840  6840 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:43:49.110  6840  6840 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-16 17:43:49.110  6840  6840 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:43:49.110  6840  6840 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-16 17:43:49.110  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.110  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:49.110  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 17:43:49.110  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:43:49.120  1017  1125 V NetworkStats: performPollLocked() took 11ms,
08-16 17:43:49.120  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:49.120  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:43:49.120  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:43:49.340  6840  6840 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:43:49.430  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:43:49.430  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:43:49.430  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:43:49.430  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.430  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:43:49.430  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:43:49.430  6840  6840 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-16 17:43:49.540  6481  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:43:49.540  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 17:43:49.540  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 17:43:49.540  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:43:49.550  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:43:49.550  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:43:49.550  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:49.550  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:43:49.550  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:43:49.550  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-16 17:43:49.550  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:49.550  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:43:49.550  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1),
08-16 17:43:49.550  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-16 17:43:49.550  1175  1175 D HotspotTile: onReceive : 1, 0
08-16 17:43:49.560  1936  2132 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:43:49.560  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:43:49.560  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:43:49.560  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:49.560  1017  4314 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:43:49.560  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:43:49.570  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:49.570  1017  4314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:49.570  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:43:49.570  3709  3709 I Hs20UtilService: Starting #18
,08-16 17:43:49.570  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:43:49.570  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:43:49.570  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:43:49.570  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:43:49.570  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:43:50.110   276   965 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-16 17:43:50.110  1017  1044 D Tethering: interfaceRemoved wlan0
,08-16 17:43:50.110  1017  1044 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:43:50.240  1017  1044 D Tethering: interfaceRemoved p2p0
,08-16 17:43:50.240  1017  1044 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:43:50.410   286   286 E SMD     : DCD OFF,
,08-16 17:43:50.420  1017  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.420  1017  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.420  1017  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.430  1017  1482 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 17:43:50.430  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.430  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.430  1017  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:50.430  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.440  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.440  1017  1514 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:50.440  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main,
,08-16 17:43:50.620  1017  1219 I art     : Explicit concurrent mark sweep GC freed 93916(5MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.396ms total 166.741ms
,08-16 17:43:50.620  1017  1219 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-16 17:43:50.620  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.620  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.620  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.620  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 17:43:50.630  1017  1562 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-16 17:43:50.630  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.630  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.630  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.630  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.630  6697  6745 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 17:43:50.630  1017  3103 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:50.630  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.630  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.630  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.630  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.640  1017  1804 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:50.640  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-16 17:43:50.640  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:50.640  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.640  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.650  1017  1509 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 17:43:50.650  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-16 17:43:50.650  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.650  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.650  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.670  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:50.670  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.670  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.670  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 17:43:50.680  1936  1936 D WearableService: callingUid 10012, callindPid: 1936
,08-16 17:43:50.690  1017  4314 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:43:50.690  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:43:50.690  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:50.690  1017  4314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:50.690  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:43:50.740  6610  6904 I MusicLeanback: Conditions not met for autocaching.
,08-16 17:43:50.740  6610  6904 I MusicLeanback: Stop autocaching.
,08-16 17:43:50.790  1936  1952 I art     : Explicit concurrent mark sweep GC freed 61509(3MB) AllocSpace objects, 65(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.326ms total 72.876ms
,08-16 17:43:50.810  6610  6610 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 17:43:50.810  6610  6911 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 17:43:50.940  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:43:51.650  6282  6335 D BluetoothAdapter: enable()
,08-16 17:43:51.650  1017  1219 W ActivityManager: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:43:51.650  1017  1219 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 17:43:51.650  1017  1219 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:43:51.650  1017  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:51.650  1017  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:51.650  1017  1219 D SettingsProvider: name = bluetooth_on,
,08-16 17:43:51.660  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:43:51.660  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:51.660  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 17:43:51.660  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 17:43:51.700  6575  6575 D BluetoothAdapterState: make
,08-16 17:43:51.700  6575  6575 I bluedroid: init
,08-16 17:43:51.700  6575  6913 I BluetoothAdapterState: Entering OffState
,08-16 17:43:51.710  6575  6575 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:43:51.710  6575  6575 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:43:51.710  6575  6575 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:43:51.710  6575  6575 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:43:51.710  6575  6575 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:43:51.710  6575  6575 I bluedroid: get_profile_interface socket
08-16 17:43:51.710  6575  6575 I bluedroid: get_profile_interface map_client
,08-16 17:43:51.710  6575  6916 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:43:51.710  6575  6575 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:43:51.720  6575  6916 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:43:51.720  6575  6916 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:51.720  6575  6916 I bluedroid: getModelRssiValues
08-16 17:43:51.720  6575  6916 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:43:51.720  6575  6916 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:51.720  6575  6575 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:51.720  6575  6916 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:43:51.720  1017  3103 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:51.720  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.720  1017  1017 D SettingsProvider: name = bluetooth_name
08-16 17:43:51.720  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.720  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.720  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.720  6575  6583 I bluedroid: config_hci_snoop_log
,08-16 17:43:51.720  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 17:43:51.730  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:43:51.730  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 17:43:51.730  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:43:51.730  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:43:51.740  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:43:51.740  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:43:51.740  6575  6575 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:43:51.740  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:43:51.740  6575  6913 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 17:43:51.740  6575  6913 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:43:51.740  6575  6913 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:43:51.740  6575  6913 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:43:51.740  6575  6913 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:43:51.750  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:51.750  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:43:51.750  6575  6913 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:51.750  6575  6913 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:43:51.760  6575  6913 D BluetoothSecureManager: getInstant: null
08-16 17:43:51.760  6575  6913 D BluetoothSecureManager: calling getMethod for getService
08-16 17:43:51.760  6575  6913 D BluetoothSecureManager: calling getService
,08-16 17:43:51.760  6575  6913 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@15e6c6e1
,08-16 17:43:51.760  1017  3104 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 17:43:51.760  1017  3104 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:43:51.760  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:51.760  6575  6913 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:43:51.760  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:51.760  1175  1175 D BluetoothTile:  getBluetoothState : 11
08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:43:51.760  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:43:51.760  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:51.760  1786  1786 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:43:51.770  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:51.770  1017  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:43:51.770  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:51.770  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:51.770  1017  1509 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:51.770  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-16 17:43:51.770  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:51.770  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:51.770  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:43:51.770  6575  6913 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService,
08-16 17:43:51.770  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:51.770  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-16 17:43:51.770  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 17:43:51.770  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:51.770  1017  4314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:51.770  6575  6913 D BluetoothBondStateMachine: make
08-16 17:43:51.770  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:43:51.770  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:51.770  1017  4314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:51.770  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:43:51.770  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:51.780  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:51.780  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:43:51.780  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:51.780  6575  6917 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:43:51.780  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.780  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.780  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:51.780  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:51.780  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.780  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:43:51.780  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:43:51.780  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:51.780  6575  6575 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:51.780  6575  6575 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:43:51.780  6575  6575 D BtGatt.GattService: start()
08-16 17:43:51.780  6575  6575 D BtGatt.GattService: start()
08-16 17:43:51.780  6575  6575 I bluedroid: get_profile_interface gatt
,08-16 17:43:51.780  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:51.780  6575  6575 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:43:51.790  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:51.790  1017  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.790  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:43:51.790  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.790  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.790  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.790  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:51.790  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:43:51.790  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:43:51.800  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:51.800  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:43:51.800  1017  3104 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.800  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.800  1017  3104 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:51.800  1017  3104 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.800  1017  3104 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.800  6575  6575 D BtGatt.GattService: mStartError = false
08-16 17:43:51.800  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:51.800  6575  6575 D HeadsetService: Received start request. Starting profile...
08-16 17:43:51.800  6575  6575 D HeadsetService: start()
08-16 17:43:51.810  6575  6575 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:43:51.810  6575  6575 D HeadsetStateMachine: make
08-16 17:43:51.810  6575  6575 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 17:43:51.820  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 17:43:51.820  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:51.820  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:43:51.820  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:51.820  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.820  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.820  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.820  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.820  1017  1217 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 17:43:51.830  1017  1217 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.830  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:43:51.830  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:43:51.830  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:43:51.830  1017  1217 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.830  1017  1217 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:51.830  1017  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:51.830  1017  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.830  1017  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.830  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.830  1017  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.830  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.830  1017  4314 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 17:43:51.830  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.830  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.830  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:43:51.830  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:43:51.830  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 17:43:51.830  1017  4314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:51.840  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:43:51.840  6575  6575 I bluedroid: get_profile_interface handsfree
,08-16 17:43:51.840  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.840  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.840  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.840  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.840  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.840  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:51.840  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:51.840  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 17:43:51.850  1017  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.850  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.850  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.850  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.850  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:51.850  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:43:51.850  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:51.850  6575  6913 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:43:51.860  1017  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:51.860  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:51.860  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:51.860  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:51.860  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:51.860  6575  6575 I DualScoManager: Instantiating Dual Sco Manager
08-16 17:43:51.860  6575  6575 I DualScoManager: Set HeadsetServiceHelper
,08-16 17:43:51.860  6575  6575 D BluetoothAtMessage: createCMTIContentObservers
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:43:51.860  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:51.860  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:43:51.860  1017  3104 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 17:43:51.860  1017  3104 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:51.860  1017  3104 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:51.860  1017  3104 D SettingsProvider: selectionArgs: false
08-16 17:43:51.860  1017  3104 D SettingsProvider: selectionArgs: 1002
08-16 17:43:51.860  1017  3104 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:51.860  1017  3104 D SettingsProvider: ret = -1
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:51.860  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:51.860  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:51.860  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:51.860  6575  6913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:43:51.860  6575  6921 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:43:51.860  6575  6575 D HeadsetService: mStartError = false
08-16 17:43:51.860  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:51.860  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:43:51.870  6575  6921 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 17:43:51.870  6575  6575 D A2dpService: Received start request. Starting profile...
08-16 17:43:51.870  6575  6575 D A2dpService: start()
,08-16 17:43:51.870  6575  6921 D HeadsetStateMachine: map size, before remove : 0
08-16 17:43:51.870  6575  6921 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:43:51.870  6575  6575 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:43:51.870  6575  6575 I bluedroid: get_profile_interface avrcp
,08-16 17:43:51.880  6575  6575 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:43:51.890  6575  6575 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:43:51.890  6575  6925 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:43:51.890  6575  6575 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:43:51.890  6575  6575 D A2dpStateMachine: make
,08-16 17:43:51.900  6575  6575 I bluedroid: get_profile_interface a2dp
,08-16 17:43:51.900  6575  6927 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 17:43:51.900  6575  6575 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:43:51.900  6575  6575 D A2dpService: mStartError = false
08-16 17:43:51.900  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:51.900  6575  6575 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:43:51.900  6575  6575 D HidService: Received start request. Starting profile...
08-16 17:43:51.900  6575  6575 D HidService: start()
08-16 17:43:51.900  6575  6575 I bluedroid: get_profile_interface hidhost
08-16 17:43:51.900  6575  6575 D HidService: setHidService(): set to: null
08-16 17:43:51.900  6575  6575 D HidService: mStartError = false
08-16 17:43:51.900  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:51.900  6575  6575 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:43:51.910  6575  6926 D A2dpStateMachine: Enter Disconnected: -2
08-16 17:43:51.910  1429  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:43:51.910  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0,
08-16 17:43:51.910  6575  6575 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 17:43:51.910  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:43:51.910  1429  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:43:51.910  6575  6575 D HealthService: Received start request. Starting profile...
08-16 17:43:51.910  6575  6575 D HealthService: start()
,08-16 17:43:51.910  6575  6575 I bluedroid: get_profile_interface health
,08-16 17:43:51.910  6575  6575 D HealthService: mStartError = false
08-16 17:43:51.910  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:51.910  6575  6575 D HeadsetStateMachine: Proxy object connected
08-16 17:43:51.910  6575  6575 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:43:51.920  6575  6925 D BluetoothMediaBrowser: no now playing list
,08-16 17:43:51.920  6575  6925 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-16 17:43:51.920  6575  6575 D PanService: Received start request. Starting profile...
08-16 17:43:51.920  6575  6575 D PanService: start()
08-16 17:43:51.920  6575  6575 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 17:43:51.920  6575  6575 I bluedroid: get_profile_interface pan
,08-16 17:43:51.920  6575  6575 D PanService: mStartError = false
08-16 17:43:51.920  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:51.920  6575  6575 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-16 17:43:51.920  6575  6575 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 17:43:51.920  6575  6921 D HeadsetStateMachine: Disconnected process message: 11
08-16 17:43:51.920  6575  6921 D HeadsetStateMachine: Disconnected process message: 18
08-16 17:43:51.920  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:43:51.920  6575  6575 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-16 17:43:51.930  6575  6575 D BluetoothMapService: Received start request. Starting profile...
08-16 17:43:51.930  6575  6575 D BluetoothMapService: start()
,08-16 17:43:51.930  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:51.930  6575  6575 D BluetoothMapService: mStartError = false
08-16 17:43:51.930  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:51.930  6575  6575 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 17:43:51.930  6575  6575 D SapService: Received start request. Starting profile...
08-16 17:43:51.930  6575  6575 D SapService: start()
08-16 17:43:51.930  6575  6575 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:43:51.930  6575  6575 I bluedroid: get_profile_interface sap
08-16 17:43:51.930  6575  6575 D SapService: mStartError = false
08-16 17:43:51.930  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:51.930  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:43:51.940  6575  6575 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:43:51.940  6575  6575 D BluetoothA2dp: Proxy object connected
08-16 17:43:51.940  6575  6575 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:43:51.940  6575  6921 D HeadsetStateMachine: Disconnected process message: 10
08-16 17:43:51.940  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:43:51.940  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:43:51.940  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:43:51.940  6575  6921 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:43:51.940  6575  6921 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:43:51.940  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:43:51.970  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:43:51.970  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:43:51.970  6575  6913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 17:43:51.970  6575  6913 I bluedroid: enable
,08-16 17:43:51.970  6575  6913 I bt_hci_bdroid: init
08-16 17:43:51.970  6575  6931 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 17:43:51.980  6575  6913 I bt_vendor: bt-vendor : init
,08-16 17:43:51.980  6575  6913 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:43:51.980  6575  6913 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-16 17:43:51.980  6575  6913 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 17:43:51.980  6575  6913 D bt_userial_mct: userial_init
,08-16 17:43:51.980  6575  6913 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:43:51.980  6575  6913 I bt_vendor: Starting hciattach daemon
08-16 17:43:51.980  6575  6913 I bt_vendor: try to set false
,08-16 17:43:51.980  6575  6913 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 17:43:51.980  6575  6913 I bt_vendor: Starting hciattach daemon
08-16 17:43:51.980  6575  6913 I bt_vendor: try to set true
,08-16 17:43:52.000  6935  6935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:43:52.050  6941  6941 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:43:52.050  6942  6942 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:43:52.070  6944  6944 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:43:52.080  6945  6945 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:43:52.090  6946  6946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:43:52.100  6947  6947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:43:52.290  6950  6950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 17:43:52.300  6951  6951 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:43:52.340  6575  6913 I bt_vendor: bluetooth satus is on
,08-16 17:43:52.340  6575  6933 D bt_userial_mct: userial_open(port:0)
08-16 17:43:52.340  6575  6933 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:43:52.340  6575  6933 I bt_vendor: Done intiailizing UART,
,08-16 17:43:52.340  6575  6933 I bt_vendor: Done intiailizing UART,
08-16 17:43:52.340  6575  6933 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
08-16 17:43:52.340  6575  6933 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:43:52.350  6575  6953 D bt_userial_mct: Entering userial_read_thread(),
,08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_HCI,
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_A2D,
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:43:52.350  6575  6931 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 17:43:52.450  6575  6931 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:43:52.460  6575  6931 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f966e9 
,08-16 17:43:52.460  6575  6931 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f966e9 
,08-16 17:43:52.470  6575  6916 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:43:52.480  6575  6916 E bt-btif : Calling BTA_HhEnable
,08-16 17:43:52.480  6575  6916 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:43:52.480  6575  6916 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:43:52.480  6575  6916 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:43:52.480  6575  6916 I bluedroid: getModelRssiValues
,08-16 17:43:52.480  6575  6916 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:43:52.480  6575  6916 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:43:52.490  6575  6916 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:43:52.490  1017  1017 D SettingsProvider: name = bluetooth_name
,08-16 17:43:52.490  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:52.490  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:52.490  6575  6916 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:43:52.490  6575  6916 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:43:52.490  6575  6916 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:43:52.490  6575  6916 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 17:43:52.490  6575  6916 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 17:43:52.490  6575  6916 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 17:43:52.490  6575  6916 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:43:52.490  6575  6916 E bt-btif : btif_sock_init: !vhci_init
,08-16 17:43:52.490  6575  6916 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db,
,08-16 17:43:52.500  6575  6916 D IOP_DB_BT: db_open: db_open : handle 3028381712l, read 13894 bytes onto local cache
,08-16 17:43:52.500  6575  6916 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:43:52.500  6575  6916 D IOP_DB_BT: db_query: result 1
,08-16 17:43:52.500  6575  6916 I         : iop_db_open: iop_db_open status 0
,08-16 17:43:52.500  6575  6916 D bte_conf: Device ID record 1 : primary
,08-16 17:43:52.500  6575  6916 D bte_conf:   vendorId            = 0075
08-16 17:43:52.500  6575  6916 D bte_conf:   vendorIdSource      = 0001
,08-16 17:43:52.500  6575  6916 D bte_conf:   product             = 0100
08-16 17:43:52.500  6575  6916 D bte_conf:   version             = 0200
,08-16 17:43:52.500  6575  6916 D bte_conf:   clientExecutableURL = 
08-16 17:43:52.500  6575  6916 D bte_conf:   serviceDescription  = 
,08-16 17:43:52.500  6575  6916 D bte_conf:   documentationURL    = 
08-16 17:43:52.510  6575  6916 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:43:52.510  6575  6916 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:43:52.510  6575  6913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:43:52.510  6575  6913 D BluetoothAdapterProperties: ScanMode =  20
,08-16 17:43:52.510  6575  6913 D BluetoothAdapterProperties: State =  11
,08-16 17:43:52.510  6575  6953 E bt_mct  : hci lib postload completed
,08-16 17:43:52.510  1017  1217 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:43:52.510  6575  6913 D BluetoothAdapterProperties: Setting state to 12
08-16 17:43:52.510  6575  6913 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:43:52.520  6575  6916 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:43:52.520  6575  6916 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:43:52.520  6575  6916 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:43:52.520  1017  1509 D SettingsProvider: name = bluetooth_a2dp_sink_mode,
08-16 17:43:52.520  1017  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-16 17:43:52.520  1017  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:52.520  1017  1509 D SettingsProvider: selectionArgs: false
,08-16 17:43:52.520  1017  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:52.520  1017  1509 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:52.520  1017  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
08-16 17:43:52.520  1017  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:52.520  1017  1509 D SettingsProvider: ret = -1
08-16 17:43:52.520  6575  6913 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:52.520  6575  6913 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:43:52.520  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.520  1017  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:52.520  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.530  6282  6282 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:52.530  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:52.540  6575  6913 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:52.540  6575  6913 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:43:52.540  6575  6913 D BluetoothAdapterService: starting service from this receiver
,08-16 17:43:52.540  2892  2903 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:52.540  1017  3104 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-16 17:43:52.540  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
,08-16 17:43:52.540  1017  3104 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.540  1017  3104 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.540  1017  3104 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:52.540  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:52.550  6575  6913 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:43:52.550  2892  2903 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.550  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:52.550  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.560  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.560  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.560  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:52.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:52.560  2892  2892 D BluetoothA2dp: Proxy object connected
,08-16 17:43:52.560  1429  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.560  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:52.570  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:52.570  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.570  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.570  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.570  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.570  6575  6575 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:43:52.570  1429  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:52.570  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.570  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:52.570  1297  1322 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:43:52.570  1297  1322 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:52.570  1297  1307 D BluetoothPan: Binding service...
,08-16 17:43:52.570  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:52.570  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.580  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.580  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.580  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.580  1429  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.580  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:43:52.580  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.580  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.580  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.580  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.580  1429  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:52.580  6575  6905 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.580  6575  6905 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:52.580  1017  1046 D BluetoothPan: Binding service...
08-16 17:43:52.580  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:43:52.580  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.580  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:43:52.580  6575  6575 I BluetoothPbapService: Handler(): got msg=1
08-16 17:43:52.580  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:52.580  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.580  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:43:52.580  6575  6584 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:52.580  1455  2442 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.580  1455  2442 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.590  1017  1030 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:52.590  2892  2911 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.590  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:52.590  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.590  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.590  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.590  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-16 17:43:52.590  2892  2911 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:43:52.590  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:43:52.590  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.590  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:52.590  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 17:43:52.590  1017  1017 D BluetoothA2dp: Proxy object connected
,08-16 17:43:52.590  1297  1322 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:43:52.590  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 17:43:52.590  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.590  6575  6957 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:43:52.600  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.600  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.600  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.600  1297  1297 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:43:52.600  1297  1297 D PanProfile: Bluetooth service connected
08-16 17:43:52.600  1429  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.610  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:52.610  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.610  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.610  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.610  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.610  6575  6957 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:52.610  6575  6957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:52.610  1429  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:52.610  6282  6290 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.610  6282  6290 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.610  1936  2120 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.610  1936  2120 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.610  6575  6957 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-16 17:43:52.610  6575  6957 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:52.610  6575  6957 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:52.610  6575  6957 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11df12b5
08-16 17:43:52.610  6575  6957 D BluetoothSocket: channel: 19
08-16 17:43:52.610  6575  6957 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:43:52.610  1297  1297 D BluetoothMap: Proxy object connected
08-16 17:43:52.610  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:43:52.610  1297  1307 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:43:52.610  1297  1297 D MapProfile: Bluetooth service connected
,08-16 17:43:52.610  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 17:43:52.610  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.610  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.610  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.610  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.610  1297  1297 D BluetoothMap: getConnectedDevices()
,08-16 17:43:52.620  1455  1676 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.620  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:43:52.620  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.620  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.620  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:52.620  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.620  1455  1676 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:52.620  1297  6959 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:43:52.620  1297  1297 D BluetoothPbap: Proxy object connected
08-16 17:43:52.620  1297  1297 D PbapServerProfile: Bluetooth service connected
,08-16 17:43:52.620  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-16 17:43:52.620  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.620  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.620  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.620  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.630  1441  1458 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-16 17:43:52.630  1441  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:52.630  1297  1297 D BluetoothInputDevice: Proxy object connected
08-16 17:43:52.630  1297  1297 D HidProfile: Bluetooth service connected
,08-16 17:43:52.630  1297  1307 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.630  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:43:52.630  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:43:52.630  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.630  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.630  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.630  1297  1307 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:43:52.630  1297  1297 D HeadsetProfile: Bluetooth service connected
,08-16 17:43:52.630  6446  6461 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.630  6446  6461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.630  1297  6959 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 17:43:52.630  1297  6959 D Bluetoothsap: Binding service...
,08-16 17:43:52.640  1297  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:43:52.640  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-16 17:43:52.640  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.640  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.640  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.640  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.640  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:43:52.640  1297  1297 D SapProfile: Bluetooth service connected
08-16 17:43:52.640  1297  1297 D Bluetoothsap: getConnectedDevices()
08-16 17:43:52.640  1297  6959 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-16 17:43:52.640  1175  1200 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.640  1175  1200 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.640  2892  2903 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.640  2892  2903 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:43:52.640  1297  1307 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:43:52.650  1297  1307 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:43:52.650  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:43:52.650  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.650  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.650  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.650  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.650  1297  1297 D BluetoothA2dp: Proxy object connected
08-16 17:43:52.650  1297  1297 D A2dpProfile: Bluetooth service connected
08-16 17:43:52.650  1429  6958 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:43:52.650  1429  6958 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:43:52.650  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:43:52.650  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:43:52.660  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@c2eaa8, true
,08-16 17:43:52.660  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:52.660  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:43:52.660  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-16 17:43:52.660  1429  1429 D BluetoothHeadset: registerMessageListener
,08-16 17:43:52.660  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:52.660  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:52.660  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:52.660  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-16 17:43:52.660  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:52.660  1786  1786 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:52.670  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:52.670  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:52.670  1017  1219 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:52.670  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:43:52.670  6575  6961 D HeadsetService: registerMessageListener
08-16 17:43:52.670  6575  6961 D HeadsetService: registerMessageListener
,08-16 17:43:52.670  6575  6921 D HeadsetStateMachine: Disconnected process message: 70
,08-16 17:43:52.670  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:43:52.670  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 17:43:52.670  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.670  6575  6921 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ac4d4a
08-16 17:43:52.670  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:52.670  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:43:52.670  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:52.670  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:52.680  1017  1805 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ),
08-16 17:43:52.680  1017  1481 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true,
,08-16 17:43:52.680  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:52.680  1297  1297 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 17:43:52.680  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null,
08-16 17:43:52.680  1297  1297 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:43:52.680  1297  1297 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:43:52.680  1297  1297 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 17:43:52.690  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:43:52.690  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 17:43:52.690  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:43:52.690  6575  6963 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:43:52.690  6575  6921 D HeadsetStateMachine: Disconnected process message: 9
08-16 17:43:52.690  6575  6921 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:43:52.690  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:52.700  1017  1292 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:52.700  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.710  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.710   281   732 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:43:52.710   281   732 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:43:52.710   281   732 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:43:52.710   281   732 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:43:52.710   281   732 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:43:52.710   281   732 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:43:52.710   281   732 V audio_hw_primary: adev_set_parameters: exit
08-16 17:43:52.710  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.710  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:52.710  6575  6963 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:43:52.710  6575  6963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:52.710  6575  6921 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:43:52.710  1017  4314 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:43:52.710  1017  4314 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4200, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 17:43:52.710  1017  4314 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 17:43:52.710  1017  4314 D BatteryService: stay LED for charging
08-16 17:43:52.710  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:43:52.720  1017  1017 I MotionRecognitionService: Plugged
,08-16 17:43:52.720  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:43:52.720  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:43:52.720  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:43:52.720  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:43:52.720  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,08-16 17:43:52.730  6575  6575 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:43:52.730  6575  6921 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:43:52.740  6575  6963 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-16 17:43:52.740  6575  6963 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:52.740  6575  6963 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:52.740  6575  6963 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a25a4bb
,08-16 17:43:52.740  6575  6963 D BluetoothSocket: channel: 5
,08-16 17:43:52.740  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:52.740  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:52.750  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
08-16 17:43:52.750  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:43:52.750  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
08-16 17:43:52.750  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:52.750  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:43:52.760  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:52.760  6575  6575 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:43:52.770  1017  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:52.770  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.770  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.770  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:52.770  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:52.790  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:52.790  1017  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:52.790  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:52.790  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:52.790  1017  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:52.790  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:52.800  1017  1805 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:43:52.800  1936  6970 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:52.810  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:52.810  1017  1805 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:52.810  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.810  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:52.810  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:52.830  6575  6973 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:43:52.830  6575  6973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:43:52.830  1017  1804 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:52.830  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:52.830  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:52.830  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:52.830  6575  6973 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 17:43:52.830  6575  6973 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:43:52.830  6575  6973 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:43:52.830  6575  6973 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ffd197
08-16 17:43:52.830  6575  6973 D BluetoothSocket: channel: 12
08-16 17:43:52.830  6575  6973 I BtOppRfcommListener: Accept thread started.
,08-16 17:43:52.840  1936  6970 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:43:53.420   286   286 E SMD     : DCD OFF,
,08-16 17:43:53.420  1017  2765 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-16 17:43:54.660  6282  6335 D BluetoothAdapter: disable(),
,08-16 17:43:54.660  1017  3103 D SettingsProvider: name = bluetooth_on
,08-16 17:43:54.670  6575  6913 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 17:43:54.670  6575  6913 D BluetoothAdapterProperties: Setting state to 13
08-16 17:43:54.670  6575  6913 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:43:54.670  6575  6913 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:54.670  6575  6913 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:43:54.680  1017  1292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:54.680  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:43:54.680  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:54.680  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:54.680  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:54.680  6575  6575 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-16 17:43:54.680  6575  6913 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:43:54.680  6575  6913 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:43:54.680  6575  6913 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:43:54.680  6575  6575 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@21926f84, channel: 19, state: LISTENING
08-16 17:43:54.680  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:43:54.680  6575  6575 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@21926f84, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11df12b5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2d6be36dmSocket: android.net.LocalSocket@9893ba2 impl:android.net.LocalSocketImpl@20e5f033 fd:FileDescriptor[75]
08-16 17:43:54.680  6575  6575 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@9893ba2 impl:android.net.LocalSocketImpl@20e5f033 fd:FileDescriptor[75]
,08-16 17:43:54.680  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:54.680  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:54.680  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:54.690  6575  6913 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:43:54.690  6575  6913 D BluetoothAdapterProperties: mDiscovering is false
08-16 17:43:54.690  1017  1805 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-16 17:43:54.690  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:54.690  1017  1017 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:43:54.690  6575  6913 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:43:54.700  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:43:54.700  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:54.700  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:43:54.700  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-16 17:43:54.700  1786  1786 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:54.700  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:54.700  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:54.710  1017  3104 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:54.710  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:43:54.710  1017  1292 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:54.720  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:43:54.720  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:54.720  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:54.720  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:54.720  1017  1562 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:54.720  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:54.720  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:54.730  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 17:43:54.730  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:43:54.730  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:43:54.730  6575  6916 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:43:54.730  6575  6916 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:43:54.740  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:54.740  1017  1562 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:54.740  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:54.740  6282  6282 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:43:54.740  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:43:54.740  1297  1297 D BluetoothPbap: Proxy object disconnected
08-16 17:43:54.740  1297  1297 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:43:54.740  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:54.750  6575  6913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-16 17:43:54.750  6575  6913 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-16 17:43:54.750  1017  1030 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:54.750  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:54.750  6575  6913 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:43:54.750  6575  6913 E bt-btif : cmd socket is not created
,08-16 17:43:54.750  6575  6973 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 17:43:54.750  6575  6931 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 17:43:54.750  6575  6931 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:43:54.750  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:54.750  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:54.750  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:54.750  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:54.750  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:54.760  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:54.760  6575  6931 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:54.760  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:43:54.760  6575  6913 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 17:43:54.770  6575  6575 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b88fff0, channel: 5, state: LISTENING
08-16 17:43:54.770  6575  6575 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b88fff0, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a25a4bb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@af04969mSocket: android.net.LocalSocket@ee36fee impl:android.net.LocalSocketImpl@23055c8f fd:FileDescriptor[77]
08-16 17:43:54.770  6575  6575 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ee36fee impl:android.net.LocalSocketImpl@23055c8f fd:FileDescriptor[77]
,08-16 17:43:54.770  6575  6575 I BtOppRfcommListener: stopping Accept Thread
08-16 17:43:54.770  6575  6575 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@31162b1c, channel: 12, state: LISTENING
,08-16 17:43:54.770  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:54.770  6575  6575 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@31162b1c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ffd197, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1b3b1325mSocket: android.net.LocalSocket@b9a9cfa impl:android.net.LocalSocketImpl@300532ab fd:FileDescriptor[80]
08-16 17:43:54.780  6575  6575 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@b9a9cfa impl:android.net.LocalSocketImpl@300532ab fd:FileDescriptor[80]
,08-16 17:43:54.780  6575  6973 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 17:43:54.780  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:54.780  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:54.780  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:43:54.800  6575  6575 V BluetoothOppManager: cleanUp...
,08-16 17:43:54.810  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:54.820  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:54.890  1017  1343 E Watchdog: !@Sync 4
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:43:54.950  6575  6953 I bt_userial_mct: exiting userial_read_thread
08-16 17:43:54.950  6575  6953 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:43:54.950  6575  6916 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:43:54.950  6575  6933 I bt_vendor: hw_epilog_process
08-16 17:43:54.950  6575  6916 D bt_userial_mct: userial_close
08-16 17:43:54.950  6575  6916 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:43:54.950  6575  6931 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:43:54.950  6575  6931 W bt-btif : ag scb idx 1 not allocated
,08-16 17:43:54.960  6575  6931 W bt-btif : ag scb idx 2 not allocated
08-16 17:43:54.960  6575  6931 E bt-btif : BTA AG is already disabled, ignoring ...
,08-16 17:43:55.480  1017  2730 D SSRM:n  : SIOP:: AP = 330
,08-16 17:43:55.960  6575  6916 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:43:55.960  6575  6916 I bt_vendor: bluetooth satus is on
08-16 17:43:55.960  6575  6916 I bt_vendor: bt-vendor : resetting BT status
08-16 17:43:55.960  6575  6916 I bt_vendor: Starting hciattach daemon
08-16 17:43:55.960  6575  6916 I bt_vendor: try to set false
,08-16 17:43:55.960  6575  6916 I bt_vendor: Starting hciattach daemon
08-16 17:43:55.960  6575  6916 I bt_vendor: try to set false
08-16 17:43:55.960  6575  6916 I bt_vendor: cleanup
,08-16 17:43:55.960  6575  6931 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-16 17:43:55.960  6575  6916 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:43:55.960  6575  6916 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:43:55.960  6575  6913 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 17:43:55.960  6575  6913 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:43:55.960  6575  6913 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-16 17:43:55.960  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:43:55.960  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:43:55.960  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:43:55.960  1017  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.960  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.960  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.960  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:55.960  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.970  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:55.970  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:55.970  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:43:55.970  1017  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 17:43:55.970  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
,08-16 17:43:55.970  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.970  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-16 17:43:55.970  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.970  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.970  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.970  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 17:43:55.970  6575  6575 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:43:55.970  1017  1805 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.970  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.980  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.980  1017  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.980  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.980  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:43:55.980  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-16 17:43:55.980  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:43:55.980  1017  1804 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.980  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:43:55.980  6575  6575 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:43:55.980  6575  6575 D BtGatt.GattService: stop()
08-16 17:43:55.980  6575  6575 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:43:55.980  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.980  1017  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:43:55.980  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.980  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:43:55.980  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:55.980  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.980  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:43:55.990  1017  4314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.990  6575  6575 D HeadsetService: Received stop request...Stopping profile...
08-16 17:43:55.990  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:43:55.990  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:55.990  1017  4314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.990  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.990  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:43:55.990  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:43:55.990  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 17:43:55.990  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:55.990  1017  1562 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:55.990  1017  1562 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:55.990  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 17:43:55.990  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:55.990  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:55.990  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:43:55.990  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:55.990  6575  6913 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:55.990  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:43:56.000  1017  1292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:43:56.000  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.000  1297  1297 D HeadsetProfile: Bluetooth service disconnected
08-16 17:43:56.000  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.000  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.000  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:43:56.000  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 17:43:56.000  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:43:56.000  6575  6913 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:43:56.000  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:43:56.000  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.000  6575  6575 D A2dpService: Received stop request...Stopping profile...
08-16 17:43:56.000  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.000  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.000  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:43:56.000  6575  6926 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:56.010  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:56.010  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:43:56.010  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:43:56.010  6575  6913 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:43:56.010  6575  6913 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:43:56.010  6575  6913 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-16 17:43:56.010  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:56.010  1017  1017 D BluetoothA2dp: Proxy object disconnected
,08-16 17:43:56.010  1017  1017 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 17:43:56.010  2892  2892 D BluetoothA2dp: Proxy object disconnected
,08-16 17:43:56.010  6575  6575 D HidService: Received stop request...Stopping profile...
08-16 17:43:56.010  6575  6575 D HidService: Stopping Bluetooth HidService
08-16 17:43:56.010  1297  1297 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:56.010  1297  1297 D A2dpProfile: Bluetooth service disconnected
,08-16 17:43:56.010  6575  6575 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:43:56.010  6575  6575 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:43:56.010  6575  6575 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 17:43:56.010  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:56.020  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-16 17:43:56.020  6575  6575 D HealthService: Received stop request...Stopping profile...
,08-16 17:43:56.020  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:56.020  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-16 17:43:56.020  1297  1297 D BluetoothInputDevice: Proxy object disconnected
08-16 17:43:56.020  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:43:56.020  6575  6575 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:56.020  1297  1297 D HidProfile: Bluetooth service disconnected
,08-16 17:43:56.020  6575  6575 D PanService: Received stop request...Stopping profile...
08-16 17:43:56.020  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:43:56.020  1017  1017 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:43:56.020  1297  1297 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:43:56.020  6575  6575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:43:56.020  6575  6575 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:43:56.020  1297  1297 D PanProfile: Bluetooth service disconnected
,08-16 17:43:56.020  6575  6575 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:43:56.030  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:56.030  6575  6575 D SapService: Received stop request...Stopping profile...
,08-16 17:43:56.030  6575  6575 D SapService: Stopping Bluetooth SapService
08-16 17:43:56.030  6575  6575 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:43:56.030  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:43:56.030  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:43:56.030  6575  6575 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:43:56.030  6575  6575 D BluetoothA2dp: Proxy object disconnected
08-16 17:43:56.030  6575  6575 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-16 17:43:56.030  6575  6927 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 17:43:56.030  6575  6575 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:43:56.030  6575  6575 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-16 17:43:56.030  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:43:56.030  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.030  6575  6575 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:43:56.030  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:43:56.030  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.040  6575  6575 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.040  1297  1297 D BluetoothMap: Proxy object disconnected
08-16 17:43:56.040  1297  1297 D MapProfile: Bluetooth service disconnected
08-16 17:43:56.040  6575  6575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:43:56.040  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:43:56.040  1297  1297 D SapProfile: Bluetooth service disconnected
08-16 17:43:56.040  6575  6575 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:43:56.040  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:43:56.040  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.040  6575  6575 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.040  6575  6575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:43:56.040  6575  6575 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 17:43:56.040  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-16 17:43:56.040  6575  6575 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:43:56.040  6575  6575 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 17:43:56.040  6575  6575 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-16 17:43:56.040  6575  6575 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-16 17:43:56.040  6575  6575 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 17:43:56.040  6575  6913 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-16 17:43:56.040  6575  6913 D BluetoothAdapterProperties: Setting state to 10
,08-16 17:43:56.040  6575  6913 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:43:56.040  6575  6913 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:43:56.040  6575  6913 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 17:43:56.040  6575  6913 D BluetoothAdapterService: Autoconnection is available 
08-16 17:43:56.040  6575  6913 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:43:56.040  6575  6913 I BluetoothAdapterState: Entering OffState
,08-16 17:43:56.050  2892  3000 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:56.050  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.050  1017  1046 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.050  1297  1322 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:56.050  1297  1322 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.050  6575  6905 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.050  6575  6905 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.050  6575  6961 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:56.050  1455  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.050  1455  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.050  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:56.060  1297  1307 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:43:56.060  6282  6290 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.060  6282  6290 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:56.060  6282  6290 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-16 17:43:56.060  6282  6290 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:43:56.060  6282  6290 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:43:56.060  6282  6290 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:43:56.060  1936  2120 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.060  1936  2120 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.060  1297  1322 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:43:56.060  1297  6959 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:43:56.060  1441  1458 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.060  1441  1458 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.060  6446  6460 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.060  6446  6460 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.070  1297  1322 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 17:43:56.070  1297  1322 D Bluetoothsap: Unbinding service...
08-16 17:43:56.070  1175  1823 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.070  1175  1823 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:56.070  2892  2911 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:43:56.070  2892  2911 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:43:56.070  1297  6959 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:43:56.070  1429  6958 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:43:56.070  1429  6958 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:43:56.070  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-16 17:43:56.070  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:43:56.080  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:56.080  1017  1017 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:43:56.080  1017  1017 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:43:56.080  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:56.080  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:43:56.080  1175  1726 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:56.080  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:43:56.080  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-16 17:43:56.080  1175  1726 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:56.080  6575  6916 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 17:43:56.080  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:56.080  1175  1175 D BluetoothAdapter: 1040093843: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:56.080  6575  6575 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:43:56.080  6575  6575 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 17:43:56.080  6575  6575 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 17:43:56.080  1017  1805 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:43:56.090  1786  1786 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:43:56.090  1017  1217 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:43:56.090  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:43:56.090  1936  2132 D BluetoothAdapter: 1025780903: getState() :  mService = null. Returning STATE_OFF
08-16 17:43:56.090  1936  2132 D BluetoothAdapter: 1025780903: getState() :  mService = null. Returning STATE_OFF
,08-16 17:43:56.090  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:56.090  6575  6575 I art     : System.exit called, status: 0
08-16 17:43:56.090  6575  6575 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:43:56.090  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.090  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:43:56.090  1017  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:43:56.090  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.090  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.090  1017  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:43:56.100  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.100  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:43:56.100  1017  1481 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:43:56.100  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.100  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:43:56.100  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:43:56.100  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:43:56.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:56.120  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:43:56.120  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:43:56.130  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:43:56.130  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:43:56.130  1017  3104 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:43:56.130  1017  3104 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:43:56.140  1017  3104 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-16 17:43:56.140  1017  3104 W BroadcastQueue: android.os.TransactionTooLargeException
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-16 17:43:56.140  1017  3104 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:43:56.140  1017  3104 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-16 17:43:56.140  1017  3104 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:56.140  1017  3104 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:56.140  1017  3104 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:56.140  1017  3104 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:56.160  1017  3104 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6990 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-16 17:43:56.160  6990  6990 E Zygote  : MountEmulatedStorage(),
08-16 17:43:56.160  6990  6990 E Zygote  : v2,
08-16 17:43:56.160  6990  6990 I libpersona: KNOX_SDCARD checking this for 1002
,08-16 17:43:56.160  6990  6990 I libpersona: KNOX_SDCARD not a persona
,08-16 17:43:56.160  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:43:56.170  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:56.170  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 17:43:56.190  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:56.190  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:56.200  6990  6990 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:43:56.200  6990  6990 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:43:56.220  6990  6990 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding GattService
,08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding HeadsetService
08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding HidService
08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding HealthService
,08-16 17:43:56.250  6990  6990 D BtSettings.ProfileConfig: Adding PanService
08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding SapService
08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:43:56.260  6990  6990 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 17:43:56.260  6990  6990 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:43:56.260  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-16 17:43:56.260  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.260  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:43:56.260  1017  1481 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  1481 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:56.260  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  1481 D SettingsProvider: ret = -1
,08-16 17:43:56.260  1017  1562 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-16 17:43:56.260  1017  1562 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.260  1017  1562 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  1562 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  1562 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.260  1017  1562 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  1562 D SettingsProvider: ret = -1
,08-16 17:43:56.260  1017  1805 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService,
08-16 17:43:56.260  1017  1805 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:56.260  1017  1805 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-16 17:43:56.260  1017  1805 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  1805 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.260  1017  1805 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  1805 D SettingsProvider: ret = -1
08-16 17:43:56.260  1017  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 17:43:56.260  1017  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:56.260  1017  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  1219 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  1219 D SettingsProvider: selectionArgs: 1002
,08-16 17:43:56.260  1017  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:56.260  1017  1219 D SettingsProvider: ret = -1
,08-16 17:43:56.260  1017  3103 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-16 17:43:56.260  1017  3103 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:43:56.260  1017  3103 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  3103 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  3103 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.260  1017  3103 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  3103 D SettingsProvider: ret = -1
08-16 17:43:56.260  1017  3104 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:43:56.260  1017  3104 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.260  1017  3104 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  3104 D SettingsProvider: selectionArgs: false
08-16 17:43:56.260  1017  3104 D SettingsProvider: selectionArgs: 1002,
08-16 17:43:56.260  1017  3104 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  3104 D SettingsProvider: ret = -1
08-16 17:43:56.260  1017  1482 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 17:43:56.260  1017  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.260  1017  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  1482 D SettingsProvider: selectionArgs: false
,08-16 17:43:56.260  1017  1482 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.260  1017  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  1482 D SettingsProvider: ret = -1
08-16 17:43:56.260  1017  1029 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:43:56.260  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.260  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.260  1017  1029 D SettingsProvider: selectionArgs: false
,08-16 17:43:56.260  1017  1029 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.260  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.260  1017  1029 D SettingsProvider: ret = -1
08-16 17:43:56.270  1017  1804 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:43:56.270  1017  1804 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.270  1017  1804 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.270  1017  1804 D SettingsProvider: selectionArgs: false
,08-16 17:43:56.270  1017  1804 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.270  1017  1804 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.270  1017  1804 D SettingsProvider: ret = -1
08-16 17:43:56.270  1017  1292 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:43:56.270  1017  1292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.270  1017  1292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.270  1017  1292 D SettingsProvider: selectionArgs: false
,08-16 17:43:56.270  1017  1292 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.270  1017  1292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.270  1017  1292 D SettingsProvider: ret = -1
08-16 17:43:56.270  1017  4314 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:43:56.270  1017  4314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.270  1017  4314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.270  1017  4314 D SettingsProvider: selectionArgs: false
,08-16 17:43:56.270  1017  4314 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.270  1017  4314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:43:56.270  1017  4314 D SettingsProvider: ret = -1
08-16 17:43:56.270  1017  1217 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 17:43:56.270  1017  1217 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:43:56.270  1017  1217 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:43:56.270  1017  1217 D SettingsProvider: selectionArgs: false
08-16 17:43:56.270  1017  1217 D SettingsProvider: selectionArgs: 1002
08-16 17:43:56.270  1017  1217 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:43:56.270  1017  1217 D SettingsProvider: ret = -1
,08-16 17:43:56.280  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:43:56.280  1017  1805 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:43:56.280  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:43:56.290  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.290  1017  1805 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:56.290  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.290  1936  7006 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:43:56.290  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:43:56.300  1017  1804 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:43:56.300  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:43:56.300  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:43:56.300  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:43:56.310  1936  7006 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:43:56.430   286   286 E SMD     : DCD OFF,
,08-16 17:43:57.120   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:57.680  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop,
08-16 17:43:57.680  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:43:58.120   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:59.030  1017  1977 V SAMP_SPCM_test: CSC File load.. 
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control,
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-16 17:43:59.040  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-16 17:43:59.080  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-16 17:43:59.090  1017  1977 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm,
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-16 17:43:59.090  1017  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-16 17:43:59.090  1017  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-16 17:43:59.090  1017  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-16 17:43:59.090  1017  1977 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:43:59.090  1017  1977 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-16 17:43:59.110  7009  7009 E Zygote  : MountEmulatedStorage()
,08-16 17:43:59.110  7009  7009 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:43:59.110  7009  7009 E Zygote  : v2
08-16 17:43:59.110  7009  7009 I libpersona: KNOX_SDCARD not a persona
08-16 17:43:59.110  1017  1977 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7009 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:43:59.110  7009  7009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:43:59.110  7009  7009 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:43:59.110  7009  7009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:43:59.110   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:43:59.140  7009  7009 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:43:59.140  7009  7009 D ActivityThread: Added TimaKeyStore provider
,08-16 17:43:59.150  7009  7009 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:43:59.200  1017  1977 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-16 17:43:59.430   286   286 E SMD     : DCD OFF
,08-16 17:43:59.990  1017  1095 V AlarmManager: waitForAlarm result :8
,08-16 17:44:00.120   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:44:00.680  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 17:44:00.680  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19b55454 added. We now have 6 listener(s)
08-16 17:44:00.680  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 17:44:00.680  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:00.680  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3edeaffd added. We now have 7 listener(s)
,08-16 17:44:00.680  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:00.680  6282  6335 I System.out: IsBluetoothEnabled
08-16 17:44:00.680  6282  6335 D BluetoothAdapter: disable()
,08-16 17:44:00.690  1017  1805 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,08-16 17:44:00.690  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:00.690  6282  6335 D BluetoothAdapter: enable()
,08-16 17:44:00.690  1017  1030 W ActivityManager: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:44:00.700  1017  1030 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 17:44:00.700  1017  1030 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:44:00.700  1017  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:44:00.700  1017  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:44:00.700  1017  1030 D SettingsProvider: name = bluetooth_on
,08-16 17:44:00.710  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:44:00.710  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:44:00.710  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-16 17:44:00.710  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 17:44:00.730  6990  6990 D BluetoothAdapterState: make
,08-16 17:44:00.730  6990  6990 I bluedroid: init
,08-16 17:44:00.740  6990  7028 I BluetoothAdapterState: Entering OffState
,08-16 17:44:00.740  6990  6990 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:44:00.740  6990  6990 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:44:00.740  6990  6990 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:44:00.740  6990  6990 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:44:00.740  6990  6990 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:44:00.740  6990  6990 I bluedroid: get_profile_interface socket
08-16 17:44:00.740  6990  6990 I bluedroid: get_profile_interface map_client
08-16 17:44:00.740  6990  7031 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:44:00.740  6990  6990 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:44:00.750  6990  7031 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:44:00.750  6990  7031 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:44:00.750  6990  7031 I bluedroid: getModelRssiValues
,08-16 17:44:00.750  6990  7031 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:44:00.750  6990  7031 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:44:00.750  1017  1017 D SettingsProvider: name = bluetooth_name
,08-16 17:44:00.750  6990  7031 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:44:00.760  6990  6990 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:00.760  1017  1292 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:44:00.760  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.760  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.760  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.760  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.760  6990  7000 I bluedroid: config_hci_snoop_log
,08-16 17:44:00.760  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 17:44:00.770  1017  1046 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:44:00.770  1017  1046 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 17:44:00.770  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:44:00.770  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:44:00.770  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:44:00.770  1017  1046 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:44:00.770  6990  6990 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:44:00.770  1017  1046 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:44:00.780  6990  7028 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 17:44:00.780  6990  7028 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:44:00.780  6990  7028 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:44:00.780  6990  7028 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:44:00.780  6990  7028 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:44:00.780  6990  7028 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:44:00.780  6990  7028 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:44:00.780  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:00.780  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:44:00.790  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:44:00.790  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:00.790  6990  7028 D BluetoothSecureManager: getInstant: null
08-16 17:44:00.790  6990  7028 D BluetoothSecureManager: calling getMethod for getService
08-16 17:44:00.790  6990  7028 D BluetoothSecureManager: calling getService
08-16 17:44:00.790  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-16 17:44:00.790  6990  7028 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@16e16c06
,08-16 17:44:00.790  1017  1219 D BluetoothSecureManagerService: isSecureModeEnabled
,08-16 17:44:00.790  1017  1219 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:44:00.790  1786  1786 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 17:44:00.790  6990  7028 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:44:00.790  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:44:00.790  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 17:44:00.790  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:44:00.790  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:44:00.790  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:44:00.790  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:44:00.790  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:44:00.790  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 17:44:00.790  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:44:00.800  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:00.800  1017  1030 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:44:00.800  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:44:00.800  6990  7028 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-16 17:44:00.800  1017  1481 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:44:00.800  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:00.800  6990  7028 D BluetoothBondStateMachine: make
,08-16 17:44:00.800  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:44:00.810  1017  3104 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:44:00.810  1017  3104 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.810  1017  1046 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:44:00.810  1017  3104 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.810  1017  3104 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:00.810  1017  3104 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:00.810  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:44:00.810  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:44:00.810  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:44:00.810  6990  7032 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:44:00.820  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:44:00.820  1017  1805 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:44:00.820  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.820  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.820  1017  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.820  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.820  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:44:00.820  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:44:00.820  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:44:00.820  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:44:00.820  1017  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:00.820  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:44:00.820  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:44:00.820  6990  6990 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:44:00.820  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.820  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.820  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.820  6990  6990 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:44:00.820  6990  6990 D BtGatt.GattService: start()
08-16 17:44:00.820  6990  6990 D BtGatt.GattService: start()
08-16 17:44:00.820  6990  6990 I bluedroid: get_profile_interface gatt
,08-16 17:44:00.820  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:44:00.820  6990  6990 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:44:00.830  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:44:00.830  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:44:00.830  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:44:00.830  1017  4314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:00.830  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.830  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.830  1017  4314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.830  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.830  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:44:00.830  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:44:00.830  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:44:00.840  1017  1514 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:44:00.840  1017  1514 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.840  1017  1514 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.840  1017  1514 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.840  1017  1514 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.840  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:44:00.840  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:44:00.840  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:44:00.840  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:44:00.850  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.850  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.850  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.850  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.850  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 17:44:00.850  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:44:00.850  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:44:00.850  1017  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:00.850  1017  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.850  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.850  1017  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.850  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.850  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:44:00.850  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:44:00.850  6990  7028 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:44:00.850  1017  3103 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:00.860  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.860  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.860  6990  6990 D BtGatt.GattService: mStartError = false
,08-16 17:44:00.860  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:00.860  6990  6990 D HeadsetService: Received start request. Starting profile...
,08-16 17:44:00.860  6990  6990 D HeadsetService: start()
,08-16 17:44:00.860  6990  6990 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:44:00.860  6990  6990 D HeadsetStateMachine: make
,08-16 17:44:00.860  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:44:00.860  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.870  6990  6990 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 17:44:00.870  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 17:44:00.870  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:44:00.870  6990  7028 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:44:00.870  1017  1805 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:00.870  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.870  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:00.870  1017  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.870  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:00.880  1017  1509 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:44:00.880  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:44:00.880  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:44:00.880  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:44:00.880  6990  7028 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:44:00.880  6990  7028 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:44:00.880  6990  7028 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:44:00.880  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.880  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.880  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.880  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:44:00.880  1017  3103 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-16 17:44:00.880  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:44:00.880  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:00.880  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:00.880  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:44:00.880  6990  6990 I bluedroid: get_profile_interface handsfree
,08-16 17:44:00.900  6990  6990 I DualScoManager: Instantiating Dual Sco Manager,
08-16 17:44:00.900  6990  6990 I DualScoManager: Set HeadsetServiceHelper
,08-16 17:44:00.900  6990  6990 D BluetoothAtMessage: createCMTIContentObservers
,08-16 17:44:00.900  1017  1562 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 17:44:00.900  1017  1562 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:44:00.900  1017  1562 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:44:00.900  1017  1562 D SettingsProvider: selectionArgs: false
08-16 17:44:00.900  1017  1562 D SettingsProvider: selectionArgs: 1002
08-16 17:44:00.900  1017  1562 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:44:00.900  1017  1562 D SettingsProvider: ret = -1
,08-16 17:44:00.900  6990  7036 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:44:00.900  6990  6990 D HeadsetService: mStartError = false
08-16 17:44:00.900  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:00.900  6990  6990 D A2dpService: Received start request. Starting profile...
08-16 17:44:00.900  6990  6990 D A2dpService: start()
,08-16 17:44:00.900  6990  6990 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:44:00.910  6990  6990 I bluedroid: get_profile_interface avrcp
,08-16 17:44:00.910  6990  7036 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 17:44:00.910  6990  7036 D HeadsetStateMachine: map size, before remove : 0
,08-16 17:44:00.910  6990  7036 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:44:00.910  6990  6990 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:44:00.930  6990  6990 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:44:00.940  6990  6990 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:44:00.940  6990  6990 D A2dpStateMachine: make
,08-16 17:44:00.940  6990  7040 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:44:00.940  6990  6990 I bluedroid: get_profile_interface a2dp
08-16 17:44:00.940  6990  7042 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 17:44:00.940  6990  6990 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:44:00.950  6990  6990 D A2dpService: mStartError = false
08-16 17:44:00.950  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:44:00.950  6990  7041 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:44:00.950  6990  6990 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:44:00.950  6990  6990 D HidService: Received start request. Starting profile...
08-16 17:44:00.950  6990  6990 D HidService: start()
08-16 17:44:00.950  6990  6990 I bluedroid: get_profile_interface hidhost
08-16 17:44:00.950  6990  6990 D HidService: setHidService(): set to: null
08-16 17:44:00.950  6990  6990 D HidService: mStartError = false
08-16 17:44:00.950  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:00.950  6990  6990 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:44:00.960  6990  6990 D HealthService: Received start request. Starting profile...
08-16 17:44:00.960  6990  6990 D HealthService: start()
,08-16 17:44:00.960  6990  6990 I bluedroid: get_profile_interface health
08-16 17:44:00.960  6990  6990 D HealthService: mStartError = false
08-16 17:44:00.960  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:00.960  6990  6990 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:44:00.960  6990  6990 D PanService: Received start request. Starting profile...
08-16 17:44:00.960  6990  6990 D PanService: start()
08-16 17:44:00.960  6990  6990 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:44:00.960  6990  6990 I bluedroid: get_profile_interface pan
,08-16 17:44:00.960  6990  6990 D PanService: mStartError = false
08-16 17:44:00.960  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:00.970  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:44:00.970  6990  6990 D BluetoothMapService: Received start request. Starting profile...
08-16 17:44:00.970  6990  6990 D BluetoothMapService: start()
,08-16 17:44:00.970  6990  7040 D BluetoothMediaBrowser: no now playing list
08-16 17:44:00.970  6990  6990 D BluetoothMapService: mStartError = false
08-16 17:44:00.970  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:44:00.970  6990  7040 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:44:00.970  6990  6990 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 17:44:00.970  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:44:00.970  6990  6990 D SapService: Received start request. Starting profile...
08-16 17:44:00.970  6990  6990 D SapService: start()
08-16 17:44:00.970  6990  6990 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:44:00.970  6990  6990 I bluedroid: get_profile_interface sap
08-16 17:44:00.970  6990  6990 D SapService: mStartError = false
08-16 17:44:00.970  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:44:00.970  6990  6990 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:44:00.970  1429  1443 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:44:00.980  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:44:00.980  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:44:00.980  1429  1443 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:44:00.980  6990  6990 D HeadsetStateMachine: Proxy object connected
,08-16 17:44:00.980  6990  6990 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:44:00.980  6990  6990 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 17:44:00.980  6990  6990 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 17:44:00.980  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:44:00.980  6990  6990 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:44:00.980  6990  6990 D BluetoothA2dp: Proxy object connected
08-16 17:44:00.980  6990  6990 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:44:00.980  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:44:00.980  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:44:00.980  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:44:00.980  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:44:00.980  6990  7036 D HeadsetStateMachine: Disconnected process message: 11
08-16 17:44:00.980  6990  7036 D HeadsetStateMachine: Disconnected process message: 18
08-16 17:44:00.980  6990  7036 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:44:00.980  6990  7036 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:44:00.980  6990  7036 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:44:00.980  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:44:01.010  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:44:01.010  6990  6990 E BluetoothAdapterService(191144752): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:44:01.020  6990  7028 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-16 17:44:01.020  6990  7028 I bluedroid: enable
,08-16 17:44:01.020  6990  7028 I bt_hci_bdroid: init
,08-16 17:44:01.020  6990  7028 I bt_vendor: bt-vendor : init
08-16 17:44:01.020  6990  7028 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:44:01.020  6990  7028 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 17:44:01.020  6990  7028 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 17:44:01.020  6990  7028 D bt_userial_mct: userial_init
08-16 17:44:01.020  6990  7046 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 17:44:01.020  6990  7028 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:44:01.020  6990  7028 I bt_vendor: Starting hciattach daemon
08-16 17:44:01.020  6990  7028 I bt_vendor: try to set false
,08-16 17:44:01.020  6990  7028 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 17:44:01.020  6990  7028 I bt_vendor: Starting hciattach daemon
08-16 17:44:01.020  6990  7028 I bt_vendor: try to set true
,08-16 17:44:01.040  7050  7050 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:44:01.090  7056  7056 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:44:01.100  7057  7057 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:44:01.110  7059  7059 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:44:01.110   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-16 17:44:01.120  7060  7060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:44:01.130  7061  7061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:44:01.140  7062  7062 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:44:01.340  7065  7065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 17:44:01.350  7066  7066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:44:01.380  6990  7028 I bt_vendor: bluetooth satus is on
,08-16 17:44:01.380  6990  7048 D bt_userial_mct: userial_open(port:0)
08-16 17:44:01.380  6990  7048 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:44:01.380  6990  7048 I bt_vendor: Done intiailizing UART,
,08-16 17:44:01.380  6990  7048 I bt_vendor: Done intiailizing UART
08-16 17:44:01.380  6990  7048 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 17:44:01.380  6990  7048 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-16 17:44:01.390  6990  7068 D bt_userial_mct: Entering userial_read_thread(),
,08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:44:01.390  6990  7046 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:44:01.400  6990  7046 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 17:44:01.500  6990  7046 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:44:01.500  6990  7046 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40946e9 
,08-16 17:44:01.500  6990  7046 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40946e9 
,08-16 17:44:01.520  6990  7031 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:44:01.520  6990  7031 E bt-btif : Calling BTA_HhEnable
,08-16 17:44:01.520  6990  7031 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:44:01.520  6990  7031 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:44:01.520  6990  7031 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:44:01.520  6990  7031 I bluedroid: getModelRssiValues
,08-16 17:44:01.520  6990  7031 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:44:01.520  6990  7031 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:44:01.530  6990  7031 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:44:01.530  1017  1017 D SettingsProvider: name = bluetooth_name
,08-16 17:44:01.530  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:01.540  6990  7031 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:44:01.540  6990  7031 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:44:01.540  6990  7031 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:44:01.540  6990  7031 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-16 17:44:01.540  6990  7031 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-16 17:44:01.540  6990  7031 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-16 17:44:01.540  6990  7031 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-16 17:44:01.540  6990  7031 E bt-btif : btif_sock_init: !vhci_init
,08-16 17:44:01.540  6990  7031 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 17:44:01.540  6990  7068 E bt_mct  : hci lib postload completed,
08-16 17:44:01.540  6990  7031 D IOP_DB_BT: db_open: db_open : handle 3028316176l, read 13894 bytes onto local cache
08-16 17:44:01.540  6990  7031 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:44:01.550  6990  7031 D IOP_DB_BT: db_query: result 1,
08-16 17:44:01.550  6990  7031 I         : iop_db_open: iop_db_open status 0,
08-16 17:44:01.550  6990  7031 D bte_conf: Device ID record 1 : primary
08-16 17:44:01.550  6990  7031 D bte_conf:   vendorId            = 0075
08-16 17:44:01.550  6990  7031 D bte_conf:   vendorIdSource      = 0001
08-16 17:44:01.550  6990  7031 D bte_conf:   product             = 0100
08-16 17:44:01.550  6990  7031 D bte_conf:   version             = 0200
08-16 17:44:01.550  6990  7031 D bte_conf:   clientExecutableURL = 
08-16 17:44:01.550  6990  7031 D bte_conf:   serviceDescription  = 
08-16 17:44:01.550  6990  7031 D bte_conf:   documentationURL    = 
08-16 17:44:01.550  6990  7031 D bte_conf: bte_load_did_conf no section named DID2.
08-16 17:44:01.550  6990  7031 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:44:01.550  6990  7028 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:44:01.550  6990  7028 D BluetoothAdapterProperties: ScanMode =  20
,08-16 17:44:01.550  6990  7028 D BluetoothAdapterProperties: State =  11
,08-16 17:44:01.550  1017  1804 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:44:01.550  6990  7028 D BluetoothAdapterProperties: Setting state to 12
,08-16 17:44:01.550  6990  7028 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:01.560  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:01.560  6990  7031 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:44:01.560  6990  7031 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:44:01.560  6990  7031 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:44:01.560  1017  1481 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-16 17:44:01.560  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:44:01.560  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:44:01.560  1017  1481 D SettingsProvider: selectionArgs: false
08-16 17:44:01.560  1017  1481 D SettingsProvider: selectionArgs: 1002
08-16 17:44:01.560  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:44:01.560  1017  1481 D SettingsProvider: ret = -1
,08-16 17:44:01.560  6990  7028 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:44:01.560  6990  7028 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:44:01.570  1017  1292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:01.570  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.570  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.570  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:44:01.570  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.570  6990  7028 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:44:01.570  1017  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:44:01.570  6990  7028 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:44:01.570  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:44:01.570  6990  7028 D BluetoothAdapterService: starting service from this receiver
,08-16 17:44:01.580  2892  2911 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:01.580  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:01.580  2892  2911 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.600  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.600  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.600  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.600  6990  7028 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:44:01.600  6990  6990 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:01.710  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:01.710  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:01.720  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:01.720  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@391e34f2 added. We now have 8 listener(s)
08-16 17:44:01.720  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:01.720  1017  1804 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:44:01.720  1017  1804 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 17:44:01.720  1017  1804 D SecContentProvider2: mCursor = null
,08-16 17:44:01.720  1017  1804 D WifiService: setWifiEnabled: false pid=6282, uid=10155
,08-16 17:44:01.720  1017  1804 D SettingsProvider: name = wifi_on
,08-16 17:44:01.730  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:01.730  1017  1514 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:44:01.730  1017  1514 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-16 17:44:01.730  1017  1514 D SecContentProvider2: mCursor = null
,08-16 17:44:01.730  1017  1514 D WifiService: setWifiEnabled: true pid=6282, uid=10155
,08-16 17:44:01.730  1017  1514 W ActivityManager: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:44:01.730  1017  1514 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:44:01.730  1017  1514 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6282, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:44:01.730  1017  1514 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:44:01.730  1017  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:44:01.730  1017  1514 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:44:01.730  1017  1514 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:44:01.730  1017  1514 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:44:01.730  1017  1514 D SettingsProvider: name = wifi_on
,08-16 17:44:01.740  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:44:01.760  1017  1046 I art     : Explicit concurrent mark sweep GC freed 34243(2002KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 27MB/41MB, paused 3.253ms total 178.579ms
08-16 17:44:01.760  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:44:01.760  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.760  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.760  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.760  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.760  2892  2892 D BluetoothA2dp: Proxy object connected
,08-16 17:44:01.770  1429  6958 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.770  6990  6990 I BluetoothPbapService: Handler(): got msg=1
,08-16 17:44:01.770  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.770  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.770  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.770  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.770  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 17:44:01.770  1017  1292 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:44:01.770  1429  6958 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.770  1017  1046 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.770  1017  1046 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.770  1297  1307 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.770  1297  1307 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.770  1297  1322 D BluetoothPan: Binding service...
,08-16 17:44:01.770  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:44:01.770  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.770  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.770  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.770  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.780  1429  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.780  1297  1297 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:44:01.780  1297  1297 D PanProfile: Bluetooth service connected
08-16 17:44:01.780  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.780  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.780  6990  7076 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:44:01.780  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.780  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.780  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.780  1429  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.780  6990  7071 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.780  6990  7071 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:44:01.780  1017  1046 D BluetoothPan: Binding service...
,08-16 17:44:01.780  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:44:01.780  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.780  1017  1046 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:44:01.790  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:44:01.790  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.790  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.790  1017  1046 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.790  1455  1466 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.790  1455  1466 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:44:01.790  6990  7076 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:44:01.790  6990  7076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:44:01.790  2892  2911 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.790  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.790  1017  1046 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.790  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.790  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:44:01.790  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth,
08-16 17:44:01.790  6990  7076 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-16 17:44:01.790  6990  7076 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:44:01.790  6990  7076 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:44:01.790  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:44:01.790  6990  7076 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@11df12b5
08-16 17:44:01.790  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.790  6990  7076 D BluetoothSocket: channel: 19
08-16 17:44:01.790  6990  7076 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-16 17:44:01.790  2892  2911 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:44:01.790  1017  1046 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:44:01.790  1017  1046 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-16 17:44:01.790  1297  6959 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:44:01.790  1017  1017 D BluetoothA2dp: Proxy object connected
,08-16 17:44:01.790  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-16 17:44:01.790  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.790  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.790  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.790  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.800  1297  1297 D BluetoothMap: Proxy object connected
,08-16 17:44:01.800  1297  1297 D MapProfile: Bluetooth service connected
08-16 17:44:01.800  1297  1297 D BluetoothMap: getConnectedDevices()
08-16 17:44:01.800  1429  1443 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.800  1017  1046 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.800  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.800  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.800  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.800  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.800  1429  1443 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.800  6282  6296 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:44:01.800  6282  6296 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:44:01.800  6990  7002 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:44:01.800  1936  1946 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:44:01.800  1936  1946 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:44:01.800  1297  1307 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:44:01.800  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-16 17:44:01.800  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.810  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.810  1297  1297 D BluetoothPbap: Proxy object connected
,08-16 17:44:01.810  1455  1676 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.810  1297  1297 D PbapServerProfile: Bluetooth service connected
08-16 17:44:01.810  1017  1046 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.810  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.810  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.810  1455  1676 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.810  1297  1322 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:44:01.810  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 17:44:01.810  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.810  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.810  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.820  1441  1458 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.820  1441  1458 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.820  1297  1297 D BluetoothInputDevice: Proxy object connected
,08-16 17:44:01.820  1297  1307 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:44:01.820  1297  1297 D HidProfile: Bluetooth service connected
,08-16 17:44:01.820  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:44:01.820  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:44:01.820  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.820  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.820  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.820  1297  1307 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:44:01.820  6446  6461 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.820  6446  6461 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.820  1297  6959 D Bluetoothsap: onBluetoothStateChange: up=true
,08-16 17:44:01.820  1297  6959 D Bluetoothsap: Binding service...
,08-16 17:44:01.820  1297  6959 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:44:01.820  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 17:44:01.820  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.830  1297  1297 D HeadsetProfile: Bluetooth service connected
,08-16 17:44:01.830  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.830  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.830  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.830  1297  6959 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 17:44:01.830  1175  1188 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:44:01.830  1175  1188 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.830  2892  2911 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:44:01.830  2892  2911 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:44:01.830  1297  1307 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:44:01.830  1297  1297 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-16 17:44:01.830  1297  1307 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:44:01.830  1297  1297 D SapProfile: Bluetooth service connected
08-16 17:44:01.830  1017  1046 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:44:01.830  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-16 17:44:01.830  1297  1297 D Bluetoothsap: getConnectedDevices()
,08-16 17:44:01.830  1017  1046 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.830  1017  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.830  1017  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.830  1429  6958 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:44:01.830  1429  6958 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:44:01.830  1017  1046 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:44:01.830  1017  1046 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:44:01.830  1297  1297 D BluetoothA2dp: Proxy object connected
,08-16 17:44:01.840  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:01.840  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-16 17:44:01.840  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:44:01.840  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:44:01.840  1429  1429 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1c6d49c1, true
08-16 17:44:01.850  1297  1297 D A2dpProfile: Bluetooth service connected
,08-16 17:44:01.850  1429  1429 D BluetoothHeadset: registerMessageListener,
,08-16 17:44:01.850  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:44:01.850  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:44:01.850  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-16 17:44:01.850  1786  1786 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:44:01.850  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:44:01.850  1017  1029 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:44:01.860  1017  3103 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 17:44:01.860  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:44:01.860  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:44:01.860  1175  1726 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:44:01.860  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:01.870  6990  7071 D HeadsetService: registerMessageListener
,08-16 17:44:01.870  1297  1297 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:44:01.870  1017  1804 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:44:01.870  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.870  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.870  1017  1804 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.870  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:44:01.870  6990  7071 D HeadsetService: registerMessageListener
08-16 17:44:01.870  6990  7036 D HeadsetStateMachine: Disconnected process message: 70
,08-16 17:44:01.870  1429  1429 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:44:01.870  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 17:44:01.870  6990  7036 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ac4d4a
,08-16 17:44:01.870  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-16 17:44:01.870  1297  1297 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 17:44:01.870  1429  1429 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 17:44:01.870  1297  1297 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:44:01.870  1429  1429 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:44:01.870  1297  1297 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-16 17:44:01.870  1297  1297 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-16 17:44:01.870  6990  7079 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:44:01.880  6990  7036 D HeadsetStateMachine: Disconnected process message: 9
,08-16 17:44:01.880  6990  7036 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:44:01.890   281   733 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:44:01.890   281   733 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:44:01.890   281   733 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:44:01.890   281   733 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:44:01.890   281   733 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:44:01.890   281   733 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:44:01.890   281   733 V audio_hw_primary: adev_set_parameters: exit
08-16 17:44:01.890  6990  7036 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:44:01.890  6990  7079 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:44:01.890  6990  7079 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:01.890  1297  1297 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:44:01.890  1017  3103 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:44:01.890  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.890  6990  7079 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-16 17:44:01.890  6990  7079 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:44:01.890  6990  7079 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-16 17:44:01.890  6990  7079 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a25a4bb
08-16 17:44:01.890  6990  7079 D BluetoothSocket: channel: 5
08-16 17:44:01.890  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.890  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.890  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:44:01.900  1297  1297 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:44:01.900  1297  1297 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:44:01.910  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:44:01.910  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:44:01.920  6990  6990 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
08-16 17:44:01.920  6990  6990 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:44:01.920  1017  1805 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:44:01.920  1017  1805 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.930  1017  1805 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.930  1017  1805 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:01.930  1017  1805 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:44:01.940  1936  1936 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:44:01.940  1017  3103 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:44:01.940  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:44:01.950  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.950  1017  3103 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.950  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:01.950  1936  7091 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:44:01.950  1936  1936 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:44:01.960  1017  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:44:01.960  1017  1219 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:44:01.960  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:01.960  1017  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:44:01.960  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:01.970  6990  7095 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:44:01.970  6990  7095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:44:01.970  6990  7095 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-16 17:44:01.970  6990  7095 D BluetoothSocket: bindListen(), new LocalSocket 
,08-16 17:44:01.970  6990  7095 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:44:01.970  6990  7095 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@35ffd197
08-16 17:44:01.970  6990  7095 D BluetoothSocket: channel: 12
08-16 17:44:01.970  6990  7095 I BtOppRfcommListener: Accept thread started.
,08-16 17:44:01.980  1017  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:44:01.980  1017  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:01.980  1017  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:44:01.980  1017  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:44:01.980  1936  7091 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:44:02.110  1017  1044 D Tethering: interfaceAdded wlan0,
,08-16 17:44:02.110  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:44:02.110  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:44:02.120  1017  1131 E Tethering: No numeric data
,08-16 17:44:02.120  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:44:02.120  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-16 17:44:02.120  1017  1131 D Tethering: clearTetheredNotification()
,08-16 17:44:02.120  1017  1131 D Tethering: InitialState.processMessage what=4
,08-16 17:44:02.120  1017  1044 D Tethering: interfaceAdded p2p0,
08-16 17:44:02.120  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit,
,08-16 17:44:02.120  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:44:02.120  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:02.120  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:44:02.120  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
08-16 17:44:02.120  1175  1175 D HotspotTile: updateTetherState():false, false
,08-16 17:44:02.130  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:02.130  1017  1125 V NetworkStats: performPollLocked() took 10ms
08-16 17:44:02.140  1017  1131 E Tethering: No numeric data,
08-16 17:44:02.140  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:44:02.140  1017  1131 D Tethering: clearTetheredNotification()
,08-16 17:44:02.140   276   972 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-16 17:44:02.140  1017  1044 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 17:44:02.140   276   972 D SoftapController: Softap fwReload - Ok
,08-16 17:44:02.140  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:44:02.140  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:44:02.140  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:44:02.140  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:44:02.140  1175  1175 D HotspotTile: updateTetherState():false, false
,08-16 17:44:02.140   276   972 D CommandListener: Setting iface cfg
08-16 17:44:02.150   276   972 D CommandListener: Trying to bring down wlan0
,08-16 17:44:02.150  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:02.150  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:44:02.150  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:02.150  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:02.150   276   972 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:44:02.150  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:02.150  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:44:02.150  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:02.150  1017  1125 V NetworkStats: performPollLocked() took 6ms
08-16 17:44:02.150  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant,
08-16 17:44:02.160  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:02.160  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:02.160  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:44:02.170  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:44:02.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:44:02.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:02.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:02.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:02.170  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:02.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:44:02.170  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-16 17:44:02.170  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 17:44:02.170  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:44:02.170  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-16 17:44:02.170  1175  1175 D HotspotTile: onReceive : 2, 0
08-16 17:44:02.170  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:02.180  1017  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:02.180  1017  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:44:02.180  1017  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:02.180  1017  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:44:02.180  1017  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:44:02.180  3709  3709 I Hs20UtilService: Starting #19
,08-16 17:44:02.180  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:44:02.180  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:44:02.180  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:44:02.180  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:44:02.180  3709  3725 I Hs20UtilService: Message received 5011
,08-16 17:44:02.210  7097  7097 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-16 17:44:02.210  7097  7097 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:44:02.210  7097  7097 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:44:02.220  7097  7097 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-16 17:44:02.220   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7097
08-16 17:44:02.220   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-16 17:44:02.220  7097  7097 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:44:02.220  7097  7097 I wpa_supplicant: ssSupport state is = 1
08-16 17:44:02.220  7097  7097 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:44:02.220  7097  7097 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-16 17:44:02.220   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7097
08-16 17:44:02.220   373   373 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-16 17:44:02.370   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-16 17:44:02.370  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,08-16 17:44:02.420   286   286 E SMD     : DCD OFF
,08-16 17:44:02.440  7097  7097 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 17:44:02.440  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 17:44:02.450  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 17:44:02.450   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7097
08-16 17:44:02.450   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-16 17:44:02.450  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 17:44:02.450  7097  7097 I wpa_supplicant: ssSupport state is = 1
08-16 17:44:02.450  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:44:02.450  7097  7097 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:44:02.450  7097  7097 E wpa_supplicant: SIM READ ERROR
08-16 17:44:02.450  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:44:02.450  7097  7097 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:44:02.450  7097  7097 E wpa_supplicant: SIM READ ERROR,
08-16 17:44:02.450  7097  7097 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:44:02.450  7097  7097 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:44:02.450  7097  7097 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:44:02.450  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:44:02.450  7097  7097 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:44:02.450  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:44:02.450  7097  7097 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:44:02.460  7097  7097 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-16 17:44:02.460  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:44:02.460  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:44:02.460  1017  1044 D Tethering: interfaceStatusChanged wlan0, false,
,08-16 17:44:02.540  7097  7097 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 17:44:02.770  1017  3104 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:44:02.780  1017  3104 D BatteryService: level:94, scale:100, status:2, health:2, present:true, voltage: 4186, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 17:44:02.780  1017  3104 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 17:44:02.780  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-16 17:44:02.780  1017  3104 D BatteryService: stay LED for charging
,08-16 17:44:02.780  1017  1017 I MotionRecognitionService: Plugged
,08-16 17:44:02.780  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:44:02.780  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-16 17:44:02.780  1419  1419 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:44:02.780  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-16 17:44:02.780  1419  1419 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 94
,08-16 17:44:02.790  6990  6990 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:44:02.790  6990  7036 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:44:02.810  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2,
08-16 17:44:02.810  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
08-16 17:44:02.810  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:94 status:2 health:2
,08-16 17:44:02.830  7097  7097 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:44:02.830  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-16 17:44:02.850  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 17:44:02.850   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7097
08-16 17:44:02.850   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
,08-16 17:44:02.850  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 17:44:02.850  7097  7097 I wpa_supplicant: ssSupport state is = 1
08-16 17:44:02.850  7097  7097 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 17:44:02.850  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 17:44:02.870  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 17:44:02.870   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7097
08-16 17:44:02.870   373   373 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-16 17:44:02.870  7097  7097 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 17:44:02.870  7097  7097 I wpa_supplicant: ssSupport state is = 1,
08-16 17:44:02.870  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-16 17:44:02.870  7097  7097 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:44:02.870  7097  7097 E wpa_supplicant: SIM READ ERROR
,08-16 17:44:02.870  7097  7097 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:44:02.870  7097  7097 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:44:02.870  7097  7097 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:44:02.870  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:44:02.870  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:44:02.870  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:44:02.880  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:44:02.880  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:44:02.880  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:44:02.960  7097  7097 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:44:02.960  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:44:03.020  7097  7097 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-16 17:44:03.020  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-16 17:44:03.020  7097  7097 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:44:03.030  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-16 17:44:03.030  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:44:03.040  7097  7097 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 17:44:03.040  7097  7097 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:44:03.040  7097  7097 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:44:03.040  7097  7097 E wpa_supplicant: SIM READ ERROR,
08-16 17:44:03.040  7097  7097 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:44:03.060  7097  7097 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 17:44:03.070  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210],
,08-16 17:44:03.070  7097  7097 I wpa_supplicant: Skip scan - bUseNetwork false
08-16 17:44:03.070  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:03.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:44:03.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:03.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:03.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:03.070  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:03.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:44:03.070  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-16 17:44:03.070  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:44:03.070  1297  1297 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:44:03.070  1175  1726 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:44:03.080  1017  1128 D WifiConfigStore: Loading config and enabling all networks ,
08-16 17:44:03.080  1175  1175 D HotspotTile: onReceive : 3, 0
08-16 17:44:03.080  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:03.080  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:44:03.080  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:03.080  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:44:03.080  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:44:03.080  3709  3709 I Hs20UtilService: Starting #20
,08-16 17:44:03.080  3709  3725 I Hs20UtilService: Message received 5011
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:03.080  6282  6282 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:03.090  1017  1128 E WifiConfigStore: Not a HS20
,08-16 17:44:03.090  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:44:03.090  6558  6558 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:44:03.090  6558  6558 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:44:03.090  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 17:44:03.090  6558  6558 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:44:03.090  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 17:44:03.090  6282  6282 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:03.090  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:44:03.090  7097  7097 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:44:03.090  7097  7097 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:44:03.090  7097  7097 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:44:03.090  7097  7097 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:44:03.090  7097  7097 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:44:03.090  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:44:03.090  7097  7097 I wpa_supplicant: First Scan Start
08-16 17:44:03.090  7097  7097 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 17:44:03.100  6481  6481 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-16 17:44:03.100  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-16 17:44:03.100  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:44:03.100  1017  1128 I WifiNative-HAL: startHal
08-16 17:44:03.100  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9c8d688c
08-16 17:44:03.100  1017  1128 I WifiNative-HAL: Could not start hal
,08-16 17:44:03.110  1017  1044 D Tethering: interfaceLinkStateChanged p2p0, false
,08-16 17:44:03.110  1017  1044 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:44:03.110  1017  1128 E WifiNative-wlan0: do suspend true
,08-16 17:44:03.110  1017  1044 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:44:03.110  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-16 17:44:03.110  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 17:44:03.110  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-16 17:44:03.110  1017  1150 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:44:03.110  1017  1150 I WifiNative-HAL: startHal
08-16 17:44:03.110  1017  1150 E wifi    : getStaticLongField sWifiHalHandle 0x9dee19bc
08-16 17:44:03.110  1017  1150 I WifiNative-HAL: Could not start hal
08-16 17:44:03.110  1017  1150 E WifiScanningService: could not start HAL
08-16 17:44:03.110  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-16 17:44:03.110  1017  1151 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:44:03.110   276   972 D CommandListener: Setting iface cfg
08-16 17:44:03.110   276   972 D CommandListener: Trying to bring up p2p0
08-16 17:44:03.110  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:44:03.110  1017  1127 D WifiP2pService: P2pEnablingState
08-16 17:44:03.110  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:44:03.110  1017  1127 D WifiP2pService: P2p socket connection successful
,08-16 17:44:03.110  1017  1127 D WifiP2pService: P2pEnabledState
08-16 17:44:03.110  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:44:03.110  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:44:03.110  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:44:03.110  1017  1128 E WifiNative-wlan0: invaild command id : 215
08-16 17:44:03.110  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:44:03.110  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:44:03.110  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:44:03.110  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-16 17:44:03.120  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:44:03.120  1017  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:44:03.120  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:44:03.120  1017  1047 D WifiDisplayController: disconnect
,08-16 17:44:03.120  1017  1047 D WifiDisplayController: updateConnection
08-16 17:44:03.120  1017  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:44:03.120  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress,
,08-16 17:44:03.120  1017  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:44:03.120  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-16 17:44:03.120  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:44:03.120  1017  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:44:03.120  1017  1127 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 17:44:03.120  7097  7097 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-16 17:44:03.120  1017  1047 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:44:03.120  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:44:03.120  1017  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:44:03.120  1017  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:44:03.120  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:44:03.130  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:44:03.130  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:44:03.130  1017  1481 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:44:03.130  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:44:03.130  1017  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1,
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  secondary type: null
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  wps: 0
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  grpcapab: 0
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  devcapab: 0
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  status: 3
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  wfdInfo: null
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  groupownerAddress: null
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  GOdeviceName: null
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  interfaceAddress: 
08-16 17:44:03.130  1017  1047 D WifiDisplayController:  SConnectInfo : null
,08-16 17:44:03.130  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:44:03.130  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:44:03.130  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:44:03.130  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:44:03.130  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:44:03.130  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:44:03.130  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:03.130  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:44:03.140  6526  6526 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:44:03.140  6526  6526 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:44:03.140  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:44:03.140  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:03.140  6541  6541 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:44:03.150  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:44:03.150  1017  1127 D WifiP2pService: InactiveState
,08-16 17:44:03.150  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:44:03.150  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:44:03.150  7097  7097 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:44:03.150  1017  1127 D WifiP2pService: InactiveState{ what=143376 },
08-16 17:44:03.150  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:03.750  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:03.750  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:03.750  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:44:03.750  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:44:03.750  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c184292 Bundle[{}]
,08-16 17:44:03.750  6282  6335 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:44:03.750  6282  6335 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 17:44:03.760  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:44:03.760  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:44:03.760  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 17:44:03.760  6282  6335 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:44:03.760  6282  6335 I System.out: Running OutgoingSocketThread
,08-16 17:44:03.760  6282  7107 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1182)
,08-16 17:44:03.770  6282  7107 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40896
,08-16 17:44:03.770  6282  7107 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:44:04.260  7097  7097 I wpa_supplicant: nl80211: Received scan results (33 BSSes),
08-16 17:44:04.260  7097  7097 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:44:04.260  7097  7097 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-16 17:44:04.260  7097  7097 I wpa_supplicant: Trying to associate with  'G700'
,08-16 17:44:04.260  7097  7097 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-16 17:44:04.260  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-16 17:44:04.260  1017  7103 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-16 17:44:04.290  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:44:04.290  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:04.380  7097  7097 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:44:04.380  7097  7097 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:44:04.380  7097  7097 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-16 17:44:04.380  7097  7097 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 17:44:04.380  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:44:04.380  7097  7097 I wpa_supplicant: Associated with F4.99.3E
,08-16 17:44:04.380  7097  7097 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-16 17:44:04.380  7097  7097 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 17:44:04.380  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
,08-16 17:44:04.380  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:44:04.380  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:44:04.380  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:44:04.390  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:44:04.390  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:44:04.390  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:44:04.390  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:44:04.390  1017  1044 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:44:04.390  7097  7097 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:44:04.390  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:44:04.390  7097  7097 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-16 17:44:04.390  7097  7097 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-16 17:44:04.400  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:44:04.390  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-16 17:44:04.390  7097  7097 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:44:04.390  7097  7097 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:44:04.390  7097  7097 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:44:04.390  7097  7097 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 17:44:04.390  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:44:04.390  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-16 17:44:04.390  7097  7097 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 17:44:04.400  1017  1044 D Tethering: interfaceLinkStateChanged wlan0, true
08-16 17:44:04.400  1017  1044 D Tethering: interfaceStatusChanged wlan0, true
08-16 17:44:04.400  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:44:04.400  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:04.400  1017  1131 E Tethering: No numeric data
,08-16 17:44:04.400  1017  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:44:04.400  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:44:04.400  1017  1131 D Tethering: clearTetheredNotification()
,08-16 17:44:04.400  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:04.400  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:44:04.410  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:04.410  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:44:04.410  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:44:04.410  1175  1175 D HotspotTile: updateTetherState():false, false
,08-16 17:44:04.410  1017  1125 V NetworkStats: performPollLocked() took 7ms
08-16 17:44:04.410  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:04.410  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:04.410  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:04.410  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:44:04.420  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:44:04.420  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:44:04.420  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:44:04.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:04.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:04.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:04.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:04.430  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-16 17:44:04.430  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-16 17:44:04.430  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:44:04.430  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-16 17:44:04.430  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:44:04.440  1017  1562 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:44:04.440  1017  1562 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
,08-16 17:44:04.440  1017  1562 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:44:04.440  1017  1562 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:04.440  1017  1562 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-16 17:44:04.450  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-16 17:44:04.450  3709  3709 I Hs20UtilService: Starting #21
,08-16 17:44:04.450  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:44:04.460  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:44:04.460  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:44:04.460  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:44:04.460  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-16 17:44:04.460  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:44:04.460   276   972 D CommandListener: Setting iface cfg
08-16 17:44:04.460  1297  1297 I NearbySettings: MountReceiver.onReceive - Set preference state off,
08-16 17:44:04.460  1297  3081 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:44:04.470  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:44:04.470  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-16 17:44:04.470  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:04.480  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:44:04.480  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:04.490  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:44:04.490  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:44:04.490  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:04.490  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:04.490  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:04.490  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:04.490  1017  1128 E WifiNative-wlan0: do suspend false
,08-16 17:44:04.500  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:44:04.500  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:44:04.500  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:44:04.500  1017  1128 D SecContentProvider2: mCursor = null
,08-16 17:44:04.710  7110  7110 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:44:04.710  7110  7110 I dhcpcd  : version 5.5.6 starting
,08-16 17:44:04.720  7110  7110 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:44:04.760  6282  6335 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1183),
08-16 17:44:04.760  6282  6335 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1183)
,08-16 17:44:04.770  6282  6335 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1188)
,08-16 17:44:04.770  6282  6335 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 17:44:04.770  6282  6335 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1189)
,08-16 17:44:04.770  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 17:44:04.770  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2a7743 added. We now have 2 listener(s)
08-16 17:44:04.770  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:44:04.770  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:04.770  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:04.770  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:04.770  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123d61c0 added. We now have 9 listener(s)
08-16 17:44:04.770  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:04.780  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:04.780  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:04.790  7110  7110 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-16 17:44:04.790  7110  7110 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-16 17:44:04.790  7110  7110 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 17:44:04.790  7110  7110 I dhcpcd  : bssid match
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:04.790  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:44:04.790  7110  7110 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-16 17:44:04.790  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-16 17:44:04.790  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1756ae3e added. We now have 3 listener(s)
08-16 17:44:04.790  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.790  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af3449f added. We now have 10 listener(s)
08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:04.790  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:04.790  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:04.790  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:04.790  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:04.790  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 17:44:04.790  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b2a7743 removed from the list
,08-16 17:44:04.790  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:04.790  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123d61c0 removed from the list
08-16 17:44:04.790  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:04.790  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.790  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:04.800  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@123d61c0 not in the list
08-16 17:44:04.800  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af3449f removed from the list
,08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:04.800  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1756ae3e removed from the list
08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a76d9ec added. We now have 2 listener(s)
08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:04.800  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2388e1b5 added. We now have 9 listener(s),
08-16 17:44:04.800  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:04.800  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-16 17:44:04.810  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:44:04.810  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:44:04.810  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:04.810  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:04.810  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d518bbb added. We now have 3 listener(s)
,08-16 17:44:04.810  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.810  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:04.810  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:44:04.810  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:04.810  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:04.810  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:04.810  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eda8d8 added. We now have 10 listener(s)
08-16 17:44:04.810  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:04.810  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:04.810  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:44:04.810  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:44:04.810  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:04.810  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:04.820  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:44:04.820  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:44:04.820  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:04.830  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:44:04.830  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:04.830  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:44:04.830  6990  7000 D BtGatt.GattService: registerClient() - UUID=c0f31eca-42c4-408a-a3d3-843090c09cb4
,08-16 17:44:04.870  6990  7031 D BtGatt.GattService: onClientRegistered() - UUID=c0f31eca-42c4-408a-a3d3-843090c09cb4, clientIf=6
,08-16 17:44:04.880  6282  6296 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:44:04.880  6990  7071 D BtGatt.GattService: start scan with filters
,08-16 17:44:04.880  7110  7110 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-16 17:44:04.880  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:44:04.880  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:04.880  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:04.880  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:44:04.880  6990  7035 D BtGatt.ScanManager: handling starting scan
,08-16 17:44:04.880  6990  7035 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b64a330
,08-16 17:44:04.890  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:44:04.890  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:44:04.890  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:04.890  6990  7031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:44:04.890  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:04.890  6990  7035 D BtGatt.ScanManager: allow scan with filters
,08-16 17:44:04.890  6990  7035 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:44:04.890  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:04.890  6990  7035 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:44:04.890  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:44:04.900  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:04.900  6990  7035 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:04.900  6990  7035 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:44:04.900  6990  7031 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:44:04.900  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:04.900  6282  6335 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:44:04.900  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:44:04.900  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:04.910  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:04.910  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:44:04.910  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.910  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:44:04.910  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:44:04.910  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:44:04.910  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:44:04.910  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:44:04.910  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:04.910  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:44:04.910  6990  7078 D BtGatt.GattService: stopScan() - queue size =1,
,08-16 17:44:04.910  6990  7002 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:44:04.920  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:04.920  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:44:04.920  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:44:04.920  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:04.930  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:04.930  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:04.930  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:44:04.930  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:04.940  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:04.940  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:04.940  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.940  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:04.940  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a76d9ec removed from the list
08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:04.940  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2388e1b5 removed from the list
08-16 17:44:04.940  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:44:04.940  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:04.940  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.940  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:04.940  6990  7035 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 21
,08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:44:04.940  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:04.940  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2388e1b5 not in the list
,08-16 17:44:04.940  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.940  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 17:44:04.950  6990  7035 D BtGatt.ScanManager: filter size is 1
08-16 17:44:04.950  6990  7035 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 17:44:04.950  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:44:04.950  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:04.950  6990  7035 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eda8d8 removed from the list
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:04.950  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:04.950  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d518bbb removed from the list
08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23007a84 added. We now have 2 listener(s)
,08-16 17:44:04.950  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:44:04.950  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:04.950  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:04.950  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a0926d added. We now have 9 listener(s)
08-16 17:44:04.950  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:04.950  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:44:04.950  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:04.950  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:04.950  6990  7035 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:44:04.960  6990  7031 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:44:04.960  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:04.960  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:04.960  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:04.960  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:04.970  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:04.970  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:04.970  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c7b733 added. We now have 3 listener(s)
,08-16 17:44:04.970  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.970  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:04.970  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:44:04.970  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:04.970  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:44:04.970  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:04.970  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d4cbaf0 added. We now have 10 listener(s)
,08-16 17:44:04.970  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:04.970  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:04.970  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:44:04.970  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:44:04.980  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:44:04.980  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:04.980  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:04.980  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:44:04.980  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:44:04.980  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:04.990  7110  7110 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-16 17:44:04.990  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:44:04.990  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:04.990  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:44:04.990  6990  7000 D BtGatt.GattService: registerClient() - UUID=d4711acd-cf73-4419-b921-a4c0b3c44f3f
,08-16 17:44:05.040  6990  7031 D BtGatt.GattService: onClientRegistered() - UUID=d4711acd-cf73-4419-b921-a4c0b3c44f3f, clientIf=6
,08-16 17:44:05.040  6282  6290 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:44:05.040  6990  7071 D BtGatt.GattService: start scan with filters
,08-16 17:44:05.040  6990  7035 D BtGatt.ScanManager: handling starting scan
08-16 17:44:05.040  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:44:05.040  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:05.040  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:05.040  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:44:05.040  6990  7031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:44:05.040  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.040  6990  7035 D BtGatt.ScanManager: allow scan with filters
08-16 17:44:05.040  6990  7035 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:44:05.040  6990  7035 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:44:05.050  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:44:05.050  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:44:05.050  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.050  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:44:05.050  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:05.050  6990  7035 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:05.050  6990  7035 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:44:05.050  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:05.050  6990  7031 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-16 17:44:05.050  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.060  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:44:05.060  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.060  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:05.060  6282  6335 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 17:44:05.060  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:44:05.060  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:05.060  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:05.060  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.060  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23007a84 removed from the list
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.060  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a0926d removed from the list
08-16 17:44:05.060  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:05.060  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:44:05.060  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.060  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a0926d not in the list
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:44:05.060  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:05.060  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:44:05.070  6990  7077 D BtGatt.GattService: stopScan() - queue size =1,
,08-16 17:44:05.070  6990  7000 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:44:05.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:44:05.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:44:05.070  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:44:05.070  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:05.070  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:44:05.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-16 17:44:05.080  6990  7035 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 22,
08-16 17:44:05.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,08-16 17:44:05.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:05.080  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:44:05.080  6990  7035 D BtGatt.ScanManager: filter size is 1
,08-16 17:44:05.080  6990  7035 D BtGatt.ScanManager: delete FilterIndex - 4
08-16 17:44:05.080  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:05.080  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:44:05.080  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.080  6990  7035 D BtGatt.ScanManager: stopping BLe Batch,
,08-16 17:44:05.080  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:44:05.090  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.090  6990  7035 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d4cbaf0 removed from the list
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:05.090  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12c7b733 removed from the list
,08-16 17:44:05.090  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:05.090  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:05.090  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ada961c added. We now have 2 listener(s)
08-16 17:44:05.090  6990  7031 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:44:05.090  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:44:05.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:05.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:44:05.090  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e76a225 added. We now have 9 listener(s)
08-16 17:44:05.090  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:05.090  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:05.100  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:05.100  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:05.110  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-16 17:44:05.110  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:44:05.110  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-16 17:44:05.110  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578d9ab added. We now have 3 listener(s)
,08-16 17:44:05.110  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:44:05.120  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:05.120  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
08-16 17:44:05.120  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:44:05.120  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:05.120  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-16 17:44:05.120  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c08f808 added. We now have 10 listener(s)
08-16 17:44:05.120  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:44:05.120  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:05.120  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:44:05.120  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:44:05.120  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:44:05.120  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:44:05.120  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-16 17:44:05.130  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:44:05.130  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:44:05.140  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-16 17:44:05.140  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:44:05.140  6282  6335 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:44:05.150  6990  7071 D BtGatt.GattService: registerClient() - UUID=69d16b4c-5dce-4e04-af83-91fff43175f0
,08-16 17:44:05.190  6990  7031 D BtGatt.GattService: onClientRegistered() - UUID=69d16b4c-5dce-4e04-af83-91fff43175f0, clientIf=6
,08-16 17:44:05.190  6282  6296 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:44:05.190  6990  7078 D BtGatt.GattService: start scan with filters
,08-16 17:44:05.190  6990  7035 D BtGatt.ScanManager: handling starting scan
,08-16 17:44:05.190  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:44:05.190  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:44:05.190  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:44:05.190  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:44:05.200  6990  7031 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:44:05.200  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.200  6990  7035 D BtGatt.ScanManager: allow scan with filters
08-16 17:44:05.200  6990  7035 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:44:05.200  6990  7035 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-16 17:44:05.200  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:44:05.200  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.200  6990  7035 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:44:05.200  6990  7035 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:44:05.200  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:05.200  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:44:05.200  6990  7031 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:44:05.200  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.200  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:44:05.210  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:44:05.210  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:44:05.210  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.220  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:05.220  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:44:05.220  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:44:05.220  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:44:05.220  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.220  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:44:05.220  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.220  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ada961c removed from the list
08-16 17:44:05.220  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:05.230  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e76a225 removed from the list
08-16 17:44:05.230  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:05.230  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:05.230  6990  7035 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 23
,08-16 17:44:05.230  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:05.230  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:44:05.230  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:05.230  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:05.230  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e76a225 not in the list
08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:44:05.230  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:44:05.230  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:44:05.230  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:44:05.230  6990  7002 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:44:05.230  6990  7035 D BtGatt.ScanManager: filter size is 1
08-16 17:44:05.230  6990  7035 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:44:05.240  6990  7031 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:44:05.240  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.240  6990  7077 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:44:05.240  6990  7035 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:44:05.240  6990  7031 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:44:05.240  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:44:05.240  6990  7035 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:05.240  6990  7031 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-16 17:44:05.240  6990  7031 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.240  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:44:05.240  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c08f808 removed from the list
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:05.240  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.240  6282  6282 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:44:05.240  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:05.240  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.240  6282  6282 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:44:05.240  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1578d9ab removed from the list
08-16 17:44:05.240  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:44:05.240  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6398cb4 added. We now have 2 listener(s)
,08-16 17:44:05.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:44:05.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:05.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:05.250  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:05.250  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3697f0dd added. We now have 9 listener(s)
08-16 17:44:05.250  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:05.250  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:44:05.260  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:44:05.260  6282  6335 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:44:05.260  6282  6335 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:44:05.260  6282  6335 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:44:05.260  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:05.260  6282  6282 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:44:05.260  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:44:05.260  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ecd323 added. We now have 3 listener(s)
,08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:44:05.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:44:05.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@313cc020 added. We now have 10 listener(s)
08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:44:05.270  6282  6335 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:44:05.270  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:44:05.270  6282  6335 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:05.270  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6398cb4 removed from the list
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:44:05.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3697f0dd removed from the list
08-16 17:44:05.270  6282  6335 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:05.270  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.270  6282  6335 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3697f0dd not in the list
08-16 17:44:05.270  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:44:05.270  6282  6335 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@313cc020 removed from the list
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:44:05.270  6282  6335 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:44:05.270  6282  6335 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:44:05.270  6282  6335 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:44:05.280  6282  6335 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4ecd323 removed from the list
,08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only,
08-16 17:44:05.280  6282  6335 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:44:05.280  6282  7143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1196, name: My test thread name)
,08-16 17:44:05.280  6282  7143 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1196, thread name: My test thread name)
08-16 17:44:05.280  6282  7143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1196, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:05.280  6282  7144 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1198, name: My test thread name)
,08-16 17:44:05.280  6282  7144 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1198, thread name: My test thread name)
08-16 17:44:05.280  6282  7144 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1198, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:44:05.290  6282  6335 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-16 17:44:05.290  6282  6335 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-16 17:44:05.290  6282  6335 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:44:05.290  6282  6335 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:44:05.290  6282  6335 D com.test.thalitest.ThaliTestRunner: Total duration: 23224 ms
,08-16 17:44:05.290  6282  6335 I jxcore-log: Total number of executed tests:  80
08-16 17:44:05.290  6282  6335 I jxcore-log: 
,08-16 17:44:05.290  6282  6335 I jxcore-log: Number of passed tests:  80
08-16 17:44:05.290  6282  6335 I jxcore-log: 
08-16 17:44:05.290  6282  6335 I jxcore-log: Number of failed tests:  0
08-16 17:44:05.290  6282  6335 I jxcore-log: 
08-16 17:44:05.290  6282  6335 I jxcore-log: Number of ignored tests:  0
08-16 17:44:05.290  6282  6335 I jxcore-log: 
08-16 17:44:05.290  6282  6335 I jxcore-log: Total duration:  23224
08-16 17:44:05.290  6282  6335 I jxcore-log: 
,08-16 17:44:05.290  6282  6335 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:44:05.290  6282  6335 I jxcore-log: 
,08-16 17:44:05.290  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.290  6282  6335 I jxcore-log: 
08-16 17:44:05.290  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.290  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6282 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.300  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:44:05.300  6282  6335 I jxcore-log: 
08-16 17:44:05.310  1017  1128 E WifiNative-wlan0: do suspend true
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
,08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.310  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.310  6282  6335 I jxcore-log: 
08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
,08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:44:05.320  6282  6335 I jxcore-log: 
08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
,08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
,08-16 17:44:05.320  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:44:05.320  6282  6335 I jxcore-log: 
,08-16 17:44:05.330  1017  1127 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:44:05.330  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:44:05.330  1017  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 17:44:05.330  1017  1128 E WifiStateMachine: VerifyingLinkState enter
,08-16 17:44:05.340  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:05.340  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:44:05.340  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.340  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.340  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.340  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.340  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210],
08-16 17:44:05.340  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:44:05.340  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-16 17:44:05.340  1017  1130 D ConnectivityService: Adding iface wlan0 to network 504
,08-16 17:44:05.350  1017  1144 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-16 17:44:05.350  1017  1144 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-16 17:44:05.350  1017  1144 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:44:05.350  1017  1144 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:44:05.350  1017  1144 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:44:05.350  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:44:05.350  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:44:05.350  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.350  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.350  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.350  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.360  1017  1804 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:44:05.360  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:44:05.360  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:05.360  1017  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:05.360  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:44:05.360  3709  3709 I Hs20UtilService: Starting #22
,08-16 17:44:05.360  3709  3725 I Hs20UtilService: Message received 5007
08-16 17:44:05.360  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:44:05.370  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 17:44:05.370  1017  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-16 17:44:05.370  1017  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-16 17:44:05.370  1017  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-16 17:44:05.370  1017  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
08-16 17:44:05.370  1017  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:44:05.370  1017  1130 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-16 17:44:05.370  1017  1130 D ConnectivityService: LTETest block dns file not exists
,08-16 17:44:05.380  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-16 17:44:05.390  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:44:05.390  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-16 17:44:05.390  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:44:05.390  1017  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-16 17:44:05.390  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:44:05.390  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:44:05.390  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 17:44:05.390  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:44:05.390  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:44:05.390  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-16 17:44:05.390  1017  7108 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:44:05.400   276   967 D EnterpriseController: uids 1000
08-16 17:44:05.400   276   967 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:44:05.400   276   967 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-16 17:44:05.400  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:44:05.400  1017  1130 D ConnectivityService:    accepting network in place of null
,08-16 17:44:05.400  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:44:05.400  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:44:05.400  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.400  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.400  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.400  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.400  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:44:05.400  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:44:05.410  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:44:05.410  1017  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-16 17:44:05.410  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:44:05.410  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 17:44:05.410  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-16 17:44:05.410  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
08-16 17:44:05.410  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-16 17:44:05.410  1017  1017 D WifiNative-wlan0: callSECApiVoid - ID [212],
,08-16 17:44:05.420  1017  1482 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:44:05.420  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:44:05.420  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:05.420  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:05.420  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:05.420  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:44:05.420  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:44:05.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.420  3709  3709 I Hs20UtilService: Starting #23
08-16 17:44:05.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.420  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.420  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:44:05.420   286   286 E SMD     : DCD OFF,
,08-16 17:44:05.420  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:44:05.430  1017  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-16 17:44:05.420  1297  1297 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:44:05.430  1017  1125 V NetworkStats: updateIfacesLocked()
08-16 17:44:05.430  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-16 17:44:05.430  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:44:05.430  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 17:44:05.430  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 17:44:05.430  1017  1131 D Tethering: MasterInitialState.processMessage what=3
08-16 17:44:05.430  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:44:05.440  1017  1125 V NetworkStats: performPollLocked() took 7ms
08-16 17:44:05.430  1297  1297 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 17:44:05.430  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 17:44:05.430  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.430  6282  6282 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:05.430  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:05.430  6282  6335 I jxcore-log: 
08-16 17:44:05.430  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:05.430  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:44:05.430  1017  1046 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:44:05.430  1175  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:44:05.440  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:44:05.430  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:44:05.440  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:05.440  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:44:05.440  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-16 17:44:05.440  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:44:05.440  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-16 17:44:05.440  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:44:05.440  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:05.440  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:05.450  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.450  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.460  1017  3103 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:44:05.460  1017  3103 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:44:05.460  1017  3103 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:05.460  1017  3103 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:05.460  1017  3103 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:44:05.460  1297  1297 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:44:05.460  1297  1297 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:44:05.470  3709  3709 I Hs20UtilService: Starting #24
08-16 17:44:05.470  3709  3725 I Hs20UtilService: Message received 5007
,08-16 17:44:05.470  1017  1219 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0,
08-16 17:44:05.470  1017  3104 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 17:44:05.470  1017  3104 D SecContentProvider2: mCursor = null
08-16 17:44:05.470  1017  1804 D SecContentProvider2: uri = 15 selection = getToastGravity,
08-16 17:44:05.470  1017  1804 D SecContentProvider2: mCursor = null
,08-16 17:44:05.470  1017  4314 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-16 17:44:05.470  1017  4314 D SecContentProvider2: mCursor = null
08-16 17:44:05.480  1017  1514 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-16 17:44:05.480  1017  1514 D SecContentProvider2: mCursor = null
,08-16 17:44:05.480  1017  3103 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-16 17:44:05.480  1017  3103 D SecContentProvider2: mCursor = null
,08-16 17:44:05.480  1017  1292 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-16 17:44:05.480  1017  1292 D SecContentProvider2: mCursor = null
,08-16 17:44:05.500  1017  2730 D SSRM:n  : SIOP:: AP = 320
,08-16 17:44:05.500   256   256 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-16 17:44:05.510  1017  7108 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-16 17:44:05.520  1017  1219 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-16 17:44:05.530  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:44:05.590  7147  7147 D AndroidRuntime: 
08-16 17:44:05.590  7147  7147 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 17:44:05.590  6282  6282 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:44:05.590  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:05.590  6282  6335 I jxcore-log: 
,08-16 17:44:05.590  7147  7147 D AndroidRuntime: CheckJNI is OFF
,08-16 17:44:05.590  7147  7147 D AndroidRuntime: readGMSProperty: start
08-16 17:44:05.590  7147  7147 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:44:05.590  7147  7147 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:44:05.590  7147  7147 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:44:05.590  7147  7147 D AndroidRuntime: readGMSProperty: end
08-16 17:44:05.590  7147  7147 D AndroidRuntime: addProductProperty: start
,08-16 17:44:05.600  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:44:05 GMT], X-Android-Received-Millis=[1471362245614], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471362245558]}
08-16 17:44:05.600  1017  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504],
08-16 17:44:05.600  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:44:05.600  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-16 17:44:05.600  1017  7108 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:44:05.600  1017  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-16 17:44:05.600  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:44:05.600  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-16 17:44:05.600  1175  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:44:05.600  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:44:05.610  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal,
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:44:05.610  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:44:05.610  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:44:05.720  7147  7147 E AffinityControl: AffinityControl: registerfunction enter,
,08-16 17:44:05.740  6282  6282 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:44:05.750  6282  6335 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:44:05.750  6282  6335 I jxcore-log: 
,08-16 17:44:05.750  7147  7147 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:44:05.760  1017  1481 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-16 17:44:05.760  1017  1481 D PackageManager: START PACKAGE DELETE: observer{522119514}
08-16 17:44:05.760  1017  1481 D PackageManager: pkg{<packageName>}
08-16 17:44:05.760  1017  1481 D PackageManager: user{0}
08-16 17:44:05.760  1017  1481 D PackageManager: caller{2000}
08-16 17:44:05.760  1017  1481 D PackageManager: flags{2}
08-16 17:44:05.760  1017  1481 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 17:44:05.760  1017  1481 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-16 17:44:05.760  1017  1481 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 17:44:05.760  1017  1481 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 17:44:05.770  1017  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 17:44:05.770  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-16 17:44:05.770  1017  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 17:44:05.770  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 17:44:05.770  1017  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 17:44:05.770  1017  1057 D PackageManager: !@killApplicatoin: 10155, uninstall pkg,
,08-16 17:44:05.770  1017  1042 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-16 17:44:05.770  1017  1042 I ActivityManager: Killing 6282:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 17:44:05.780  1017  1042 I ActivityManager:   Force finishing activity ActivityRecord{6fc512c u0 com.test.thalitest/.MainActivity t128}
,08-16 17:44:05.780  1017  1042 W ActivityManager: mDVFSHelper.acquire()
,08-16 17:44:05.870   256  1097 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
08-16 17:44:05.870  1017  4314 I WindowState: WIN DEATH: Window{198fd58c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 17:44:05.870   256  1097 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-16 17:44:05.870  1017  4314 D InputDispatcher: Focus left window: 6282
,08-16 17:44:05.880  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:44:05.880  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:44:05.890  1017  1057 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-16 17:44:05.890  1017  1057 I ActivityManager:   Force finishing activity ActivityRecord{6fc512c u0 com.test.thalitest/.MainActivity t128 f}
,08-16 17:44:05.890  1017  1057 W ActivityManager: Duplicate finish request for ActivityRecord{6fc512c u0 com.test.thalitest/.MainActivity t128 f}
,08-16 17:44:05.910  1017  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 17:44:05.920  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-16 17:44:05.930  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:05.930  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 17:44:05.940  5706  5706 I art     : Explicit concurrent mark sweep GC freed 2070(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 27.878ms
,08-16 17:44:05.950  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 17:44:05.960  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 17:44:05.960  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-16 17:44:05.970  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-16 17:44:05.970  3189  3189 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-16 17:44:05.970  6118  6118 I art     : Explicit concurrent mark sweep GC freed 583(34KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 764us total 50.760ms
,08-16 17:44:05.980  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
08-16 17:44:05.980  1017  1042 D InputDispatcher: Focused application released
,08-16 17:44:05.980  3189  3189 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 com.wssyncmldm.ui.XUIInstallConfirmActivity.onResume:446 
,08-16 17:44:06.000  3772  3772 I art     : Explicit concurrent mark sweep GC freed 23813(1447KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 16MB/26MB, paused 1.333ms total 102.355ms
,08-16 17:44:06.030  1786  1786 E SamsungIME: mOCRHelper is null
08-16 17:44:06.030  1936  2119 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:44:06.030  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:44:06.050  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-16 17:44:06.050  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:06.050  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-16 17:44:06.060  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:44:06.060  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:44:06.070  1017  1125 V NetworkStats: performPollLocked() took 15ms
,08-16 17:44:06.070  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:06.090  6610  6610 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 17:44:06.100  1017  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-16 17:44:06.100  1017  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 17:44:06.100  1017  1041 W TextServicesManagerService: no available spell checker services found
,08-16 17:44:06.100  1017  1514 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,08-16 17:44:06.110  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:06.120  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:44:06.120  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:44:06.120  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-16 17:44:06.120  1441  1441 D RegisteredServicesCache: empty dynamic service
,08-16 17:44:06.130  1175  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 17:44:06.130  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-16 17:44:06.130  1175  1693 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 17:44:06.130  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 17:44:06.140  3772  6344 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 17:44:06.140  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
08-16 17:44:06.140  3727  3727 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:44:06 GMT+02:00 2016
,08-16 17:44:06.140  1017  1804 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 17:44:06.140  1017  3104 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-16 17:44:06.150  1017  3104 D SecContentProvider2: mCursor = null
,08-16 17:44:06.150  1017  1804 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:44:06.150  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.150  1017  1804 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:06.150  1017  1804 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:06.150  1017  1804 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:44:06.170  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 17:44:06.170  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 17:44:06.170  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:06.180  3727  3727 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:44:06.180  1017  1514 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-16 17:44:06.180  1017  1514 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 17:44:06.190  1017  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 17:44:06.190  1017  1057 I art     : Explicit concurrent mark sweep GC freed 71992(4MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 28MB/43MB, paused 3.409ms total 264.483ms
,08-16 17:44:06.190  3727  3727 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-16 17:44:06.190  1017  1030 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
08-16 17:44:06.190  1017  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-16 17:44:06.190  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.190  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.190  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.190  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.200  3727  3727 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:44:06.200  3727  3727 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:44:06.200  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:44:06.210  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-16 17:44:06.210  7163  7163 E Zygote  : MountEmulatedStorage(),
08-16 17:44:06.210  7163  7163 E Zygote  : v2
08-16 17:44:06.210  7163  7163 I libpersona: KNOX_SDCARD checking this for 10094,
08-16 17:44:06.210  7163  7163 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:06.210  1017  1514 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7163 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
08-16 17:44:06.210  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
08-16 17:44:06.210  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
08-16 17:44:06.210  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 17:44:06.220  7163  7163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:44:06.220  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-16 17:44:06.230  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:44:06.230  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:44:06.230  7163  7163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.230  7163  7163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.240  3189  3189 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 17:44:06.240  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
08-16 17:44:06.240  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-16 17:44:06.240  3189  3189 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-16 17:44:06.240  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.240  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.240  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.240  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.240  1017  1057 D PackageManager: delete codoeFile: 
,08-16 17:44:06.240  3189  3189 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-16 17:44:06.250  7175  7175 E Zygote  : MountEmulatedStorage(),
08-16 17:44:06.250  7175  7175 E Zygote  : v2
08-16 17:44:06.250  7175  7175 I libpersona: KNOX_SDCARD checking this for 10044
,08-16 17:44:06.260  7175  7175 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:06.260  1017  1042 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7175 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 17:44:06.260  7175  7175 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:44:06.260  7175  7175 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:44:06.260  1017  1057 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-16 17:44:06.260  7175  7175 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:44:06.270  1017  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-16 17:44:06.260  1017  1057 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-16 17:44:06.270  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.270  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.270  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.270  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.270  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.270  1017  1057 D PackageManager: result of delete: 1{522119514}
,08-16 17:44:06.280  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.290  7163  7163 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:06.290  7163  7163 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.290  7192  7192 E Zygote  : MountEmulatedStorage()
,08-16 17:44:06.290  7192  7192 E Zygote  : v2
08-16 17:44:06.290  1017  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-16 17:44:06.290  1017  1042 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7192 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:44:06.290  1017  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:44:06.290  1017  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-16 17:44:06.290  7192  7192 I libpersona: KNOX_SDCARD checking this for 10149
08-16 17:44:06.290  7192  7192 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:06.290  3189  3189 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-16 17:44:06.300  7192  7192 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-16 17:44:06.300  7175  7175 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:06.300  7192  7192 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.300  7192  7192 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.300  7175  7175 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.310   256   256 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-16 17:44:06.310  7147  7147 D AndroidRuntime: Shutting down VM
,08-16 17:44:06.320  1017  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 17:44:06.320  1017  1562 D InputDispatcher: Focus entered window: 3189
,08-16 17:44:06.320  1017  1017 D RCPManagerService: PackageReceiver onReceive()
,08-16 17:44:06.320  1017  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:44:06.320  1017  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:44:06.320  3189  3189 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:44:06.320  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 17:44:06.330  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 17:44:06.330  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-16 17:44:06.330  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-16 17:44:06.330  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-16 17:44:06.340  3189  3189 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-16 17:44:06.340  3189  3189 V ActivityThread: updateVisibility : ActivityRecord{33f01446 token=android.os.BinderProxy@36900f95 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
08-16 17:44:06.340  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
08-16 17:44:06.340  1017  1562 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-16 17:44:06.340  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
08-16 17:44:06.340  1017  1562 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6282 uid 10155
,08-16 17:44:06.340  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 17:44:06.340  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 17:44:06.340  1017  7209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:44:06.340  7192  7192 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:06.340  7192  7192 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-16 17:44:06.350  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:44:06.350  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-16 17:44:06.350  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:44:06.350  1786  1786 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-16 17:44:06.360  1017  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 17:44:06.360  1017  1057 D PackageManager: userId{-1}
08-16 17:44:06.360  1017  1057 D PackageManager: andCode{true}
,08-16 17:44:06.370  3189  3189 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36900f95 time:149841
,08-16 17:44:06.370  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:44:06.370  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 17:44:06.370  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-16 17:44:06.370  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:44:06.370  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-16 17:44:06.370  1017  2730 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 17:44:06.380  7009  7009 W art     : Suspending all threads took: 6.575ms
08-16 17:44:06.380  1017  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 17:44:06.380  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-16 17:44:06.380  7009  7009 I art     : Explicit concurrent mark sweep GC freed 495(37KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 7.515ms total 64.403ms
08-16 17:44:06.380  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-16 17:44:06.380  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:06.380  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:06.380  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-16 17:44:06.380  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-16 17:44:06.380  3727  7162 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:44:06.380  7175  7175 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:44:06.390  7175  7175 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:44:06.390  7009  7183 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-16 17:44:06.390  7163  7163 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 17:44:06.390  7163  7163 D elm:15183: ELMEngine.ELMEngine( context ).
,08-16 17:44:06.400  7163  7163 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-16 17:44:06.400  1017  4314 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-16 17:44:06.400  1017  4314 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 17:44:06.420  1017  4314 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:06.420  1017  4314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:06.420  1017  4314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 17:44:06.420  3727  7162 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 17:44:06.430  7163  7163 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-16 17:44:06.430  1017  1047 W ActivityManager: mDVFSHelper.release()
,08-16 17:44:06.430  1017  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{20ae4d3a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149902
,08-16 17:44:06.430  1017  1130 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 17:44:06.440  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-16 17:44:06.440  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:44:06.440  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:44:06.440  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-16 17:44:06.440  3727  3727 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 17:44:06.450  1017  1161 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml,
,08-16 17:44:06.450  7163  7163 D elm:15183: ElmAgentService : onCreate()
,08-16 17:44:06.450  7163  7213 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-16 17:44:06.450  7163  7213 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-16 17:44:06.450  7163  7213 D elm:15183: MDMBridge.getInstance()
08-16 17:44:06.450  7163  7213 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:44:06.450  6034  6046 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-16 17:44:06.450  6034  6046 D BadgeProvider: sendNotify, [notify] : null
08-16 17:44:06.450  6034  6046 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-16 17:44:06.450  6034  6046 D BadgeProvider: update, [BadgeCount] : badgecount=0
,08-16 17:44:06.450  6034  6046 D BadgeProvider: update, [UpdateCount] : 1
,08-16 17:44:06.460  3450  3450 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-16 17:44:06.460  7163  7213 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:44:06.460  3450  3450 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 17:44:06.460  3450  3450 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,08-16 17:44:06.460  3450  3450 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.460  3450  3450 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:44:06.460  3450  3450 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:06.460  3450  3450 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:44:06.460  3450  3450 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:44:06.460  3450  3450 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:44:06.470  1017  1804 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-16 17:44:06.470  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.470  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.470  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.470  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.480  7192  7192 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 17:44:06.480  7192  7192 D ThemeInfoUtil: isCurrentFestival = false
,08-16 17:44:06.490  7217  7217 E Zygote  : MountEmulatedStorage(),
08-16 17:44:06.490  7217  7217 E Zygote  : v2
08-16 17:44:06.490  7217  7217 I libpersona: KNOX_SDCARD checking this for 1000,
08-16 17:44:06.490  1017  1804 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 17:44:06.490  7217  7217 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:06.490  7217  7217 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-16 17:44:06.490  1175  1175 D PanelView: There is/are notification(s) 
08-16 17:44:06.490  1017  1804 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-16 17:44:06.500  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:44:06.500  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.500  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.500  1017  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-16 17:44:06.500  1017  1804 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-16 17:44:06.500  7217  7217 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.500  7217  7217 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:44:06.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.500  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.500  1017  1292 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-16 17:44:06.500  1017  1292 D SecContentProvider2: mCursor = null
,08-16 17:44:06.510  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:06.510  1175  1175 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
08-16 17:44:06.510  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:06.510  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:44:06.510  1175  1175 D PanelView: There is/are notification(s) 
08-16 17:44:06.510  1175  1175 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 17:44:06.510  1175  1175 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:44:06.510  1017  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:06.510  1017  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:06.510  1017  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:44:06.510  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.520  1175  1175 D PanelView: There is/are notification(s) ,
08-16 17:44:06.520  1175  1175 D PanelView: kidsfalse mQsExpansionEnabled:true
08-16 17:44:06.520  7217  7217 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:06.530  7217  7217 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.530  7147  7147 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:44:06.540  7232  7232 E Zygote  : MountEmulatedStorage(),
08-16 17:44:06.540  7232  7232 I libpersona: KNOX_SDCARD checking this for 10152
08-16 17:44:06.540  7232  7232 E Zygote  : v2
08-16 17:44:06.540  7232  7232 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:06.540  7232  7232 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:44:06.540  1017  1804 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7232 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
08-16 17:44:06.540  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:06.540  7232  7232 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.540  7232  7232 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.550  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.560  7163  7163 D elm:15183: ElmAgentService : onDestroy().
,08-16 17:44:06.570  6592  6592 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-16 17:44:06.570  6592  6592 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 17:44:06.570  6592  6592 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-16 17:44:06.570  6592  6592 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-16 17:44:06.570  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:06.570  1017  1509 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-16 17:44:06.570  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:06.570  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.570  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.570  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.570  1017  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.570  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.580  7232  7232 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:06.580  7232  7232 D ActivityThread: Added TimaKeyStore provider
08-16 17:44:06.580  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:06.580  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:06.580  1175  1175 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-16 17:44:06.580  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:44:06.580  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:44:06.580  1017  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:44:06.590  7250  7250 E Zygote  : MountEmulatedStorage()
,08-16 17:44:06.590  7250  7250 E Zygote  : v2
08-16 17:44:06.590  7250  7250 I libpersona: KNOX_SDCARD checking this for 10032
08-16 17:44:06.590  7250  7250 I libpersona: KNOX_SDCARD not a persona,
,08-16 17:44:06.590  7250  7250 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:44:06.600  7250  7250 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.600  1017  1509 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7250 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
08-16 17:44:06.600  7250  7250 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.600  1017  1509 I ActivityManager: Killing 6211:com.samsung.helphub/1000 (adj 15): empty #31
,08-16 17:44:06.620  7250  7250 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:06.630  7250  7250 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.630  1017  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-16 17:44:06.630  1017  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-16 17:44:06.630  1017  1041 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:44:06.660  7232  7232 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-16 17:44:06.670  1017  1562 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:44:06.670  7175  7175 D NearbySource: Nearby Source Create!
,08-16 17:44:06.670  7175  7175 D NearbyContext: Nearby Context Create!
,08-16 17:44:06.680  1017  1292 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-16 17:44:06.680  1017  1292 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-16 17:44:06.680  7217  7217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-16 17:44:06.690  1017  1292 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:44:06.690  1017  1292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:44:06.690  1017  1292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-16 17:44:06.690  1017  1482 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-16 17:44:06.690  1017  1482 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-16 17:44:06.690  1017  1482 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:44:06.690  1017  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:44:06.690  1017  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-16 17:44:06.700  1017  3103 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-16 17:44:06.700  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.700  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.700  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.700  1017  3103 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.700  7250  7265 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-16 17:44:06.710  7268  7268 E Zygote  : MountEmulatedStorage()
08-16 17:44:06.710  7268  7268 I libpersona: KNOX_SDCARD checking this for 10156
08-16 17:44:06.710  7268  7268 E Zygote  : v2
08-16 17:44:06.710  7268  7268 I libpersona: KNOX_SDCARD not a persona
,08-16 17:44:06.710  7268  7268 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:44:06.720   255   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-16 17:44:06.720   255   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:44:06.720  7268  7268 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:44:06.720  7175  7175 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-16 17:44:06.720  7268  7268 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.720  7175  7175 D SLinkSource: Samsung link source created
,08-16 17:44:06.720  1017  3103 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7268 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 17:44:06.730  7250  7265 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-16 17:44:06.740  7009  7214 E SQLiteLog: (10) unixWrite() File Descriptor : 36 gets errno : 9
08-16 17:44:06.740  7217  7270 W FileUtils: Failed to chmod(/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: Error inserting name=isDevelopVersion value=false
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:207)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.740  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.750  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.750  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: Error inserting name=DBVersion value=2003
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:208)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.750  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.750  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:209)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.750  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.750  7268  7268 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:44:06.750  1017  1217 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-16 17:44:06.750  7268  7268 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.750  5962  5962 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
08-16 17:44:06.760  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:44:06.760  5962  5962 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:44:06.760  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.760  5962  5962 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:06.760  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.760  1017  1217 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:44:06.760  7217  7270 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.760  7217  7270 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM AMData WHERE appname=?] disk I/O error
08-16 17:44:06.760  7217  7270 W System.err: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1637)
08-16 17:44:06.760  7217  7270 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:161)
08-16 17:44:06.760  7217  7270 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.760  7217  7270 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.760  7250  7265 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:44:06.770  7250  7265 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
08-16 17:44:06.770  7250  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:06.770  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.780  7285  7285 E Zygote  : MountEmulatedStorage()
08-16 17:44:06.780  7285  7285 E Zygote  : v2
08-16 17:44:06.780  7285  7285 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:44:06.780  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.780  7285  7285 I libpersona: KNOX_SDCARD not a persona
08-16 17:44:06.780  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-16 17:44:06.780  7009  7214 E SQLiteDatabase: Error inserting name=UT enabled value=false
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:210)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	,at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.780  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.780  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100),
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41),
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.780  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
08-16 17:44:06.780  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error,
08-16 17:44:06.780  7285  7285 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:44:06.780  7250  7265 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952),
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	,at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: ,	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.780  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.780  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.780  7250  7265 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-16 17:44:06.780  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-16 17:44:06.780  7009  7214 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
,08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: ,	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.780  7285  7285 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:44:06.790  1017  1217 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7285 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 17:44:06.780  7009  7214 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-16 17:44:06.780  7009  7214 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: Error inserting name=status value=successfully initialized
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:,100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.780  7009  7214 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:44:06.790  1017  1217 I ActivityManager: Killing 6118:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
08-16 17:44:06.790  7285  7285 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:44:06.800  1017  1514 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 17:44:06.800  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.810  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.810  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.810  1017  1514 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:44:06.810  7285  7285 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:44:06.810  7285  7285 D ActivityThread: Added TimaKeyStore provider
,08-16 17:44:06.820  7175  7175 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/local.db" with flag (131138) and mode_t (0) due to error (30)
08-16 17:44:06.820   311   311 I art     : Explicit concurrent mark sweep GC freed 8736(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 665us total 25.505ms
,08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:44:06.820  7250  7265 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:44:06.820  7175  7175 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/local.db'.
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:44:06.820  7175  7175 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: Couldn't open local.db for writing (will try read-only):
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getReadableDatabase(LocalDatabaseManager.java:232)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.<init>(LocalDatabaseManager.java:202)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.sec.samsung.gallery.util.LocalDatabaseManager.getInstance(LocalDatabaseManager.java:212)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.initLocalDataBase(GalleryAppImpl.java:211)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.sec.android.gallery3d.app.GalleryAppImpl.onCreate(GalleryAppImpl.java:203)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:44:06.820  7175  7175 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:44:06.830  7175  7175 W SQLiteOpenHelper: Opened local.db in read-only mode
,08-16 17:44:06.830  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.830  7250  7265 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:44:06.830  7250  7265 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:44:06.830  1017  1482 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:44:06.840   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 684us total 17.280ms
,08-16 17:44:06.850  7250  7265 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-16 17:44:06.850  7250  7265 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:44:06.850  7250  7265 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:44:06.850  7250  7265 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:44:06.850  7250  7265 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.

```
