#### Test 8149356279477ac_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
08-16 17:57:52.780  1015  1330 E Watchdog: !@Sync 3
,--------- beginning of main
08-16 17:57:53.350   324   324 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-16 17:57:53.350   324   324 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-16 17:57:53.480  6165  6165 D AndroidRuntime: 
08-16 17:57:53.480  6165  6165 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:57:53.490  6165  6165 D AndroidRuntime: CheckJNI is OFF
08-16 17:57:53.490  6165  6165 D AndroidRuntime: readGMSProperty: start
08-16 17:57:53.490  6165  6165 D AndroidRuntime: readGMSProperty: already setted!!
08-16 17:57:53.490  6165  6165 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:57:53.490  6165  6165 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-16 17:57:53.490  6165  6165 D AndroidRuntime: readGMSProperty: end
08-16 17:57:53.490  6165  6165 D AndroidRuntime: addProductProperty: start
08-16 17:57:53.630  6165  6165 E AffinityControl: AffinityControl: registerfunction enter
08-16 17:57:53.660  6165  6165 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 17:57:53.670  1015  3089 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:57:53.670  1015  3089 I PersonaManagerService: PersonaId don't exist
08-16 17:57:53.670  1015  3089 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-16 17:57:53.670  1015  3089 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:57:53.680  1015  3089 W ActivityManager: mDVFSHelper.acquire()
08-16 17:57:53.690  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-16 17:57:53.690  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-16 17:57:53.690  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.690  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.690  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.690  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:57:53.710  6176  6176 E Zygote  : MountEmulatedStorage()
08-16 17:57:53.710  6176  6176 E Zygote  : v2
08-16 17:57:53.710  6176  6176 I libpersona: KNOX_SDCARD checking this for 10155
08-16 17:57:53.710  6176  6176 I libpersona: KNOX_SDCARD not a persona
08-16 17:57:53.710  1015  3089 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6176 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:57:53.710  1015  3089 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-16 17:57:53.710  1015  3089 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-16 17:57:53.710  1015  3089 D InputDispatcher: Focused application set to: xxxx
08-16 17:57:53.710  1015  3089 D InputDispatcher: Focus left window: 3126
08-16 17:57:53.710  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:57:53.710  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-16 17:57:53.710   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-16 17:57:53.710  6165  6165 D AndroidRuntime: Shutting down VM
08-16 17:57:53.710  6176  6176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:57:53.720  6176  6176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:57:53.720  6176  6176 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-16 17:57:53.730  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:57:53.730  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:57:53.740  6176  6176 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:57:53.740  6176  6176 D ActivityThread: Added TimaKeyStore provider
08-16 17:57:53.750  1015  1015 V ActivityManager: Display changed displayId=0
08-16 17:57:53.760  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-16 17:57:53.770  1015  1384 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:57:53.810   258   446 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-16 17:57:53.810   258  1160 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-16 17:57:53.820  3126  3126 V ActivityThread: updateVisibility : ActivityRecord{2c5351bb token=android.os.BinderProxy@39bf8b6e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-16 17:57:53.880  6176  6176 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-16 17:57:53.900  6176  6176 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9348-9349)
08-16 17:57:53.900  6176  6176 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:57:53.910  6176  6176 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {175eaa67}
08-16 17:57:53.920  6176  6176 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:57:53.920  6176  6176 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:57:53.920  6165  6165 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-16 17:57:53.950  6176  6176 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:57:53.950  6176  6176 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:57:53.950  6176  6176 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:57:53.970  6176  6176 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 17:57:53.970  6176  6176 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-16 17:57:53.970  6176  6176 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-16 17:57:53.980  6176  6176 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:57:53.980  6176  6176 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:57:53.980  6176  6176 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:57:53.980  6176  6176 I Adreno-EGL: Local Branch: 
08-16 17:57:53.980  6176  6176 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:57:53.980  6176  6176 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:57:53.980  6176  6176 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:57:54.100  6176  6203 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-16 17:57:54.150  6176  6176 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:57:54.160  6176  6176 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 17:57:54.170  6176  6176 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-16 17:57:54.170  6176  6176 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-16 17:57:54.180  6176  6176 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-16 17:57:54.180  6176  6176 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:57:54.180  6176  6176 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:57:54.220  6176  6216 D OpenGLRenderer: Render dirty regions requested: true
,08-16 17:57:54.230  1015  1250 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 17:57:54.230  1015  1250 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:57:54.230  1015  1250 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 17:57:54.230  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:57:54.230  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:57:54.240  6176  6176 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-16 17:57:54.240  6176  6176 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-16 17:57:54.250   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,08-16 17:57:54.260  1015  3089 D InputDispatcher: Focus entered window: 6176
,08-16 17:57:54.260  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:57:54.270  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-16 17:57:54.270  6176  6176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-16 17:57:54.270  6176  6216 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:57:54.270  6176  6216 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-16 17:57:54.270  6176  6216 D OpenGLRenderer: Enabling debug mode 0
,08-16 17:57:54.300  6176  6176 V ActivityThread: updateVisibility : ActivityRecord{25c280ae token=android.os.BinderProxy@145df2b0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-16 17:57:54.330   288   288 E SMD     : DCD OFF
,08-16 17:57:54.330  1015  1250 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:57:54.340  1174  1174 D PanelView: There is/are notification(s) 
,08-16 17:57:54.340  1015  6219 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:57:54.350  1015  1045 I ActivityManager: Displayed Component not be shown by security: +576ms (total +658ms)
,08-16 17:57:54.350  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{f90b7cb u0 com.test.thalitest/.MainActivity t128} time:109806
08-16 17:57:54.350  1015  1045 W ActivityManager: mDVFSHelper.release()
,08-16 17:57:54.350  1779  1779 I SamsungIME: getCurrentCandidateView
,08-16 17:57:54.360  6176  6176 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-16 17:57:54.360  6176  6176 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@145df2b0 time:109810
,08-16 17:57:54.360   258  1160 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-16 17:57:54.360   258  1100 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,08-16 17:57:54.440  6176  6176 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6176
,08-16 17:57:54.440  1779  1779 D SamsungIME: Dismiss ExpandCandiate
,08-16 17:57:54.550  6176  6176 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:57:54.580  1779  1779 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:57:54.610  1779  1779 I SamsungIME: getDebugLevel  : 0x4f4c
,08-16 17:57:54.630  1779  1779 I SamsungIME: KeybaordView init() : load resources
,08-16 17:57:54.650  1779  1779 I SamsungIME: getCurrentKeyboard
08-16 17:57:54.650  1779  1779 I SamsungIME: getTextKeyboard
,08-16 17:57:54.660  6176  6221 D jxcore_app_log: JniHelper::setJavaVM(0xb8a9f328), pthread_self() = -1191148312
,08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 17:57:54.670  6176  6221 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21a6715e added. We now have 1 listener(s)
08-16 17:57:54.670  1779  1779 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 17:57:54.670  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-16 17:57:54.680  6176  6221 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:57:54.680  6176  6221 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:57:54.680  6176  6221 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 17:57:54.680  6176  6221 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d95755 added. We now have 1 listener(s)
08-16 17:57:54.680  6176  6221 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:57:54.690  6176  6221 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:57:54.700  6176  6221 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-16 17:57:54.700  6176  6221 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:57:54.700  6176  6221 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:57:54.700  6176  6221 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 17:57:54.700  6176  6221 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:57:54.710  6176  6221 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:57:54.710  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:57:54.710  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:57:54.750  6176  6176 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:57:55.200  1779  6225 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-16 17:57:55.240  6176  6229 W jxcore-log: Initializing JXcore engine
08-16 17:57:55.240  6176  6229 W jxcore-log: JXcore engine is ready
,08-16 17:57:55.290  1912  1912 E audit   : type=1400 msg=audit(1471363075.290:205): avc:  denied  { ioctl } for  pid=6229 comm="Thread-1069" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 17:57:55.290  1912  1912 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:57:55.290  1912  1912 E audit   : type=1300 msg=audit(1471363075.290:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e6008f8 items=0 ppid=312 ppcomm=main pid=6229 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1069" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-16 17:57:55.290  1912  1912 E audit   : type=1320 msg=audit(1471363075.290:205): 
,08-16 17:57:55.300  6176  6229 W jxcore-log: Starting JXcore engine
,08-16 17:57:55.410  6176  6229 W jxcore-log: Platform android
08-16 17:57:55.410  6176  6229 W jxcore-log: 
08-16 17:57:55.410  6176  6229 W jxcore-log: Process ARCH arm
08-16 17:57:55.410  6176  6229 W jxcore-log: 
,08-16 17:57:55.600  6176  6229 I jxcore-log: JXcore Cordova bridge is ready!,
08-16 17:57:55.600  6176  6229 I jxcore-log: 
08-16 17:57:55.600  6176  6229 W jxcore-log: JXcore engine is started
,08-16 17:57:55.600  6176  6221 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:57:55.600  6176  6176 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:57:57.330   288   288 E SMD     : DCD OFF,
,08-16 17:57:58.350   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:57:58.600  5401  5401 D FactoryTest: Not factory mode
,08-16 17:57:58.600  5401  5401 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-16 17:57:58.600  5401  5401 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-16 17:57:58.600  5401  5401 D MTPRx   : still no open session command from host, so toast
,08-16 17:57:58.600  5401  5401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-16 17:57:58.600  5401  5401 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-16 17:57:58.600  5401  5401 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114056,
08-16 17:57:58.600  1015  3204 E PersonaManagerService: inState():  stateMachine is null !!
08-16 17:57:58.600  1015  3204 I PersonaManagerService: PersonaId don't exist
08-16 17:57:58.600  1015  3204 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false,
,08-16 17:57:58.610  1015  3204 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-16 17:57:58.610  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:57:58.610  1015  3204 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:57:58.610  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-16 17:57:58.610  1015  3204 W ActivityManager: mDVFSHelper.acquire(),
,08-16 17:57:58.630  1015  3204 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:57:58.640  1015  3204 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:57:58.640  1015  3204 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:57:58.640  1015  3204 D InputDispatcher: Focused application set to: xxxx
08-16 17:57:58.640  1015  3204 D InputDispatcher: Focus left window: 6176
,08-16 17:57:58.640  5401  5401 E MTPRx   : started activity for popup
,08-16 17:57:58.650  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:57:58.650  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:57:58.670  5401  5401 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:57:58.690  5401  5401 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-16 17:57:58.690  1015  3089 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-16 17:57:58.690  1015  3089 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:57:58.690  1015  3089 D InputDispatcher: Focused application set to: xxxx
,08-16 17:57:58.690  1015  3089 D InputDispatcher: Focus entered window: 6176
,08-16 17:57:58.690  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-16 17:57:58.690  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:57:58.690  1015  1544 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:57:58.690  1015  1544 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3a2131aa attribute=null, token = android.os.BinderProxy@e4755fa
,08-16 17:57:58.740  5401  5401 D SettingsReceiverActivity: dev.kiessupport is : TRUE,
,08-16 17:57:58.740  5401  5401 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-16 17:57:58.740  5401  5401 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-16 17:57:58.760  6176  6176 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:57:58.760  6176  6176 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-16 17:57:58.770  6176  6176 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 17:57:58.770  6176  6176 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-16 17:57:58.770  1015  1384 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 17:57:58.770  1015  1384 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-16 17:57:58.770  1015  1384 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 17:57:58.770  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-16 17:57:58.770  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-16 17:57:58.780  6176  6176 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:57:58.780  6176  6176 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:57:58.780  6176  6176 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@145df2b0 time:114238
,08-16 17:57:58.790  6176  6176 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1650fb57 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2d79dfbd, 16908290=android.view.AbsSavedState$1@2d79dfbd}, android:focusedViewId=100}]}]
,08-16 17:57:58.790  6176  6176 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 17:57:58.790  6176  6176 V ActivityThread: updateVisibility : ActivityRecord{25c280ae token=android.os.BinderProxy@145df2b0 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-16 17:57:58.790  6176  6176 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:57:58.790  6176  6176 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:57:58.790  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:57:59.350   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:57:59.990  1015  1093 V AlarmManager: waitForAlarm result :8
,08-16 17:58:00.330   288   288 E SMD     : DCD OFF,
,08-16 17:58:00.350   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:00.580  1015  1543 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-16 17:58:00.580  1015  1543 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4182, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 17:58:00.580  1015  1543 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 17:58:00.580  1015  1543 D BatteryService: stay LED for charging
,08-16 17:58:00.580  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:58:00.580  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:58:00.590  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:00.590  1015  1015 I MotionRecognitionService: Plugged
,08-16 17:58:00.590  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
08-16 17:58:00.590  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:58:00.590  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-16 17:58:00.600  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:58:00.600  2648  2735 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:58:00.610  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:00.610  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:00.610  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:01.200  1015  2753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-16 17:58:01.350   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:01.610  1015  1040 W ActivityManager: mDVFSHelper.release()
,08-16 17:58:02.120  1015  2722 D SSRM:n  : SIOP:: AP = 330
,08-16 17:58:02.350   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:03.330   288   288 E SMD     : DCD OFF,
,08-16 17:58:03.350   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-16 17:58:03.740  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-16 17:58:04.550  1015  1093 V AlarmManager: waitForAlarm result :4
,08-16 17:58:04.550  1015  1093 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-16 17:58:04.560  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-16 17:58:04.560  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
08-16 17:58:04.560  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-16 17:58:04.560  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-16 17:58:04.560  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 17:58:04.580  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-16 17:58:04.590  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,08-16 17:58:04.590  1935  1935 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-16 17:58:04.600  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:04.620  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-16 17:58:04.620  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,08-16 17:58:04.630  1015  1384 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:04.630  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-16 17:58:04.630  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:04.630  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:04.630  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:04.670  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:04.670  3789  3789 D ConnectivityManager: CallingUid : 10012, CallingPid : 3789
,08-16 17:58:04.680  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:04.680  1015  3201 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:58:04.680  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
08-16 17:58:04.680  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-16 17:58:04.680  1015  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,08-16 17:58:04.680  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:58:04.680  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:04.700  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-16 17:58:04.750  3789  6239 W DriveInitializer: Background init thread started
,08-16 17:58:04.760   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-16 17:58:04.760   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:04.760  3789  6239 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-16 17:58:04.820  1015  1545 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:04.820  1015  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-16 17:58:04.820  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:04.820  1015  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:04.820  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:04.840  1015  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-16 17:58:04.840  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-16 17:58:04.860  3789  6239 W DriveInitializer: Background init thread ended
,08-16 17:58:04.860  1015  3089 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:04.860  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-16 17:58:04.860  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:04.860  1015  3089 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:04.860  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:04.890  3789  6247 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-16 17:58:04.890  3789  6247 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-16 17:58:04.900  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:58:04.940  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:04.940  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:04.940  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.020  1015  1353 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:05.020  1015  1353 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-16 17:58:05.020  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.020  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:05.020  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.050  1015  3204 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:05.050  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-16 17:58:05.050  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.050  1015  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.050  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.110  1015  1545 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.110  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:05.110  1015  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:05.110  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.160  1015  1250 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.170  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.170  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-16 17:58:05.170  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.210  1015  1542 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.210  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.210  1015  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.210  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.210  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:05.210  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:05.210  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:05.210  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:05.230  6252  6252 E Zygote  : MountEmulatedStorage()
08-16 17:58:05.230  6252  6252 I libpersona: KNOX_SDCARD checking this for 10012
08-16 17:58:05.230  6252  6252 E Zygote  : v2
08-16 17:58:05.230  6252  6252 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:05.230  6252  6252 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:05.230  6252  6252 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:05.240  6252  6252 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:05.250  1015  1542 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6252 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-16 17:58:05.250   312   312 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 21.370ms
,08-16 17:58:05.260  6252  6252 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 17:58:05.260  6252  6252 D ActivityThread: Added TimaKeyStore provider,
,08-16 17:58:05.270   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 628us total 18.591ms
,08-16 17:58:05.280  6252  6252 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 17:58:05.280  6252  6252 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:58:05.290   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.340ms
,08-16 17:58:05.320  6252  6252 I MultiDex: VM with version 2.1.0 has multidex support
08-16 17:58:05.320  6252  6252 I MultiDex: install
08-16 17:58:05.320  6252  6252 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 17:58:05.360  6252  6252 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 17:58:05.410  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-16 17:58:05.420  1015  3200 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.420  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.420  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:05.420  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.430  6252  6252 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:58:05.430  6252  6252 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a188910: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 17:58:05.430  6252  6252 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 17:58:05.450  1015  1384 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.450  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.450  6252  6252 D ChimeraCfgMgr: Reading stored module config
08-16 17:58:05.450  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.450  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.490  1935  1935 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=24b3528e-df3f-495f-9d1b-cdbdb397f543
,08-16 17:58:05.510  1015  1093 V AlarmManager: waitForAlarm result :4
,08-16 17:58:05.530  1015  1384 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 17:58:05.530  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:58:05.530  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.530  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:05.530  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.540  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:58:05.540  1935  1935 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-16 17:58:05.560  6252  6252 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 17:58:05.560  6252  6252 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-16 17:58:05.560  6252  6271 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-16 17:58:05.570  1015  1353 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.570  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.570  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.570  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.660   283   283 D WVCdm   : Instantiating CDM.
,08-16 17:58:05.660   283   706 I WVCdm   : CdmEngine::OpenSession
,08-16 17:58:05.660   283   706 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-16 17:58:05.690   283   706 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-16 17:58:05.710   283   706 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-16 17:58:05.710   283   706 D DrmWidevineDash: Service_Initialize: starts!
08-16 17:58:05.710   283   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 17:58:05.710  1647  2130 I art     : Explicit concurrent mark sweep GC freed 1464(50KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 989us total 26.539ms
,08-16 17:58:05.710   283   706 D QSEECOMAPI: : App is not loaded in QSEE
08-16 17:58:05.710   283   706 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-16 17:58:05.710   283   706 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 17:58:05.710   283   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 17:58:05.710   283   706 D QSEECOMAPI: : App is not loaded in QSEE
08-16 17:58:05.710   283   706 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-16 17:58:05.710   283   706 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-16 17:58:05.710   283   706 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-16 17:58:05.710   283   706 D QSEECOMAPI: : App is not loaded in QSEE
,08-16 17:58:05.740   283   706 D QSEECOMAPI: : Loaded image: APP id = 11
,08-16 17:58:05.740   283   706 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-16 17:58:05.750   283   706 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-16 17:58:05.750   283   706 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-16 17:58:05.750   283   706 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb15d5000
08-16 17:58:05.750   283   706 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb15d5000
08-16 17:58:05.750   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.750   432   445 D DrmLibTime: got the req here! ret=0
08-16 17:58:05.750   432   445 D DrmLibTime: command id, time_cmd_id = 770
08-16 17:58:05.750   432   445 D DrmLibTime: time_getutcsec starts!
08-16 17:58:05.750   432   445 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-16 17:58:05.750   432   445 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-16 17:58:05.750   432   445 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-16 17:58:05.750   432   445 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-16 17:58:05.750   432   445 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
08-16 17:58:05.750   432   445 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-16 17:58:05.750   432   445 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-16 17:58:05.750   432   445 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-16 17:58:05.750   326   426 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-16 17:58:05.760   326  6276 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
08-16 17:58:05.760   326  6276 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-16 17:58:05.760   326  6276 D QC-time-services: offset is: 0 for base: 0
08-16 17:58:05.760   432   445 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-16 17:58:05.760   432   445 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-16 17:58:05.760   432   445 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471363085
08-16 17:58:05.760   432   445 D DrmLibTime: time_getutcsec returns 0, sec = 1471363085; nsec = 0
08-16 17:58:05.760   432   445 D DrmLibTime: time_getutcsec finished! 
08-16 17:58:05.760   432   445 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-16 17:58:05.760   432   445 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-16 17:58:05.760   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.760   326   426 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-16 17:58:05.770   283   706 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-16 17:58:05.770   283   706 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 17:58:05.770   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:58:05.770  6252  6260 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-16 17:58:05.770  6252  6260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:58:05.770  6252  6260 I System.out: (HTTPLog)-Static: isShipBuild true
08-16 17:58:05.770  6252  6260 I System.out: (HTTPLog)-Thread-1044-273883773: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-16 17:58:05.770  6252  6260 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:05.770   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.770   283   706 D DrmWidevineDash: hlos api version =  9
08-16 17:58:05.770   283   706 D DrmWidevineDash: tz api version =  9
08-16 17:58:05.770   283   706 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 17:58:05.770   283   706 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-16 17:58:05.770   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.780   278   991 D EnterpriseController: uids 10012
08-16 17:58:05.780   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:05.780   278   991 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:58:05.790   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-16 17:58:05.790   283   706 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1729960
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-16 17:58:05.790   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.790   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb70a4920, dataLength=8
08-16 17:58:05.790   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
08-16 17:58:05.790   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.790   283   706 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-16 17:58:05.800  1935  2105 W GCoreFlp: No location to return for getLastLocation()
,08-16 17:58:05.800   283   706 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7072820, wrapped_rsa_key_length=1280
08-16 17:58:05.800   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.800   283   706 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.800   283   706 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-16 17:58:05.800   283   706 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-16 17:58:05.800   283   683 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-16 17:58:05.800   283   683 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-16 17:58:05.800   283   683 I WVCdm   : CdmEngine::GenerateKeyRequest
08-16 17:58:05.800   283   683 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb709d4d8, idLength=0xb1929730
08-16 17:58:05.800   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.820   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.820   283   683 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-16 17:58:05.820   283   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-16 17:58:05.820   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
,08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1929746, maximum = 0xb1929747
08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: hlos api version =  9
08-16 17:58:05.830   283   683 D DrmWidevineDash: tz api version =  9
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb19297b4
08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-16 17:58:05.830  6252  6260 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-16 17:58:05.830   283   683 D WVCdm   : PrepareKeyRequest: nonce=4277631361
,08-16 17:58:05.830  6252  6260 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6252, getuid(): 10012
08-16 17:58:05.830   283   683 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb706e148
08-16 17:58:05.830   283   683 D DrmWidevineDash: message_length=1599, signature=0xb706e790, signature_length=0xb1929714
08-16 17:58:05.830   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.920  1935  2105 I art     : Explicit concurrent mark sweep GC freed 55250(3MB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 14MB/23MB, paused 1.492ms total 73.792ms
,08-16 17:58:05.920  1015  1354 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.930  1015  1354 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.930  1015  1354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:05.930  1015  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.930  1015  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.930  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.930  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.930  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.940  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:05.940  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:05.940  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:05.940  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:05.960  3789  6248 D UdcContextInitService: registered all accounts: true
,08-16 17:58:05.980   283   683 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.980   283   683 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-16 17:58:05.980   283   283 I WVCdm   : CdmEngine::CloseSession
08-16 17:58:05.980   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-16 17:58:05.980   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.980   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-16 17:58:05.980   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,08-16 17:58:05.980   283   283 I WVCdm   : L3 Terminate.
08-16 17:58:05.980   283   283 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,08-16 17:58:05.980   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-16 17:58:05.980   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-16 17:58:05.980   283   283 D DrmWidevineDash: Service_Uninitialize: starts!
08-16 17:58:05.980   283   283 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-16 17:58:05.980   283   283 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-16 17:58:05.990   283   283 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,08-16 17:58:05.990   283   283 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-16 17:58:06.070  6252  6260 I qtaguid : Untagging socket 30
,08-16 17:58:06.110  1015  1542 I art     : Explicit concurrent mark sweep GC freed 39706(2MB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 27MB/41MB, paused 2.540ms total 147.761ms
,08-16 17:58:06.110  1935  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:58:06.120  1935  4369 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-16 17:58:06.260  1015  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:06.260  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-16 17:58:06.260  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.260  1015  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.260  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.290  1015  3200 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-16 17:58:06.290  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:58:06.290  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.290  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.290  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.330   288   288 E SMD     : DCD OFF
,08-16 17:58:06.360  1015  1542 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.360  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.360  1015  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.360  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.420  1015  3201 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.420  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.420  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.420  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.450  6284  6284 I dex2oat : ----------------------------------------------------
08-16 17:58:06.450  6284  6284 I dex2oat : <SS>: S T A R T I N G . . .
08-16 17:58:06.450  6284  6284 I dex2oat : <SS>: Zip is absent. Canceled.
,08-16 17:58:06.450  6284  6284 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 17:58:06.460  1015  3200 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.460  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.460  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.460  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.460  1935  6286 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:58:06.460  1935  6283 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 17:58:06.460  1015  1353 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.460  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:06.460  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.460  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.490  6284  6284 I dex2oat : dex2oat took 37.108ms (threads: 4)
,08-16 17:58:06.500  1015  3089 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.500  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.500  1015  3089 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.500  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.500  1935  6286 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:58:06.500  1935  6283 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 17:58:06.500  1015  3201 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.500  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:06.500  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.500  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.500  6252  6260 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:58:06.500  6252  6260 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:58:06.500  6252  6260 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:58:06.500  6252  6260 I Adreno-EGL: Local Branch: 
08-16 17:58:06.500  6252  6260 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:58:06.500  6252  6260 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:58:06.500  6252  6260 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:58:06.540  1015  1544 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:06.540  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.540  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.540  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.540  1935  6286 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-16 17:58:06.540  1935  6283 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-16 17:58:06.540  1935  6283 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-16 17:58:06.550  1935  6283 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 17:58:06.600  1015  1138 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:58:06.640  1015  3204 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-16 17:58:06.640  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 17:58:06.640  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:06.640  1015  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:06.640  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:06.650  1935  6283 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:06.650   278   991 D EnterpriseController: uids 10012
08-16 17:58:06.650   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:06.650   278   991 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:58:06.650  1935  6283 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:06.650  1935  6283 I qtaguid : Tagging socket 73 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1935, getuid(): 10012
,08-16 17:58:06.700  1935  6283 I qtaguid : Tagging socket 76 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1935, getuid(): 10012
,08-16 17:58:06.960  1015  3200 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:58:06.970  1935  6283 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:06.970  1935  6283 I qtaguid : Tagging socket 73 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1935, getuid(): 10012
,08-16 17:58:06.990  6252  6260 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:58:06.990  6252  6260 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:58:06.990  6252  6260 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:58:06.990  6252  6260 I Adreno-EGL: Local Branch: 
08-16 17:58:06.990  6252  6260 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:58:06.990  6252  6260 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:58:06.990  6252  6260 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:58:07.040  6252  6260 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:58:07.040  6252  6260 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02,
08-16 17:58:07.040  6252  6260 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:58:07.040  6252  6260 I Adreno-EGL: Local Branch: 
08-16 17:58:07.040  6252  6260 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:58:07.040  6252  6260 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:58:07.040  6252  6260 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:58:07.100  1015  1250 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:58:07.120  1935  6283 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:07.120  1935  6283 I qtaguid : Tagging socket 73 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1935, getuid(): 10012
,08-16 17:58:07.120  1935  6250 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:07.130   278   991 D EnterpriseController: uids 10012
08-16 17:58:07.130   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:07.130   278   991 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:58:07.130  1935  6250 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:07.130  1935  6250 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1935, getuid(): 10012
,08-16 17:58:07.160  1935  6250 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1935, getuid(): 10012
,08-16 17:58:07.250  1015  1545 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-16 17:58:07.250  1935  6283 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:07.250  1935  6283 I qtaguid : Tagging socket 73 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1935, getuid(): 10012
,08-16 17:58:07.330  1935  4369 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 17:58:07.330  1935  4369 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-16 17:58:07.330  1935  4369 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-16 17:58:06.211+0200, stopTime=2016-08-16 17:58:07.346+0200, duration=1135ms
,08-16 17:58:07.340  1935  6299 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:07.350   278   991 D EnterpriseController: uids 10012
08-16 17:58:07.350   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:07.350   278   991 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-16 17:58:07.350  1935  6299 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:07.350  1935  6299 I qtaguid : Tagging socket 80 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1935, getuid(): 10012
,08-16 17:58:07.380  1935  6299 I qtaguid : Tagging socket 83 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1935, getuid(): 10012
,08-16 17:58:07.390  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-16 17:58:07.560  1935  6299 I qtaguid : Untagging socket 80
,08-16 17:58:07.560  1935  4369 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-16 17:58:08.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:08.640  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:58:08.640  6176  6229 I jxcore-log: 
,08-16 17:58:08.650  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:58:08.650  6176  6229 I jxcore-log: 
,08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:08.650  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:08.650  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:08.650  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:58:08.650  6176  6229 I jxcore-log: 
,08-16 17:58:08.660  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:58:08.660  6176  6229 I jxcore-log: 
,08-16 17:58:09.090  6176  6229 D ExecuteNativeTests: Running unit tests
,08-16 17:58:09.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:09.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 added. We now have 2 listener(s)
,08-16 17:58:09.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:58:09.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:09.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:09.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 added. We now have 2 listener(s)
08-16 17:58:09.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:09.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:09.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.180  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.180  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.180  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.180  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:58:09.190  6176  6229 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-16 17:58:09.190  6176  6229 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:09.190  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.190  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:09.190  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.190  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.190  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 removed from the list
08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 removed from the list
08-16 17:58:09.190  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.190  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.190  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.190  6176  6229 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-16 17:58:09.200  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.200  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.200  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:09.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.200  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.200  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.200  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.200  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.200  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.200  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.200  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.200  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:58:09.210  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.210  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.210  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.210  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.210  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.210  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.210  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.210  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.210  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.210  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.210  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.210  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.210  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.210  6176  6229 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:09.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.220  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:09.220  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.220  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:09.220  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.220  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:09.220  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.220  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.220  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:58:09.220  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:09.220  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:58:09.220  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:09.230  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:58:09.230  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:09.230  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 17:58:09.240  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:58:09.240  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:09.240  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:58:09.250  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:09.260  2648  2737 D BtGatt.GattService: registerClient() - UUID=bbbb0baa-4f20-4fb3-a998-dd6a9f20d1c2
,08-16 17:58:09.300  2648  2718 D BtGatt.GattService: onClientRegistered() - UUID=bbbb0baa-4f20-4fb3-a998-dd6a9f20d1c2, clientIf=6
,08-16 17:58:09.300  6176  6184 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.300  2648  2658 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.310  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:09.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:09.310  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:09.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.310  2648  2733 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.310  2648  2733 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:09.320  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:09.320  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.320  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.320  6176  6229 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.330  2648  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:58:09.330  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.330  2648  2733 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:09.330  2648  2733 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:09.330  2648  2733 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:58:09.330  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.330  6176  6229 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:09.330  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:09.330  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:09.330  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.330  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:58:09.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:09.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:58:09.330  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:09.330  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:09.330   288   288 E SMD     : DCD OFF
,08-16 17:58:09.340  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:58:09.340  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:09.340  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.340  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.340  2648  2733 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:09.340  2648  2733 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.340  2648  2737 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.340  2648  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:09.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:58:09.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:09.340  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:09.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-16 17:58:09.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.350  2648  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:58:09.350  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-16 17:58:09.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.350  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.350  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
,08-16 17:58:09.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.350  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.350  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.350  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.350  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.350  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.350  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.350  6176  6229 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:09.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:09.360  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:58:09.360  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.360  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.370  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.370  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.370  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.380  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.380  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:09.380  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.380  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.380  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:09.380  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.380  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:09.390  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-16 17:58:09.390  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:58:09.390  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:58:09.390  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:09.390  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:09.400  2648  2665 D BtGatt.GattService: registerClient() - UUID=80b9802f-e1d5-4133-b90f-3fdf2a6df5ff
,08-16 17:58:09.400  2648  2733 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 24
,08-16 17:58:09.400  2648  2733 D BtGatt.ScanManager: filter size is 1
,08-16 17:58:09.400  2648  2733 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 17:58:09.410  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:09.410  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.410  2648  2733 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:09.420  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:58:09.420  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.420  2648  2733 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:09.420  2648  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 17:58:09.420  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.440  2648  2718 D BtGatt.GattService: onClientRegistered() - UUID=80b9802f-e1d5-4133-b90f-3fdf2a6df5ff, clientIf=6
,08-16 17:58:09.440  6176  6188 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.440  2648  2737 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.440  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.440  2648  2733 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.440  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:09.440  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:09.440  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:09.450  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.450  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.450  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:09.450  2648  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-16 17:58:09.450  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.450  2648  2733 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:09.450  2648  2733 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:09.450  2648  2733 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-16 17:58:09.450  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.460  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:09.460  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.460  2648  2733 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:58:09.460  2648  2733 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.460  6176  6229 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.470  2648  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:09.470  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.470  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.470  6176  6229 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:09.470  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:09.470  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:09.470  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:09.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:09.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:58:09.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:09.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:58:09.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:09.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.470  2648  2658 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.470  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-16 17:58:09.480  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.480  2648  2665 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:09.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:09.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:09.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:09.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:09.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:09.490  1935  6298 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:58:09.490  1935  6298 I qtaguid : Tagging socket 80 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1935, getuid(): 10012
,08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.490  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.490  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.490  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.490  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.490  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.490  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.490  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.490  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.490  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.490  6176  6229 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:58:09.500  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:09.500  2648  2733 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 25
,08-16 17:58:09.500  2648  2733 D BtGatt.ScanManager: filter size is 1,
08-16 17:58:09.500  2648  2733 D BtGatt.ScanManager: delete FilterIndex - 4
,08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.500  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.500  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.500  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.510  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:09.510  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.510  2648  2733 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:09.510  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:09.510  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:09.510  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:09.510  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.510  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:09.510  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:58:09.510  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.510  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-16 17:58:09.520  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.520  2648  2733 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:09.520  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:09.520  2648  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-16 17:58:09.520  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:09.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:09.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:09.530  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:09.530  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:09.530  2648  2658 D BtGatt.GattService: registerClient() - UUID=c0378fe5-a31a-4cf5-b262-1869a885e7e6
,08-16 17:58:09.570  2648  2718 D BtGatt.GattService: onClientRegistered() - UUID=c0378fe5-a31a-4cf5-b262-1869a885e7e6, clientIf=6
,08-16 17:58:09.570  6176  6191 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:09.570  2648  2665 D BtGatt.GattService: start scan with filters
,08-16 17:58:09.570  2648  2733 D BtGatt.ScanManager: handling starting scan
,08-16 17:58:09.570  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:58:09.570  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:09.580  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:09.580  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:09.580  2648  2718 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:09.580  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.580  2648  2733 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:09.580  2648  2733 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:09.580  2648  2733 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-16 17:58:09.580  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:09.580  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.580  2648  2733 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:09.580  2648  2733 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:09.580  2648  2718 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:09.580  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.580  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.580  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:09.580  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:58:09.590  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:58:09.590  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.590  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:09.600  2648  2733 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 26
,08-16 17:58:09.600  6176  6229 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:58:09.600  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.600  6176  6229 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:58:09.600  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.600  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:09.600  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:09.600  2648  2737 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:09.600  2648  2658 D BtGatt.GattService: unregisterClient() - clientIf=6
08-16 17:58:09.600  2648  2733 D BtGatt.ScanManager: filter size is 1
08-16 17:58:09.600  2648  2733 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:09.600  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:09.600  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:09.610  2648  2718 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:09.610  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:09.610  2648  2733 D BtGatt.ScanManager: stopping BLe Batch
08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:09.610  2648  2718 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-16 17:58:09.610  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.610  2648  2733 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:09.610  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:09.610  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.610  6176  6229 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:58:09.610  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.610  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.610  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:09.610  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.610  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.610  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.610  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:09.610  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.610  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.610  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.610  2648  2718 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:09.610  2648  2718 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.610  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.610  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.610  6176  6229 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 17:58:09.610  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.610  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.610  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.620  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.620  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 17:58:09.620  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.620  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.620  6176  6229 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:58:09.620  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.620  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.620  6176  6229 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 17:58:09.620  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.620  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.620  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.620  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.620  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.620  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:09.620  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:09.630  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list,
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:58:09.630  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
,08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-16 17:58:09.630  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:58:09.630  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.630  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.630  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.630  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.630  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.630  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.630  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.630  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.630  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.630  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.630  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.630  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 17:58:09.630  6176  6229 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:58:09.630  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:58:09.630  6176  6229 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.630  6176  6229 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.630  6176  6229 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:58:09.630  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:58:09.630  6176  6229 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:58:09.630  6176  6229 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:58:09.640  6176  6309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1133)
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6310 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1133
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:58:09.640  6176  6229 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.640  6176  6229 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.640  6176  6229 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.640  6176  6229 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:58:09.640  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.640  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.640  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.640  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.640  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.640  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.640  6176  6309 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.650  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.650  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.650  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.650  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.650  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.650  6176  6309 D BluetoothSocket: connect(): myUserId = 0
08-16 17:58:09.650  6176  6309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.650  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.650  6176  6229 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 17:58:09.650  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.650  2648  2665 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:58:09.660  6176  6309 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[107]}
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:09.660  6176  6176 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6176 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.660  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.660  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.660  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.660  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.660  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:09.660  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6312 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:09.660  6176  6312 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.660  6176  6229 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 17:58:09.660  6176  6229 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:58:09.660  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:58:09.660  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.660  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.660  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.660  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.660  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.660  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.660  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.660  6176  6312 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
08-16 17:58:09.660  6176  6312 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:09.660  6176  6312 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:09.660  6176  6312 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2706009d
08-16 17:58:09.660  6176  6312 D BluetoothSocket: channel: 6
08-16 17:58:09.660  6176  6312 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@82c4912, channel: 6, state: LISTENING
08-16 17:58:09.660  6176  6312 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@82c4912, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2706009d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@f0ac8e3mSocket: android.net.LocalSocket@335ee2e0 impl:android.net.LocalSocketImpl@21c70999 fd:FileDescriptor[108]
08-16 17:58:09.660  6176  6312 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@335ee2e0 impl:android.net.LocalSocketImpl@21c70999 fd:FileDescriptor[108]
08-16 17:58:09.660  6176  6312 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:58:09.660  6176  6312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:58:09.660  6176  6312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:58:09.660  6176  6176 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.670  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.670  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.670  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.670  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.670  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:09.670  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:09.670  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30684362 not in the list
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.670  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:09.670  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:09.670  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:09.670  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20b8bcf3 not in the list
08-16 17:58:09.670  6176  6229 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:58:09.670  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.670  6176  6229 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 17:58:09.670  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:58:09.670  6176  6229 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:58:09.670  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:58:09.680  6176  6229 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:09.680  6176  6229 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 17:58:09.680  6176  6229 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:58:09.680  6176  6229 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 17:58:09.680  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.680  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c01e45e added. We now have 2 listener(s)
08-16 17:58:09.680  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.680  6176  6229 D BluetoothAdapter: enable()
,08-16 17:58:09.680  6176  6229 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 17:58:09.680  1015  1138 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:09.680  1015  1138 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:09.680  1015  1138 D SecContentProvider2: mCursor = null
08-16 17:58:09.680  1015  1138 D WifiService: setWifiEnabled: true pid=6176, uid=10155
08-16 17:58:09.680  1015  1138 W ActivityManager: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:09.680  1015  1138 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:09.680  1015  1138 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:09.680  1015  1138 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:58:09.680  1015  1138 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:09.680  1015  1138 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:09.680  1015  1138 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:09.680  1015  1138 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:09.690  1015  1138 D SettingsProvider: name = wifi_on
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f17103f added. We now have 3 listener(s)
08-16 17:58:09.690  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@237f4d0c added. We now have 4 listener(s)
08-16 17:58:09.690  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:09.690  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f5a655 added. We now have 5 listener(s)
08-16 17:58:09.690  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:09.700  1015  3089 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:09.700  1015  3089 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:09.700  1015  3089 D SecContentProvider2: mCursor = null
08-16 17:58:09.700  1015  3089 D WifiService: setWifiEnabled: false pid=6176, uid=10155
08-16 17:58:09.700  1015  3089 D SettingsProvider: name = wifi_on
08-16 17:58:09.700  1015  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:58:09.710  2094  2094 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:58:09.710  2094  2094 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-16 17:58:09.710  2094  2094 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:09.710  6176  6229 D BluetoothAdapter: disable()
08-16 17:58:09.710  2094  2094 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:58:09.710  1015  3204 D SettingsProvider: name = bluetooth_on
08-16 17:58:09.710  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:58:09.720  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:09.720  2648  2715 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-16 17:58:09.720  2648  2715 D BluetoothAdapterProperties: Setting state to 13
08-16 17:58:09.720  2648  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:58:09.720  2648  2715 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:09.720  2648  2715 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:58:09.720  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:09.720  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.720  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.720  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.720  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:09.720  2648  2648 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 17:58:09.720  2648  2715 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:58:09.730  2648  2715 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-16 17:58:09.730  2648  2715 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:58:09.730  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c419341, channel: 19, state: LISTENING
,08-16 17:58:09.730  1015  1126 E WifiNative-wlan0: do suspend true
08-16 17:58:09.730  1015  1354 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.730  1015  1354 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.730  1015  1354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.730  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c419341, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38956c09, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@180fb0e6mSocket: android.net.LocalSocket@3e789627 impl:android.net.LocalSocketImpl@204200d4 fd:FileDescriptor[74]
08-16 17:58:09.730  1015  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:09.730  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e789627 impl:android.net.LocalSocketImpl@204200d4 fd:FileDescriptor[74]
,08-16 17:58:09.730  2648  2715 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:58:09.730  2648  2715 D BluetoothAdapterProperties: mDiscovering is false
,08-16 17:58:09.730  1015  1028 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:09.730  2648  2715 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:58:09.730  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.740  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.740  2648  2718 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:09.740  2648  2718 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:58:09.740  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.740  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.740  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:09.740  2648  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:58:09.740  2648  2715 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-16 17:58:09.740  2648  2715 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:58:09.740  2648  2715 E bt-btif : cmd socket is not created
,08-16 17:58:09.740  2648  2715 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 17:58:09.740  2648  2818 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-16 17:58:09.740  2648  2818 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:58:09.740  2648  4957 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 17:58:09.740  1324  1324 D BluetoothPbap: Proxy object disconnected
08-16 17:58:09.740  1324  1324 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:58:09.740  6176  6309 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b76715b, channel: -1, state: INIT
08-16 17:58:09.740  6176  6309 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b76715b, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@f5a2df8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@93752d1mSocket: android.net.LocalSocket@26702136 impl:android.net.LocalSocketImpl@2da0c837 fd:FileDescriptor[107]
08-16 17:58:09.740  6176  6309 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@26702136 impl:android.net.LocalSocketImpl@2da0c837 fd:FileDescriptor[107]
08-16 17:58:09.740  6176  6309 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1133)
,08-16 17:58:09.750  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:09.750  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.750  2648  2818 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:58:09.750  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.750  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:58:09.760  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:09.760  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.760  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:58:09.760  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:58:09.760  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:09.760  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:58:09.770  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.770  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:09.770  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:58:09.780  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:09.780  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:09.780  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:09.780  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:09.790  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:09.790  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-16 17:58:09.790  1779  1779 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:09.790  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3195f572, channel: 5, state: LISTENING
,08-16 17:58:09.790  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3195f572, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367fee0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15ce6dc3mSocket: android.net.LocalSocket@16285640 impl:android.net.LocalSocketImpl@2ef46979 fd:FileDescriptor[76]
08-16 17:58:09.790  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@16285640 impl:android.net.LocalSocketImpl@2ef46979 fd:FileDescriptor[76]
,08-16 17:58:09.790  2648  2648 I BtOppRfcommListener: stopping Accept Thread
08-16 17:58:09.790  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c9f6be, channel: 12, state: LISTENING
08-16 17:58:09.790  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c9f6be, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7c6a28, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e20231fmSocket: android.net.LocalSocket@175c966c impl:android.net.LocalSocketImpl@2bc92435 fd:FileDescriptor[80]
08-16 17:58:09.790  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@175c966c impl:android.net.LocalSocketImpl@2bc92435 fd:FileDescriptor[80]
08-16 17:58:09.790  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-16 17:58:09.790  2648  4957 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:58:09.790  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:09.790  1015  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:09.790  1015  1384 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:09.790  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:58:09.790  1015  3204 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 17:58:09.800  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:09.800  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:09.800  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:09.800  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:09.800  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.800  2648  2648 V BluetoothOppManager: cleanUp...
,08-16 17:58:09.810  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:09.810  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:09.810  1015  1027 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:09.810  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.810  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:09.810  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:09.810  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:09.820  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:09.830  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:09.830  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:09.830  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:58:09.830  1015  1542 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast,
08-16 17:58:09.830  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:09.830  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.830  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.830  1015  1542 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:09.850  6318  6318 E Zygote  : MountEmulatedStorage()
08-16 17:58:09.850  6318  6318 I libpersona: KNOX_SDCARD checking this for 10003
08-16 17:58:09.850  6318  6318 E Zygote  : v2
08-16 17:58:09.850  6318  6318 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:09.850  6318  6318 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:09.850  1015  1542 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6318 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-16 17:58:09.850  6318  6318 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:09.850  6318  6318 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:09.850  1935  6298 I qtaguid : Untagging socket 80
,08-16 17:58:09.880  1935  4369 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-16 17:58:09.890  6318  6318 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:09.890  6318  6318 D ActivityThread: Added TimaKeyStore provider,
,08-16 17:58:09.910  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-16 17:58:09.920  6318  6318 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:09.940  2648  2818 W bt-btif : ag scb idx 1 not allocated
08-16 17:58:09.940  2648  2818 W bt-btif : ag scb idx 2 not allocated
08-16 17:58:09.940  2648  2818 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:58:09.940  2648  2919 I bt_userial_mct: exiting userial_read_thread
08-16 17:58:09.940  2648  2919 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:58:09.940  2648  2718 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:58:09.940  2648  2820 I bt_vendor: hw_epilog_process
08-16 17:58:09.940  2648  2718 D bt_userial_mct: userial_close
08-16 17:58:09.940  2648  2718 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:58:09.960  6318  6318 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-16 17:58:09.960  6318  6318 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-16 17:58:09.960  6318  6318 D UserAnalysis: Create SecureDbHelper
,08-16 17:58:09.960  6318  6318 D IntelligenceServiceApplication: onCreate(),
,08-16 17:58:09.970  1015  1545 I ActivityManager: Killing 5300:com.google.android.talk/u0a104 (adj 15): empty #31
,08-16 17:58:09.970  1015  3089 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-16 17:58:09.980  6318  6318 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-16 17:58:09.980  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.980  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.980  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:09.980  1015  3089 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:09.990  6337  6337 E Zygote  : MountEmulatedStorage()
08-16 17:58:09.990  6337  6337 E Zygote  : v2
08-16 17:58:09.990  6337  6337 I libpersona: KNOX_SDCARD checking this for 10107
08-16 17:58:09.990  6337  6337 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:09.990  6337  6337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:10.000  1015  3089 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6337 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-16 17:58:10.000  6318  6318 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-16 17:58:10.000  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-16 17:58:10.000  6337  6337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:10.000  6337  6337 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:10.010  6318  6318 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-16 17:58:10.020  6337  6337 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.020  6337  6337 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.160  6176  6176 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:10.190  2648  2718 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:58:10.190  2648  2718 I bt_vendor: bluetooth satus is on
08-16 17:58:10.190  2648  2718 I bt_vendor: bt-vendor : resetting BT status
08-16 17:58:10.190  2648  2718 I bt_vendor: Starting hciattach daemon
08-16 17:58:10.190  2648  2718 I bt_vendor: try to set false
,08-16 17:58:10.190  2648  2718 I bt_vendor: Starting hciattach daemon
08-16 17:58:10.190  2648  2718 I bt_vendor: try to set false
08-16 17:58:10.190  2648  2718 I bt_vendor: cleanup
,08-16 17:58:10.190  2648  2818 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 17:58:10.190  2648  2718 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:58:10.190  2648  2718 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:58:10.200  2648  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-16 17:58:10.200  2648  2715 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:10.200  2648  2715 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-16 17:58:10.200  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:58:10.200  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:58:10.200  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:58:10.200  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.200  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.200  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.200  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.200  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.210  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:10.210  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:10.210  2648  2648 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:58:10.210  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:10.210  2648  2648 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:58:10.210  2648  2648 D BtGatt.GattService: stop()
08-16 17:58:10.210  2648  2648 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:58:10.220  1015  1354 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.220  1015  1354 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.220  1015  1354 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.220  1015  1354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.220  1015  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.220  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:58:10.220  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
08-16 17:58:10.220  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:10.220  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:10.220  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.220  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.220  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.220  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.220  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.220  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-16 17:58:10.230  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:10.230  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:10.230  1015  3089 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:10.230  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.230  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.230  1015  3089 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.230  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.230  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:10.230  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:10.230  1015  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.230  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 17:58:10.230  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.230  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.230  1015  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.230  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.230  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:10.230  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService,
08-16 17:58:10.240  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:10.240  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.240  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.240  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.240  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.240  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.240  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.240  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.240  2648  2715 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.240  1015  1138 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:10.240  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.240  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.240  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.240  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.240  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:58:10.240  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:58:10.240  2648  2715 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:10.250  1015  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:10.250  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.250  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.250  1015  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.250  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:10.250  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:10.250  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:10.250  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:10.250  2648  2715 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:58:10.250  2648  2715 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:10.250  2648  2715 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:58:10.250  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-16 17:58:10.260  2648  2648 D HeadsetService: Received stop request...Stopping profile...
,08-16 17:58:10.260  1015  1542 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,08-16 17:58:10.260  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-16 17:58:10.260  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.260  1015  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.260  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-16 17:58:10.260  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.270  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-16 17:58:10.270  2648  2648 D A2dpService: Received stop request...Stopping profile...
,08-16 17:58:10.270  2648  2752 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:58:10.270  1324  1324 D HeadsetProfile: Bluetooth service disconnected
,08-16 17:58:10.270  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.270  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:10.270  2648  2648 D HidService: Received stop request...Stopping profile...
08-16 17:58:10.270  2648  2648 D HidService: Stopping Bluetooth HidService
08-16 17:58:10.270  1324  1324 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:10.270  1324  1324 D A2dpProfile: Bluetooth service disconnected
08-16 17:58:10.270  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:58:10.270  2648  2648 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-16 17:58:10.270  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:58:10.270  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 17:58:10.270  2865  2865 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:10.270  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.280  1324  1324 D BluetoothInputDevice: Proxy object disconnected
,08-16 17:58:10.280  1324  1324 D HidProfile: Bluetooth service disconnected
,08-16 17:58:10.280  2648  2648 D HealthService: Received stop request...Stopping profile...,
08-16 17:58:10.280  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.280  2648  2648 D PanService: Received stop request...Stopping profile...
,08-16 17:58:10.280  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.280  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:58:10.280  1324  1324 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:58:10.280  1324  1324 D PanProfile: Bluetooth service disconnected
,08-16 17:58:10.280  2648  2648 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:58:10.290  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.290  1324  1324 D BluetoothMap: Proxy object disconnected
08-16 17:58:10.290  1324  1324 D MapProfile: Bluetooth service disconnected
08-16 17:58:10.290  2648  2648 D SapService: Received stop request...Stopping profile...
08-16 17:58:10.290  2648  2648 D SapService: Stopping Bluetooth SapService,
08-16 17:58:10.290  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@175eaa67
,08-16 17:58:10.290  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-16 17:58:10.290  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:10.290  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:58:10.290  1324  1324 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:58:10.290  1324  1324 D SapProfile: Bluetooth service disconnected
,08-16 17:58:10.300  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:58:10.300  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:58:10.300  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-16 17:58:10.300  2648  2648 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-16 17:58:10.300  2648  2755 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 17:58:10.300  2648  2648 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:58:10.300  2648  2648 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-16 17:58:10.300  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:58:10.300  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.300  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:10.300  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:58:10.300  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.300  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:58:10.300  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:58:10.300  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:10.300  2648  2648 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-16 17:58:10.300  2648  2648 E BluetoothAdapterService(392079975): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-16 17:58:10.300  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-16 17:58:10.300  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-16 17:58:10.300  2648  2715 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:58:10.300  2648  2715 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:10.300  2648  2715 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:58:10.300  2648  2715 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:10.300  2648  2715 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 17:58:10.300  2648  2715 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:58:10.310  2648  2715 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:58:10.310  2648  2715 I BluetoothAdapterState: Entering OffState
,08-16 17:58:10.310  1935  2113 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.310  1935  2113 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.310  1324  6361 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:58:10.310  1174  2341 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:10.310  1174  2341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.310  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.310  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.310  1433  1442 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:10.310  1433  1442 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.320  2648  2665 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:10.320  2648  2658 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.320  2648  2658 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.320  2865  2877 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.320  2865  2877 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.320  1324  6361 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.320  1324  6361 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=246 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=238 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(P,G:92)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543),
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:58:10.320  6337  6337 D StrictMode: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=185 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6,337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  1324  1333 D Bluetoothsap: onBluetoothStateChange: up=false
08-16 17:58:10.320  1015  3089 I ActivityManager: Killing 4996:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-16 17:58:10.320  1324  1333 D Bluetoothsap: Unbinding service...
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=182 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-16 17:58:10.320  6337  6337 D StrictMode: ,	at com.google.v.a.a.eq.a(PG:12397)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: ,	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.k.c(PG:583)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:58:10.320  6337  6337 D StrictMode: 	,at com.google.r.e.b(PG:13188)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
,08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  6337  6337 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-16 17:58:10.320  6337  6337 D StrictMode: ,	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.io.File.exists(File.java:363)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-16 17:58:10.320  6337  6337 D StrictMode: ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:10.320  6337  6337 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:10.320  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:10.330  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:10.330  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:10.340  1457  2968 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.340  1457  2968 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.340  2865  2877 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:10.340  1324  1338 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:58:10.340  6176  6188 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.340  6176  6188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.340  6176  6188 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:58:10.340  6176  6188 D BluetoothLeAdvertiser: Exit stop advertising
08-16 17:58:10.340  6176  6188 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:58:10.340  6176  6188 D BluetoothLeScanner: Exiting stopAllScan
08-16 17:58:10.340  1324  6361 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:58:10.340  1447  1471 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:10.340  1447  1471 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:10.340  1324  1333 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:58:10.340  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 17:58:10.350  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:58:10.350  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:10.350  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-16 17:58:10.350  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:10.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:10.360  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:10.360  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-16 17:58:10.360  1174  1739 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:10.360  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:10.360  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-16 17:58:10.360  1174  1739 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:10.360  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:10.360  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:10.360  1779  1779 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:10.360  1015  1542 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:10.370  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:10.370  1015  3089 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:10.370  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:10.370  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:10.370  1935  2125 D BluetoothAdapter: 649232868: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:10.370  1935  2125 D BluetoothAdapter: 649232868: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:10.370  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:10.380  1015  3200 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:10.380  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.380  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.380  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.380  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.380  6337  6358 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:58:10.380  2648  2718 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 17:58:10.380  2648  2648 I GKI_LINUX: GKI_exit_task 1 done
,08-16 17:58:10.390  2648  2648 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 17:58:10.390  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:58:10.390  2648  2648 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:58:10.390  1015  1545 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:10.390  1015  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.390  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.390  1015  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.390  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:10.390  2648  2648 I art     : System.exit called, status: 0
08-16 17:58:10.390  2648  2648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:58:10.400  1015  3202 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:10.400  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.400  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.400  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.400  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:10.400  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:10.410  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:10.410  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:58:10.420  1015  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:10.420  1015  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:10.420  1015  1027 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-16 17:58:10.420  1015  1027 W BroadcastQueue: android.os.TransactionTooLargeException
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
,08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	,at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	,at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-16 17:58:10.420  1015  1027 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:10.420  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast,
,08-16 17:58:10.430  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.430  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.430  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-16 17:58:10.430  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.440  6369  6369 E Zygote  : MountEmulatedStorage()
,08-16 17:58:10.440  6369  6369 E Zygote  : v2
08-16 17:58:10.440  6369  6369 I libpersona: KNOX_SDCARD checking this for 1002
08-16 17:58:10.440  6369  6369 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:10.440  1015  1027 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6369 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-16 17:58:10.440  6369  6369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:10.450  6369  6369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:58:10.450  6369  6369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:10.470  6369  6369 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.470  6369  6369 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.480  6369  6369 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 17:58:10.480  6369  6369 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:58:10.510  6369  6369 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:58:10.530  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:58:10.530  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:10.530  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:10.530  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-16 17:58:10.530  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:10.530  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.530  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.530  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.540   278   995 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:10.540  1935  4334 V NativeCrypto: Read error: ssl=0xb8fcd650: I/O error during system call, Connection timed out
,08-16 17:58:10.540  1935  4334 V NativeCrypto: SSL shutdown failed: ssl=0xb8fcd650: I/O error during system call, Broken pipe,
,08-16 17:58:10.540  1015  1250 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012,
,08-16 17:58:10.540  1935  4334 E GCM     : Wifi connection closed with errorCode 20
08-16 17:58:10.550  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:10.550  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:10.550  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-16 17:58:10.550  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:10.550  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 17:58:10.550  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:10.550  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-16 17:58:10.550  1015  2205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:10.550  1015  2205 I qtaguid : Tagging socket 358 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
08-16 17:58:10.550  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:10.550  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:10.550  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:10.550  1015  2205 I qtaguid : Untagging socket 358
08-16 17:58:10.550  1015  2205 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-16 17:58:10.550  6369  6369 D BtSettings.ProfileConfig: Adding GattService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding A2dpService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding HidService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding HealthService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding PanService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding SapService
,08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:58:10.560  6369  6369 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 17:58:10.560  6369  6369 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:58:10.570  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:10.570  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
08-16 17:58:10.570  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:10.570  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:58:10.570  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.570  1015  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:58:10.570  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.570  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:10.570  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:10.570  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-16 17:58:10.570  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:10.580  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-16 17:58:10.580  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-16 17:58:10.580  1015  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:10.580  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:58:10.580  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-16 17:58:10.590  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-16 17:58:10.590  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.590  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  1027 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  1027 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.590  1015  1027 D SettingsProvider: ret = -1
08-16 17:58:10.590  1015  1250 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-16 17:58:10.590  1015  1250 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.590  1015  1250 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  1250 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  1250 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  1250 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.590  1015  1250 D SettingsProvider: ret = -1
08-16 17:58:10.590  1015  1543 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-16 17:58:10.590  1015  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.590  1015  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-16 17:58:10.590  1015  1543 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  1543 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.590  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:10.590  1015  1543 D SettingsProvider: ret = -1
08-16 17:58:10.590  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:10.590  1015  3201 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 17:58:10.590  1015  3201 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:10.590  1015  3201 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  3201 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  3201 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  3201 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:58:10.590  1015  3201 D SettingsProvider: ret = -1
,08-16 17:58:10.590  1015  3204 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-16 17:58:10.590  1015  3204 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.590  1015  3204 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  3204 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  3204 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  3204 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.590  1015  3204 D SettingsProvider: ret = -1
08-16 17:58:10.590  1015  1353 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:58:10.590  1015  1353 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.590  1015  1353 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.590  1015  1353 D SettingsProvider: selectionArgs: false
08-16 17:58:10.590  1015  1353 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.590  1015  1353 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.590  1015  1353 D SettingsProvider: ret = -1
,08-16 17:58:10.600  1015  3202 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-16 17:58:10.600  1015  3202 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  3202 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-16 17:58:10.600  1015  3202 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  3202 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  3202 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  3202 D SettingsProvider: ret = -1
08-16 17:58:10.600  1015  1138 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:58:10.600  1015  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:58:10.600  1015  1138 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  1138 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  1138 D SettingsProvider: ret = -1
08-16 17:58:10.600  1015  1545 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:10.600  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:58:10.600  1015  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:58:10.600  1015  1545 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  1545 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  1125 D WifiP2pService: P2pDisablingState
08-16 17:58:10.600  1015  1545 D SettingsProvider: ret = -1
08-16 17:58:10.600  1015  1354 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:10.600  1015  1354 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:58:10.600  1015  1354 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.600  1015  1125 D WifiP2pService: p2p socket connection lost
08-16 17:58:10.600  1015  1354 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  1354 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  1354 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  1354 D SettingsProvider: ret = -1
08-16 17:58:10.600  1015  1125 D WifiP2pService: P2pDisabledState
08-16 17:58:10.600  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:58:10.600  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:10.600  1015  1544 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:58:10.600  1015  1045 D WifiDisplayController: disconnect
08-16 17:58:10.600  1015  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  1045 D WifiDisplayController: updateConnection
08-16 17:58:10.600  1015  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.600  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:10.600  1015  1544 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:10.600  1015  1544 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  1544 D SettingsProvider: ret = -1
08-16 17:58:10.600  1015  1126 E WifiNative-wlan0: do suspend true
08-16 17:58:10.600  1015  1384 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-16 17:58:10.600  1015  1384 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:10.600  1015  1384 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:10.600  1015  1384 D SettingsProvider: selectionArgs: false
08-16 17:58:10.600  1015  1384 D SettingsProvider: selectionArgs: 1002
08-16 17:58:10.600  1015  1384 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:10.600  1015  1384 D SettingsProvider: ret = -1
,08-16 17:58:10.600  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:58:10.600  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-16 17:58:10.600  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:10.600  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:10.610  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:10.610  1015  1543 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:10.610  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:10.620  1015  1353 I ActivityManager: Killing 5550:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-16 17:58:10.620  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:10.620  1015  3202 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:10.620  1015  3202 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.620  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.620  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.620  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.630  1935  6391 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-16 17:58:10.630  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:10.630  1015  1545 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:10.640  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.640  1015  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.640  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.640  1015  1384 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-16 17:58:10.640  1015  1384 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4141, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-16 17:58:10.640  1015  1384 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-16 17:58:10.640  1015  1384 D BatteryService: stay LED for charging
08-16 17:58:10.640  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:58:10.640  1015  1015 I MotionRecognitionService: Plugged
08-16 17:58:10.640  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:58:10.650  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:58:10.650  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:10.650  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-16 17:58:10.650  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-16 17:58:10.660  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:10.660  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:10.660  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.660  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:10.660  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:10.660  3588  3588 I Hs20UtilService: Starting #8
,08-16 17:58:10.660  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:10.670  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:10.670  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:10.670  1015  1543 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:10.670  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:58:10.670  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-16 17:58:10.670  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:58:10.670  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:10.670  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:10.670  1015  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.670  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:10.670  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:10.670  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
08-16 17:58:10.670  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:10.670  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:10.680  1935  6391 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:58:10.680  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.680  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:10.680  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-16 17:58:10.680  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-16 17:58:10.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:10.680  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:10.690  6392  6392 E Zygote  : MountEmulatedStorage()
,08-16 17:58:10.690  6392  6392 E Zygote  : v2
08-16 17:58:10.690  6392  6392 I libpersona: KNOX_SDCARD checking this for 10104
08-16 17:58:10.690  6392  6392 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:10.700  6392  6392 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:10.700  1015  1027 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6392 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 17:58:10.700  6392  6392 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:10.700  6392  6392 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-16 17:58:10.720  6392  6392 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:10.720  6392  6392 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:10.730  6392  6392 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 17:58:10.930  6392  6415 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 17:58:10.930  6392  6415 I Babel   : MmsConfig.loadMmsSettings
,08-16 17:58:10.940  6392  6415 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml,
08-16 17:58:10.940  6392  6415 I Babel   : MmsConfig.loadFromDatabase
,08-16 17:58:10.960  6392  6415 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-16 17:58:10.960  6392  6415 I Babel   : MmsConfig.loadFromResources
,08-16 17:58:10.960  6392  6415 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:58:10.960  6392  6415 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-16 17:58:10.970  1015  1545 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-16 17:58:10.970  1015  1545 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-16 17:58:10.970  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:10.970  1015  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:10.970  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:58:10.970  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:11.010  6392  6392 I Babel_StickerModule: App launched.
,08-16 17:58:11.010  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:11.010  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:11.020  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:11.020  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-16 17:58:11.020  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:11.020  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:11.020  1015  3200 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-16 17:58:11.020  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:11.020  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.020  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.020  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.020  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.030   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-16 17:58:11.030   283   283 W QCamera2Factory: getCameraInfo: X
08-16 17:58:11.030   283   705 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-16 17:58:11.030   283   705 W QCamera2Factory: getCameraInfo: X
,08-16 17:58:11.030  6417  6417 E Zygote  : MountEmulatedStorage()
08-16 17:58:11.030  6417  6417 E Zygote  : v2
08-16 17:58:11.030  6417  6417 I libpersona: KNOX_SDCARD checking this for 10068
08-16 17:58:11.030  6417  6417 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:11.030  6417  6417 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:11.040  6417  6417 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:11.040  6417  6417 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.040  1015  3200 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6417 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:11.050  6392  6392 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:58:11.060  6392  6392 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:58:11.060  6392  6392 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:58:11.060  6392  6392 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-16 17:58:11.060  6392  6392 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-16 17:58:11.070  6417  6417 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.070  6417  6417 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.070  6392  6392 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-16 17:58:11.070  6392  6392 W AudioCapabilities: Unsupported mime audio/x-ima
,08-16 17:58:11.070  6392  6392 W AudioCapabilities: Unsupported mime audio/qcelp
,08-16 17:58:11.080  6392  6392 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 17:58:11.080  6417  6417 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:58:11.090  6392  6392 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:58:11.090  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:58:11.090  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:11.090  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:11.100  6392  6392 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-16 17:58:11.100  6392  6392 W VideoCapabilities: Unsupported mime video/wvc1
,08-16 17:58:11.100  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 17:58:11.110  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-16 17:58:11.110  6392  6392 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-16 17:58:11.110  6392  6392 W VideoCapabilities: Unsupported mime video/mp43
,08-16 17:58:11.120  6392  6392 W VideoCapabilities: Unsupported mime video/sorenson
,08-16 17:58:11.120  6392  6392 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 17:58:11.140  6417  6417 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:11.140  1015  1354 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-16 17:58:11.140  1015  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.140  1015  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.140  1015  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.140  1015  1354 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.140  6392  6392 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:58:11.160  6432  6432 E Zygote  : MountEmulatedStorage(),
08-16 17:58:11.160  6432  6432 E Zygote  : v2
08-16 17:58:11.160  6432  6432 I libpersona: KNOX_SDCARD checking this for 10069,
08-16 17:58:11.160  6432  6432 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:11.160  6432  6432 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:11.160  1015  1354 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6432 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:11.160  6432  6432 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:11.160  6432  6432 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.180  1015  1250 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-16 17:58:11.180  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-16 17:58:11.180  6432  6432 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.180  6432  6432 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.180  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.180  1015  1250 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:11.180  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-16 17:58:11.200  1015  1028 I ActivityManager: Killing 5463:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-16 17:58:11.210  6432  6432 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:11.220  1015  1250 I ActivityManager: Killing 5772:com.sec.pcw.device/1000 (adj 15): empty #31
,08-16 17:58:11.370   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:11.410  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:58:11.410  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:11.410  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:11.410  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:11.410  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.410  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:11.420  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-16 17:58:11.420   278   991 D EnterpriseController: uids 1000
08-16 17:58:11.420  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
08-16 17:58:11.420   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:11.420  1015  1128 E NetdConnector: NDC Command {53 network destroy 502} took too long (865ms)
08-16 17:58:11.420   278   991 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-16 17:58:11.420  1015  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-16 17:58:11.420   278   995 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:11.420  1015  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-16 17:58:11.420  1015  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:58:11.420  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-16 17:58:11.420  1015  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,08-16 17:58:11.420  1015  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-16 17:58:11.420  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 17:58:11.430  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:58:11.430  1174  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
08-16 17:58:11.430  1457  1457 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 17:58:11.430  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-16 17:58:11.430  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:58:11.430  2094  2094 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:11.430  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-16 17:58:11.430  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-16 17:58:11.430  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:58:11.430  1015  2205 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:11.440  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:11.440  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:11.440  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.440  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.440  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.440  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:11.440  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false,
08-16 17:58:11.440  1015  3201 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:11.440  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:11.450  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.450  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.450  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:11.450  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:11.450  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:11.450  1015  1128 D ConnectivityService: nai.networkMonitor.doQuit(),
,08-16 17:58:11.450  1015  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-16 17:58:11.450  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:11.450  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:11.450  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:11.450  3588  3588 I Hs20UtilService: Starting #9
,08-16 17:58:11.450  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:11.450  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false,
,08-16 17:58:11.450  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:11.450  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:11.450  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.450  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.460  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.460  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:11.460  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:11.460  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:11.460  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-16 17:58:11.460  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:11.460  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:11.460  1174  1174 D HotspotTile: onReceive : 0, 0
,08-16 17:58:11.460  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:11.460  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:11.460  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:11.460  1015  1123 V NetworkStats: updateIfacesLocked()
08-16 17:58:11.460  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.460  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:11.460  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:11.460  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:11.460  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-16 17:58:11.460  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:11.460  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:11.470  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:11.470  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.470  1015  1123 V NetworkStats: performPollLocked() took 6ms
08-16 17:58:11.470  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.470  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:58:11.470  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.470  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:11.470  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:11.470  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.470  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:11.470  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:11.470  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:58:11.470  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:11.470  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:58:11.470  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-16 17:58:11.470  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:58:11.470  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:11.480  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:11.480  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:11.480  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:11.480  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:11.480  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:11.480  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:11.480  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:11.480  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:11.480  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-16 17:58:11.480  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.480  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:11.500  1015  1544 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:11.500  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:11.500  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.500  1015  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.500  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:11.520  3588  3588 I Hs20UtilService: Starting #10
08-16 17:58:11.520  1015  1543 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-16 17:58:11.520  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:11.520  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.520  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.520  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.520  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.530  1015  1543 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6450 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:58:11.530  6450  6450 E Zygote  : MountEmulatedStorage()
08-16 17:58:11.530  6450  6450 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:11.530  6450  6450 E Zygote  : v2
08-16 17:58:11.530  6450  6450 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:11.530  6450  6450 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:11.540  6450  6450 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:11.540  6450  6450 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:11.570  6450  6450 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:11.570  6450  6450 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:11.580  2094  2094 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:11.580  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.580  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.580  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.580  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.590  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.590  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.590  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.590  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.590  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.590  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.590  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.590  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.590  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.600  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.600  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.600  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.600  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.600  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.600  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.600  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.600  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.600  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.600  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.610  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.610  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.610  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.610  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.610  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.610  1457  1457 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-16 17:58:11.610  1457  1457 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-16 17:58:11.620  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:11.620  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:11.620  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:11.620  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:11.620  1015  1543 I ActivityManager: Killing 5484:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-16 17:58:11.630  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.630  1015  3202 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.630  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.630  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.630  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.630  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.630  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.630  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.630  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.640  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.640  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.640  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.640  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.640  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.640  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.640  2094  2094 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 17:58:11.640  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:11.640  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:11.640  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:11.650  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.650  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.650  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.650  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.660  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.660  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.660  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.660  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.670  2094  2094 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-16 17:58:11.670  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:11.670  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:11.670  2094  2094 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-16 17:58:11.670  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:11.670  2094  2094 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-16 17:58:11.670  2094  2094 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:11.670  2094  2094 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:11.670  1015  1129 D Tethering: InitialState.processMessage what=4
,08-16 17:58:11.670  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.670  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.670  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.670  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:11.670  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:11.670  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:11.670  1015  1129 E Tethering: No numeric data
,08-16 17:58:11.670  1015  1126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-16 17:58:11.670  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:11.670  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:11.670  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:11.670  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.670  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.670  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.680  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-16 17:58:11.680  1015  1129 D Tethering: clearTetheredNotification()
,08-16 17:58:11.680  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:11.680  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:11.680  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:11.680  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 17:58:11.680  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.680  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.680  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.680  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-16 17:58:11.680  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:11.680  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:11.680  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:11.680  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-16 17:58:11.680  1015  1123 V NetworkStats: performPollLocked() took 6ms
,08-16 17:58:11.680  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:11.690  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:11.690  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:11.730   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb73b77c8
08-16 17:58:11.730   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-16 17:58:11.730   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
08-16 17:58:11.730   273   336 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220839288)
,08-16 17:58:11.760   273   336 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-16 17:58:11.760   273   336 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-16 17:58:11.760   273   336 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220839288) wakelock released: 1, error no: 0
08-16 17:58:11.760   273   336 I rmt_storage: 
,08-16 17:58:11.760   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb73b77c8
,08-16 17:58:11.870  2094  2094 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:11.950  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:11.950  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-16 17:58:11.960  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:11.970  3126  3126 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-16 17:58:11.980  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:11.980  3126  3126 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-16 17:58:11.980  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-16 17:58:11.980  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:11.980  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:11.980  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.980  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:11.980  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.000  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6481 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,08-16 17:58:12.000  6481  6481 E Zygote  : MountEmulatedStorage(),
08-16 17:58:12.000  6481  6481 E Zygote  : v2
08-16 17:58:12.000  6481  6481 I libpersona: KNOX_SDCARD checking this for 1000,
08-16 17:58:12.000  6481  6481 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.000  6481  6481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.000  6481  6481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:58:12.010  6481  6481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.020  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:12.020  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:12.020  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:12.020  2094  2094 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-16 17:58:12.030  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-16 17:58:12.030  6481  6481 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.060  6481  6481 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-16 17:58:12.060  6481  6481 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-16 17:58:12.060  6481  6481 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-16 17:58:12.080  6481  6481 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 17:58:12.080  6481  6481 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-16 17:58:12.080  6481  6481 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-16 17:58:12.080  6481  6481 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:12.080  1015  1543 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-16 17:58:12.080  1015  1543 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-16 17:58:12.080  1015  1543 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-16 17:58:12.080  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.080  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.080  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.080  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.090  6481  6496 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-16 17:58:12.090  6498  6498 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.090  6498  6498 E Zygote  : v2
08-16 17:58:12.090  6498  6498 I libpersona: KNOX_SDCARD checking this for 10111
08-16 17:58:12.090  6498  6498 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.100  6498  6498 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.100  1015  1543 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6498 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:12.100  6498  6498 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:12.100  1015  1543 I ActivityManager: Killing 5788:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-16 17:58:12.100  6498  6498 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.110  1015  1542 I ActivityManager: Killing 4053:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-16 17:58:12.110  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-16 17:58:12.110  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.110  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.110  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.110  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.130  6513  6513 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.130  6513  6513 E Zygote  : v2
08-16 17:58:12.130  6513  6513 I libpersona: KNOX_SDCARD checking this for 10009
08-16 17:58:12.130  6513  6513 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.130  6498  6498 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:12.130  6513  6513 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:58:12.130  6498  6498 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.130  1015  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6513 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:12.130  6513  6513 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:12.130  6513  6513 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.140  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-16 17:58:12.140  1721  1721 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.140  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.140  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.140  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.140  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.140  1015  2722 D SSRM:n  : SIOP:: AP = 340,
,08-16 17:58:12.150  6525  6525 E Zygote  : MountEmulatedStorage(),
,08-16 17:58:12.160  6525  6525 E Zygote  : v2
08-16 17:58:12.160  6525  6525 I libpersona: KNOX_SDCARD checking this for 10145
08-16 17:58:12.160  6525  6525 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.160  6525  6525 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.160  1015  1040 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6525 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-16 17:58:12.160  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-16 17:58:12.160  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-16 17:58:12.160  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:58:12.160  6525  6525 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:12.160  6525  6525 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:58:12.170  1015  1047 I PowerManagerService: [PWL] Off : 50s ago
08-16 17:58:12.170  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:58:12.170  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-16 17:58:12.170  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:12.170  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-16 17:58:12.170  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:12.170  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=721)
08-16 17:58:12.170  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:12.170  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:12.170  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:12.170  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:12.170  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:12.170  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-16 17:58:12.170  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:12.170  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:12.170  1174  1174 D HotspotTile: onReceive : 1, 0
08-16 17:58:12.180  1935  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:12.180  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:12.180   312   312 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 26.534ms
,08-16 17:58:12.190  6513  6513 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.190  6513  6513 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.190  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:12.190  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:12.190  1721  1721 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-16 17:58:12.190  1721  1721 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-16 17:58:12.190  1721  1721 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-16 17:58:12.190  1721  1721 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.200   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 18.778ms
,08-16 17:58:12.210  1294  1314 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
,08-16 17:58:12.210  6525  6525 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:12.210  1721  1721 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-16 17:58:12.210  6525  6525 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.220  1721  1721 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-16 17:58:12.220  1721  1721 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-16 17:58:12.220   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.604ms
,08-16 17:58:12.230  1015  1544 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-16 17:58:12.230  1015  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.230  1015  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.230  1015  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.230  1015  1544 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.240  6525  6525 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-16 17:58:12.240  6543  6543 E Zygote  : MountEmulatedStorage()
08-16 17:58:12.240  6543  6543 E Zygote  : v2
08-16 17:58:12.240  6543  6543 I libpersona: KNOX_SDCARD checking this for 10081
08-16 17:58:12.240  6543  6543 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:12.240  6543  6543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.240  6543  6543 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:12.240  1015  1544 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6543 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:58:12.250  6543  6543 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-16 17:58:12.250  6525  6525 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:12.250  6525  6525 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:58:12.250  6525  6525 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:58:12.250  6525  6525 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-16 17:58:12.270  6543  6543 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.270  6543  6543 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.300  1015  1542 I ActivityManager: Killing 5076:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-16 17:58:12.310  3625  3625 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:58:12 GMT+02:00 2016
,08-16 17:58:12.310  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-16 17:58:12.310  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.310  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.310  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:12.310  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:58:12.320  3625  3625 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:58:12.320  1015  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-16 17:58:12.330  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.330  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.330  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.330  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.330  3625  3625 I KLMS-2.5.183: : KLMSIntentService(): onCreate(),
,08-16 17:58:12.340   288   288 E SMD     : DCD OFF,
,08-16 17:58:12.340  6563  6563 E Zygote  : MountEmulatedStorage(),
08-16 17:58:12.340  3625  3625 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:58:12.340  6563  6563 E Zygote  : v2
08-16 17:58:12.340  6563  6563 I libpersona: KNOX_SDCARD checking this for 10034,
08-16 17:58:12.340  6563  6563 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.340  6563  6563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.340  6563  6563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:12.350  1015  1543 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6563 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-16 17:58:12.350  6563  6563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-16 17:58:12.350  6498  6498 I MusicStore: Database version: 108
,08-16 17:58:12.360  3625  3625 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-16 17:58:12.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:12.370  3625  6561 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:58:12.370  6563  6563 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.370  6563  6563 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.370  3625  6561 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-16 17:58:12.370  1015  1354 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.380  3625  6561 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-16 17:58:12.380  3625  6561 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-16 17:58:12.380  3625  3625 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 17:58:12.410  1015  1138 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:12.410  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:58:12.410  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.410  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.410  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:12.430  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.440  6563  6563 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-16 17:58:12.440  1015  3201 I ActivityManager: Killing 5815:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-16 17:58:12.460  1015  1138 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-16 17:58:12.460  1015  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.460  1015  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.460  1015  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.460  1015  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.470  6584  6584 E Zygote  : MountEmulatedStorage()
,08-16 17:58:12.470  6584  6584 E Zygote  : v2
08-16 17:58:12.470  6584  6584 I libpersona: KNOX_SDCARD checking this for 10113
08-16 17:58:12.470  6584  6584 I libpersona: KNOX_SDCARD not a persona,
08-16 17:58:12.470  6584  6584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.480  1015  1138 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6584 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-16 17:58:12.480  6584  6584 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:12.480  6584  6584 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.480  1015  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-16 17:58:12.480  1015  1545 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.480  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.480  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.480  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.480  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.490  3217  6594 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-16 17:58:12.500  3217  6594 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-16 17:58:12.500  6602  6602 E Zygote  : MountEmulatedStorage()
08-16 17:58:12.500  6602  6602 I libpersona: KNOX_SDCARD checking this for 10035
08-16 17:58:12.500  6602  6602 E Zygote  : v2
08-16 17:58:12.500  6602  6602 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:12.500  6584  6584 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.500  6584  6584 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.500  6602  6602 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:12.500  3217  6594 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-16 17:58:12.500  3217  6594 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0,
08-16 17:58:12.500  3217  6594 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-16 17:58:12.500  6602  6602 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:58:12.500  1015  1543 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6602 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-16 17:58:12.510  6602  6602 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.520  1015  3204 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.540  6602  6602 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.540  6602  6602 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.560  6498  6498 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 17:58:12.560  6498  6498 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 17:58:12.580  5915  5926 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-16 17:58:12.600  5915  5926 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-16 17:58:12.600  5915  5926 D BadgeProvider: sendNotify, [notify] : null
08-16 17:58:12.600  5915  5926 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-16 17:58:12.600  5915  5926 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 17:58:12.600  5915  5926 D BadgeProvider: update, [UpdateCount] : 1
,08-16 17:58:12.600  1478  1478 D Launcher.Model: reloadBadges entered.
,08-16 17:58:12.600  1015  3202 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.610  6498  6498 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-16 17:58:12.610  6602  6620 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-16 17:58:12.610  6602  6620 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-16 17:58:12.620  6602  6602 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-16 17:58:12.630  1015  3202 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-16 17:58:12.630  1015  3202 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.630  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.630  1015  3202 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-16 17:58:12.630  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-16 17:58:12.630  1015  1543 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.640  6001  6001 I SA      : [DM] init START
,08-16 17:58:12.640  6602  6620 D SPPClientService: PushLog.txt file is not deleted.
08-16 17:58:12.640  6602  6620 D SPPClientService: PushLog.txt file is not deleted.
08-16 17:58:12.640  6602  6620 D SPPClientService: ============PushLog. stop!
,08-16 17:58:12.640  6001  6001 I SA      : [DM] This device is not a Vodafone
,08-16 17:58:12.650  1015  1138 D RCPManagerService: exchangeData() failure , invalid userId
,08-16 17:58:12.650  6602  6623 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-16 17:58:12.660  6001  6001 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-16 17:58:12.670  1015  3200 D RCPManagerService: exchangeData() failure , invalid userId
08-16 17:58:12.670  1015  1042 D Tethering: interfaceRemoved wlan0
08-16 17:58:12.670  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
08-16 17:58:12.670  6001  6001 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-16 17:58:12.670  6001  6001 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
08-16 17:58:12.680  6001  6001 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-16 17:58:12.690  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:12.690  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:12.690  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:12.690  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:12.690  1015  1545 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-16 17:58:12.690  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.690  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.690  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.690  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.700  6001  6001 I SA      : [SCU] isHaveSA() - false
,08-16 17:58:12.700  6001  6001 I SA      : support phone number id : false
,08-16 17:58:12.700  6001  6001 I SA      : [DM] Supports Ref Jpn : true
,08-16 17:58:12.700  6001  6001 I SA      : [DM] init END
,08-16 17:58:12.700  6001  6001 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-16 17:58:12.700  6001  6001 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-16 17:58:12.700  6001  6001 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-16 17:58:12.710  6001  6001 I SA      : [SLFUCHKMGR] constructor called
,08-16 17:58:12.720  6628  6628 E Zygote  : MountEmulatedStorage()
08-16 17:58:12.720  6628  6628 E Zygote  : v2
08-16 17:58:12.720  6628  6628 I libpersona: KNOX_SDCARD checking this for 10159
08-16 17:58:12.720  6628  6628 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:12.720  6628  6628 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.720  6628  6628 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:12.720  1015  1545 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6628 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:58:12.720  6628  6628 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.740  6498  6498 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-16 17:58:12.740  6498  6498 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15e8404b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-16 17:58:12.740  6498  6498 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 17:58:12.740  6498  6498 D AndroidMusic: GMSCore installation verified
,08-16 17:58:12.750  6001  6001 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-16 17:58:12.750  6001  6001 I SA      : [OR] == isSIMCardReady false ==
,08-16 17:58:12.760  6001  6001 I SA      : [SCU] == networkStateCheck == false
,08-16 17:58:12.760  6001  6001 I SA      : [OR] onReceive END
,08-16 17:58:12.760  6628  6628 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.760  1015  1138 I ActivityManager: Killing 5838:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-16 17:58:12.760  1015  3202 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:12.760  6628  6628 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.760  1015  3202 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:12.760  1015  3202 D SecContentProvider2: mCursor = null
,08-16 17:58:12.760  1015  3202 D WifiService: setWifiEnabled: true pid=6176, uid=10155
08-16 17:58:12.760  1015  3202 W ActivityManager: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:12.760  1015  3202 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:12.760  1015  3202 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:12.760  1015  3202 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:58:12.760  1015  3202 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:12.760  1015  3202 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:12.760  1015  3202 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:12.760  1015  3202 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:12.760  1015  3202 D SettingsProvider: name = wifi_on
,08-16 17:58:12.770  1229  1229 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:12.780  6498  6511 W art     : Suspending all threads took: 5.096ms
,08-16 17:58:12.780  1015  1544 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:12.780  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-16 17:58:12.790  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.790  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:12.790  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:12.800  1015  1353 I art     : Explicit concurrent mark sweep GC freed 53275(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 3.155ms total 190.966ms
,08-16 17:58:12.800  6498  6498 I ConfigStore: Config Database version: 1
,08-16 17:58:12.810  1015  1042 D Tethering: interfaceRemoved p2p0
,08-16 17:58:12.810  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:58:12.820  1015  1353 I ActivityManager: Killing 5518:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-16 17:58:12.850  1015  1384 I ActivityManager: Killing 5891:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,08-16 17:58:12.860  1015  1353 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:12.860  1015  1353 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.860  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:12.860  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:12.860  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:12.870  3789  3789 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:58:12.880  3789  4552 I iu.UploadsManager: num queued entries: 0
,08-16 17:58:12.880  3789  4552 I iu.UploadsManager: num updated entries: 0
,08-16 17:58:12.880  3789  4552 I iu.SyncManager: NEXT; no task
,08-16 17:58:12.880  1015  1543 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:12.880  1015  1543 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.networkstatereceiver.NetworkStateReceiver}
08-16 17:58:12.880  1015  1543 W BroadcastQueue: android.os.TransactionTooLargeException
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-16 17:58:12.880  1015  1543 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:12.880  1015  1543 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-16 17:58:12.880  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.890  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.890  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:12.890  1015  1543 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:12.900   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
,08-16 17:58:12.900   257   516 W Vold    : Returning OperationFailed - no handler for errno 0,
08-16 17:58:12.900  6584  6648 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:58:12.910   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:58:12.910   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:12.910  6584  6648 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-16 17:58:12.910  6653  6653 E Zygote  : MountEmulatedStorage(),
,08-16 17:58:12.910  6653  6653 E Zygote  : v2
,08-16 17:58:12.910  6653  6653 I libpersona: KNOX_SDCARD checking this for 10010
08-16 17:58:12.910  6653  6653 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:12.920  1015  1543 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=6653 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 17:58:12.920  6653  6653 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:12.920  6653  6653 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:12.920  6653  6653 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-16 17:58:12.940   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:58:12.940   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:12.940  6498  6498 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:58:12.940  1015  1039 W libprocessgroup: failed to open /acct/uid_10010/pid_5891/cgroup.procs: No such file or directory
,08-16 17:58:12.950   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:58:12.950   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:12.950  6498  6498 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:58:12.950  6653  6653 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:12.950  6653  6653 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:12.950   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-16 17:58:12.950   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:12.950   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-16 17:58:12.950   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 17:58:12.950  6584  6662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-16 17:58:12.960  6498  6498 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-16 17:58:12.960   257   516 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-16 17:58:12.960   257   516 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 17:58:12.960  6584  6662 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
08-16 17:58:12.960  1015  1544 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-16 17:58:12.960  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-16 17:58:12.960  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:12.960  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.960  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:12.980  1015  3204 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:12.980  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-16 17:58:12.980  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:12.980  1015  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:12.980  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:13.010  1015  3202 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-16 17:58:13.010  1015  3202 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-16 17:58:13.010  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-16 17:58:13.010  1015  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-16 17:58:13.010  1015  3200 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:13.020  1015  1027 I ActivityManager: Killing 5753:com.android.mms/u0a46 (adj 15): empty #31
,08-16 17:58:13.020  1015  1542 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:13.030  1015  1250 I AudioService: getStreamVolume 3 index 0
,08-16 17:58:13.030  6498  6498 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-16 17:58:13.040  6498  6498 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-16 17:58:13.060  1015  3201 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:13.060  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:58:13.060  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.060  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:13.060  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:13.060  1015  1543 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:13.060  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 17:58:13.060  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.060  1015  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:13.060  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:13.060  1015  1544 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:13.070  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-16 17:58:13.070  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.070  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:13.070  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:13.070  1015  1545 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:13.080  1015  1353 D CountryDetector: No listener is left
,08-16 17:58:13.090  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-16 17:58:13.090  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.090  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.090  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.090  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.100  6688  6688 E Zygote  : MountEmulatedStorage()
,08-16 17:58:13.100  6688  6688 E Zygote  : v2
08-16 17:58:13.100  6688  6688 I libpersona: KNOX_SDCARD checking this for 10002
08-16 17:58:13.100  6688  6688 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:13.100  6688  6688 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:13.100  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6688 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 17:58:13.110  6688  6688 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:13.110  6584  6584 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-16 17:58:13.110  6688  6688 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:13.110  1015  3202 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:13.110  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:13.110  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:13.110  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 17:58:13.130  6584  6584 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8579-8580)
,08-16 17:58:13.130  6584  6584 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:58:13.130  6688  6688 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:13.130  6688  6688 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:13.130  1015  1138 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-16 17:58:13.130  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-16 17:58:13.130  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.130  1015  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:13.130  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 17:58:13.140  6584  6584 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16285640}
,08-16 17:58:13.140  6584  6584 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:58:13.140  6584  6584 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:58:13.140  6498  6498 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-16 17:58:13.140  1015  1542 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:13.140  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:58:13.140  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:13.140  1015  1542 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:13.140  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:13.160  6584  6584 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:58:13.160  6584  6584 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 17:58:13.160  6584  6584 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:58:13.170  1015  1353 I ActivityManager: Killing 5931:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-16 17:58:13.180  6584  6584 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-16 17:58:13.180  6584  6584 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-16 17:58:13.180  6584  6584 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-16 17:58:13.190  6584  6584 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-16 17:58:13.190  6584  6584 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-16 17:58:13.190  6584  6584 I Adreno-EGL: Build Date: 04/06/15 Mon
08-16 17:58:13.190  6584  6584 I Adreno-EGL: Local Branch: 
08-16 17:58:13.190  6584  6584 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-16 17:58:13.190  6584  6584 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-16 17:58:13.190  6584  6584 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-16 17:58:13.190  1015  1028 I ActivityManager: Killing 5955:com.wsomacp/u0a25 (adj 15): empty #31
,08-16 17:58:13.200  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-16 17:58:13.200  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.200  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.200  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.200  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.210  6712  6712 E Zygote  : MountEmulatedStorage(),
,08-16 17:58:13.210  6712  6712 E Zygote  : v2,
08-16 17:58:13.210  6712  6712 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:13.210  6712  6712 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:13.210  6712  6712 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:13.210  1015  1028 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-16 17:58:13.210  6712  6712 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:13.210  6712  6712 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:13.230  6712  6712 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:13.230  6712  6712 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:13.270  6584  6734 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 17:58:13.270  6712  6712 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-16 17:58:13.280  6584  6584 I NSApplication: Starting up...
,08-16 17:58:13.290  1015  1545 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-16 17:58:13.290  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.290  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.290  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.290  1015  1545 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.300  1015  1545 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6739 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 17:58:13.300  6739  6739 E Zygote  : MountEmulatedStorage()
08-16 17:58:13.300  6739  6739 I libpersona: KNOX_SDCARD checking this for 10120
08-16 17:58:13.300  6739  6739 E Zygote  : v2
08-16 17:58:13.300  6739  6739 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:13.300  6739  6739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:13.310  6739  6739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:13.310  1015  1545 I ActivityManager: Killing 5974:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
08-16 17:58:13.310  1015  1545 I ActivityManager: Killing 5806:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #32
,08-16 17:58:13.310  6739  6739 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-16 17:58:13.330  6739  6739 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:13.330  6739  6739 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:13.350  6739  6739 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:58:13.360   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-16 17:58:13.400  6712  6712 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-16 17:58:13.410  6712  6712 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-16 17:58:13.410  6712  6712 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:13.410  6712  6712 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-16 17:58:13.410  6712  6712 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-16 17:58:13.410  6712  6712 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-16 17:58:13.420  1015  1353 I ActivityManager: Killing 5856:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-16 17:58:13.490  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:58:13.490  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-16 17:58:13.650  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-16 17:58:13.650  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.650  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.650  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:13.650  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:13.670  6760  6760 E Zygote  : MountEmulatedStorage(),
08-16 17:58:13.670  6760  6760 E Zygote  : v2
08-16 17:58:13.670  6760  6760 I libpersona: KNOX_SDCARD checking this for 10125,
08-16 17:58:13.670  6760  6760 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:13.670  6760  6760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-16 17:58:13.670  6760  6760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:58:13.670  6760  6760 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:13.680  1015  1028 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6760 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-16 17:58:13.680  1015  1028 I ActivityManager: Killing 6036:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,08-16 17:58:13.700  6760  6760 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:13.700  6760  6760 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:13.710  6760  6760 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 17:58:13.710  6760  6760 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-16 17:58:13.720  6760  6760 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:58:13.730  6760  6760 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:13.730  6760  6760 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-16 17:58:13.730  6760  6760 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-16 17:58:13.730  1015  1353 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-16 17:58:13.740  1015  1353 I ActivityManager: Killing 6058:com.samsung.helphub/1000 (adj 15): empty #31
,08-16 17:58:13.740  1015  3204 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:13.740  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:13.740  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:13.740  1015  3204 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:13.740  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:13.740  3588  3588 I Hs20UtilService: Starting #11
,08-16 17:58:13.740  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:13.750  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:13.750  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:13.750  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:13.750  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:13.860  1015  1042 D Tethering: interfaceAdded wlan0
,08-16 17:58:13.870  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-16 17:58:13.870  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:13.870  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:13.870  1015  1129 E Tethering: No numeric data
,08-16 17:58:13.870  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:58:13.870  1015  1129 D Tethering: clearTetheredNotification()
,08-16 17:58:13.880  1015  1129 D Tethering: InitialState.processMessage what=4,
,08-16 17:58:13.880  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
,08-16 17:58:13.880  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-16 17:58:13.880  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:13.880  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:13.880  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.880  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:13.880  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:13.880  1174  1174 D HotspotTile: updateTetherState():false, false
08-16 17:58:13.880  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:13.890  1015  1129 E Tethering: No numeric data
,08-16 17:58:13.890  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 17:58:13.890  1015  1042 D Tethering: interfaceAdded p2p0
08-16 17:58:13.890  1015  1123 V NetworkStats: performPollLocked() took 8ms
08-16 17:58:13.890  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.890  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-16 17:58:13.890  1015  1129 D Tethering: clearTetheredNotification(),
,08-16 17:58:13.900   278   995 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-16 17:58:13.900   278   995 D SoftapController: Softap fwReload - Ok
08-16 17:58:13.900  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:13.900  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 17:58:13.900   278   995 D CommandListener: Setting iface cfg
08-16 17:58:13.900   278   995 D CommandListener: Trying to bring down wlan0
,08-16 17:58:13.900   278   995 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:13.900  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:13.900  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.910  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.910  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.910  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:13.910  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:13.910  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-16 17:58:13.910  1015  1123 V NetworkStats: performPollLocked() took 8ms
08-16 17:58:13.910  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:13.920  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:13.920  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:13.920  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-16 17:58:13.930  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:13.930  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:13.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.930  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:13.930  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:13.930  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:13.930  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:13.930  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-16 17:58:13.930  1174  1174 D HotspotTile: onReceive : 2, 0
,08-16 17:58:13.930  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-16 17:58:13.930  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:13.940  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:13.940  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:13.940  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:13.940  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:13.940  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:13.940  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:13.950  3588  3588 I Hs20UtilService: Starting #12
,08-16 17:58:13.950  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:13.950  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:13.950  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:13.950  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:13.950  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:13.970  6782  6782 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-16 17:58:13.970  6782  6782 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 17:58:13.970  6782  6782 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:58:13.980  6782  6782 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-16 17:58:13.990   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6782
08-16 17:58:13.990   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-16 17:58:13.990  6782  6782 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:58:13.990  6782  6782 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:13.990  6782  6782 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-16 17:58:13.990  6782  6782 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-16 17:58:13.990   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6782,
08-16 17:58:13.990   386   386 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-16 17:58:14.150   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-16 17:58:14.150  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-16 17:58:14.220  6782  6782 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-16 17:58:14.220  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:58:14.230  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-16 17:58:14.230   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6782
08-16 17:58:14.230   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 17:58:14.230  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:58:14.230  6782  6782 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:14.230  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:58:14.230  6782  6782 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:58:14.230  6782  6782 E wpa_supplicant: SIM READ ERROR
08-16 17:58:14.230  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:14.230  6782  6782 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:14.230  6782  6782 E wpa_supplicant: SIM READ ERROR
08-16 17:58:14.230  6782  6782 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:58:14.230  6782  6782 I wpa_supplicant: wpa_default_ap_write_once,
08-16 17:58:14.230  6782  6782 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:14.230  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:14.230  6782  6782 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:58:14.230  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:14.230  6782  6782 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-16 17:58:14.240  6782  6782 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-16 17:58:14.240  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:14.240  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:14.240  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:14.330  6782  6782 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 17:58:14.590  6782  6782 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:58:14.590  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-16 17:58:14.600  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:58:14.610   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6782
08-16 17:58:14.610   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-16 17:58:14.610  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-16 17:58:14.610  6782  6782 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:14.610  6782  6782 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-16 17:58:14.610  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-16 17:58:14.620  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-16 17:58:14.620   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6782
08-16 17:58:14.620   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-16 17:58:14.620  6782  6782 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-16 17:58:14.620  6782  6782 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:14.620  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-16 17:58:14.620  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:14.620  6782  6782 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:14.630  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:14.620  6782  6782 E wpa_supplicant: SIM READ ERROR
08-16 17:58:14.620  6782  6782 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:14.620  6782  6782 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:14.620  6782  6782 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:58:14.620  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:14.620  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-16 17:58:14.630  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:14.630  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:14.670  6782  6782 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:58:14.670  6782  6782 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:58:14.810  6782  6782 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-16 17:58:14.810  6782  6782 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:58:14.810  6782  6782 I wpa_supplicant: Skip scan - bUseNetwork false
,08-16 17:58:14.820  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
08-16 17:58:14.820  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:58:14.820  6782  6782 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 17:58:14.820  6782  6782 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:58:14.820  6782  6782 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 17:58:14.830  6782  6782 E wpa_supplicant: SIM READ ERROR
08-16 17:58:14.830  6782  6782 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:14.850  6782  6782 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 17:58:14.860  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:58:14.860  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:14.860  1015  1042 D Tethering: interfaceStatusChanged p2p0, false,
,08-16 17:58:14.870  6782  6782 I wpa_supplicant: Skip scan - bUseNetwork false,
08-16 17:58:14.870  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 17:58:14.870  1015  1126 D WifiConfigStore: Loading config and enabling all networks ,
,08-16 17:58:14.880  1015  1126 E WifiConfigStore: Not a HS20
,08-16 17:58:14.880  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 17:58:14.890  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:14.890  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:14.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:14.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:14.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:14.890  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:14.890  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:14.890  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 17:58:14.890  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-16 17:58:14.890  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:14.890  1174  1174 D HotspotTile: onReceive : 3, 0
,08-16 17:58:14.890  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-16 17:58:14.890  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:14.890  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:14.890  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:14.890  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:14.900  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 17:58:14.900  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:14.900  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:14.900  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:14.900  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:14.900  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-16 17:58:14.900  6782  6782 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:58:14.900  6782  6782 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:58:14.900  6782  6782 I wpa_supplicant: reset timer : RESET_TIMER 0
08-16 17:58:14.900  6782  6782 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:14.900  6782  6782 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-16 17:58:14.900  6782  6782 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:58:14.900  6782  6782 I wpa_supplicant: First Scan Start
,08-16 17:58:14.900  6782  6782 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-16 17:58:14.900  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-16 17:58:14.900  1015  1138 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:14.900  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:58:14.900  1015  1138 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:14.900  1015  1126 I WifiNative-HAL: startHal
08-16 17:58:14.900  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9c8ef88c
08-16 17:58:14.900  1015  1126 I WifiNative-HAL: Could not start hal
,08-16 17:58:14.900  1015  1138 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:14.900  1015  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:14.900  1015  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:14.900  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:14.910  1015  1126 E WifiNative-wlan0: do suspend true
,08-16 17:58:14.910  3588  3588 I Hs20UtilService: Starting #13
,08-16 17:58:14.910  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 17:58:14.910  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-16 17:58:14.910  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:58:14.910  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:14.910  1015  1149 I WifiNative-HAL: startHal
08-16 17:58:14.910  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9daa19bc
08-16 17:58:14.910  1015  1149 I WifiNative-HAL: Could not start hal
08-16 17:58:14.910  1015  1149 E WifiScanningService: could not start HAL
,08-16 17:58:14.910  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-16 17:58:14.910  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:14.910   278   995 D CommandListener: Setting iface cfg
08-16 17:58:14.910   278   995 D CommandListener: Trying to bring up p2p0
08-16 17:58:14.910  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:58:14.920  1015  1125 D WifiP2pService: P2pEnablingState
,08-16 17:58:14.920  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:58:14.920  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:14.920  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:14.920  1015  1126 E WifiNative-wlan0: invaild command id : 215
,08-16 17:58:14.920  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:14.920  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-16 17:58:14.920  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:14.920  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:14.920  1015  1125 D WifiP2pService: P2p socket connection successful
08-16 17:58:14.920  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-16 17:58:14.920  6782  6782 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:58:14.920  1015  1125 D WifiP2pService: P2pEnabledState
08-16 17:58:14.920  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:58:14.920  1015  1128 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:14.920  6782  6782 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-16 17:58:14.920  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:58:14.920  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:58:14.920  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:14.920  1015  1045 D WifiDisplayController: disconnect
08-16 17:58:14.920  1015  1045 D WifiDisplayController: updateConnection
08-16 17:58:14.920  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:14.920  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:14.930  6782  6782 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-16 17:58:14.930  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:14.930  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:14.930  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:14.930  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:14.930  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:14.940  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:58:14.940  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:14.940  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:14.940  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-16 17:58:14.940  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:14.940  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:14.940  1015  1126 E WifiNative-wlan0: invaild command id : 215
08-16 17:58:14.940  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:14.940  1015  1126 D SecContentProvider2: mCursor = null
08-16 17:58:14.940  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-16 17:58:14.940  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-16 17:58:14.940  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 17:58:14.950  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:58:14.950  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  secondary type: null
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  wps: 0
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  grpcapab: 0
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  devcapab: 0
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  status: 3
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  wfdInfo: null
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-16 17:58:14.950  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-16 17:58:14.950  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:14.950  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:14.950  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:14.950  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:14.950  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:14.950  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:14.950  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:14.950  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-16 17:58:14.950  6417  6417 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:14.960  6432  6432 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:14.970  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:58:14.970  1015  1125 D WifiP2pService: InactiveState
,08-16 17:58:14.970  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:58:14.970  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:14.970  6782  6782 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-16 17:58:14.970  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:58:14.970  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:15.030  1015  1093 V AlarmManager: waitForAlarm result :4
,08-16 17:58:15.040   278   991 D EnterpriseController: uids 10012
08-16 17:58:15.040   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:15.040   278   991 D Netd    : getNetworkForDns: using netid 0 for uid 10012
,08-16 17:58:15.050  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.050  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:15.050  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-16 17:58:15.340   288   288 E SMD     : DCD OFF
,08-16 17:58:15.690  1015  1543 I ActivityManager: Killing 5440:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-16 17:58:15.770  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:15.770  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:15.770  1015  1027 D SecContentProvider2: mCursor = null
,08-16 17:58:15.780  1015  1027 D WifiService: setWifiEnabled: false pid=6176, uid=10155
08-16 17:58:15.780  1015  1027 D SettingsProvider: name = wifi_on
,08-16 17:58:15.790  1015  1125 D WifiP2pService: InactiveState{ what=131204 },
08-16 17:58:15.790  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 17:58:15.790  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-16 17:58:15.790  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler },
,08-16 17:58:15.790  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-16 17:58:15.790  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.790  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-16 17:58:15.790  1015  1150 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler },
,08-16 17:58:15.800  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-16 17:58:15.800  1015  1125 D WifiP2pService: P2pDisablingState,
08-16 17:58:15.800  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 17:58:15.800  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-16 17:58:15.800  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:15.800  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 17:58:15.800  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:15.800  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:15.800  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:15.800   278   995 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:58:15.800  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:15.800  1015  1125 D WifiP2pService: p2p socket connection lost
08-16 17:58:15.800  1015  1125 D WifiP2pService: P2pDisabledState
08-16 17:58:15.810  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-16 17:58:15.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-16 17:58:15.810  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-16 17:58:15.810  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:15.810  1015  1045 D WifiDisplayController: disconnect
08-16 17:58:15.810  1015  1045 D WifiDisplayController: updateConnection
08-16 17:58:15.810  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:15.810  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:15.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:15.810  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 17:58:15.810  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:15.810  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-16 17:58:15.810  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:15.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.810  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:15.810  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:15.810  1015  3201 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:15.810  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:15.810  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.820  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-16 17:58:15.820  6782  6782 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-16 17:58:15.820  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:15.820  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:15.820  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.820  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.820  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.820  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:15.830  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.830  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:15.830  6417  6417 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:15.830  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:15.830  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:15.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:15.830  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:15.830  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-16 17:58:15.840  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:15.840  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:15.840  1174  1174 D HotspotTile: onReceive : 0, 0
,08-16 17:58:15.840  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:15.840  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:15.840  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.840  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:15.840  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:15.840  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:15.840  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:15.840  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:15.850  6432  6432 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.850  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:15.850  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:15.850  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:15.850  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:15.850  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.850  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-16 17:58:15.850  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.860  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.860  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:15.860  6417  6417 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:15.860  6432  6432 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:15.870  1015  1384 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:15.870  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:15.870  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.870  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.870  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:15.870  3588  3588 I Hs20UtilService: Starting #14
,08-16 17:58:15.880  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:15.880  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-16 17:58:15.880  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:15.880  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:15.880  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:15.880  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-16 17:58:15.880  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:15.880  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:15.890  1015  1542 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:15.890  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:15.890  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:15.890  1015  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:15.890  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:15.890  3588  3588 I Hs20UtilService: Starting #15
,08-16 17:58:15.890  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:15.890  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:15.890  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:15.890  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:15.890  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:15.930  6782  6782 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:16.030  6782  6782 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-16 17:58:16.030  6782  6782 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
08-16 17:58:16.030  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:16.030  6782  6782 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-16 17:58:16.030  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:16.030  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:16.420  6782  6782 I wpa_supplicant: Blacklist: Clear (all) ,
,08-16 17:58:16.500  6782  6782 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-16 17:58:16.500  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:16.500  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-16 17:58:16.510  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:16.610  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-16 17:58:16.610  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-16 17:58:16.610  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:58:16.620  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:16.620  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:16.620  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:16.620  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.620  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.620  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.620  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:16.620  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:16.620  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:16.620  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-16 17:58:16.620  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:16.620  1174  1174 D HotspotTile: onReceive : 1, 0
,08-16 17:58:16.620  1935  2125 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:16.630  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:16.630  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:16.630  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:16.630  1015  3201 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:16.630  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:16.630  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:16.630  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:16.630  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:16.640  3588  3588 I Hs20UtilService: Starting #16
,08-16 17:58:16.640  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:16.640  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:16.640  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:16.640  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
,08-16 17:58:16.640  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:17.370  1015  1042 D Tethering: interfaceRemoved wlan0
,08-16 17:58:17.370  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-16 17:58:17.540  1015  1042 D Tethering: interfaceRemoved p2p0
,08-16 17:58:17.540  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-16 17:58:17.900  1015  3201 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-16 17:58:17.900  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-16 17:58:17.900  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:17.900  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:17.900  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-16 17:58:17.910  6584  6650 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 17:58:18.020  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.020  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.020  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.020  1015  1384 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-16 17:58:18.020  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.020  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.020  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:18.020  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.030  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.030  1015  1545 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.030  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.040  1015  1353 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:18.040  1015  1353 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.040  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.040  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:18.040  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.050  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:18.050  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.050  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.050  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:18.050  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.050  1015  1544 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:18.050  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:58:18.050  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.050  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:18.050  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.070  1015  1384 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-16 17:58:18.070  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.070  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:18.070  1015  1384 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.070  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.100  1015  3202 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:18.100  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.100  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.100  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-16 17:58:18.110  1935  1935 D WearableService: callingUid 10012, callindPid: 1935
,08-16 17:58:18.130  1015  3204 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-16 17:58:18.130  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-16 17:58:18.140  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.140  1015  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.140  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-16 17:58:18.170  6498  6798 I MusicLeanback: Conditions not met for autocaching.
08-16 17:58:18.170  6498  6798 I MusicLeanback: Stop autocaching.
,08-16 17:58:18.170  6498  6498 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 17:58:18.180  6498  6803 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-16 17:58:18.240  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-16 17:58:18.340   288   288 E SMD     : DCD OFF
,08-16 17:58:18.790  6176  6229 D BluetoothAdapter: enable()
,08-16 17:58:18.790  1015  3202 W ActivityManager: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:18.800  1015  3202 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 17:58:18.800  1015  3202 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:18.800  1015  3202 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.800  1015  3202 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.800  1015  3202 D SettingsProvider: name = bluetooth_on,
,08-16 17:58:18.810  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.810  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.810  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-16 17:58:18.810  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-16 17:58:18.850  6369  6369 D BluetoothAdapterState: make
,08-16 17:58:18.860  6369  6369 I bluedroid: init
,08-16 17:58:18.870  6369  6805 I BluetoothAdapterState: Entering OffState
,08-16 17:58:18.870  6369  6369 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:58:18.870  6369  6369 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:58:18.870  6369  6369 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 17:58:18.870  6369  6369 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:58:18.870  6369  6369 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:58:18.870  6369  6369 I bluedroid: get_profile_interface socket
08-16 17:58:18.870  6369  6369 I bluedroid: get_profile_interface map_client
08-16 17:58:18.870  6369  6808 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:58:18.880  6369  6369 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:58:18.880  6369  6808 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:58:18.880  6369  6808 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:58:18.880  6369  6808 I bluedroid: getModelRssiValues
08-16 17:58:18.880  6369  6808 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-16 17:58:18.880  6369  6808 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:18.880  6369  6369 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:18.880  6369  6808 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:58:18.890  1015  1015 D SettingsProvider: name = bluetooth_name
08-16 17:58:18.890  1015  3089 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:18.890  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.890  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.890  1015  3089 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.890  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.890  6369  6378 I bluedroid: config_hci_snoop_log
,08-16 17:58:18.890  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 17:58:18.900  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:58:18.900  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-16 17:58:18.900  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:58:18.900  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:18.900  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.900  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:18.910  6369  6369 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:58:18.910  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:58:18.910  6369  6805 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-16 17:58:18.910  6369  6805 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:58:18.910  6369  6805 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 17:58:18.910  6369  6805 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:18.910  6369  6805 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:58:18.910  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:18.920  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
08-16 17:58:18.920  6369  6805 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:18.920  6369  6805 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:58:18.920  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:18.930  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:18.930  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-16 17:58:18.930  6369  6805 D BluetoothSecureManager: getInstant: null
,08-16 17:58:18.930  6369  6805 D BluetoothSecureManager: calling getMethod for getService
08-16 17:58:18.930  6369  6805 D BluetoothSecureManager: calling getService
,08-16 17:58:18.930  1779  1779 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 17:58:18.930  6369  6805 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@d43b27b
,08-16 17:58:18.930  1015  1354 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 17:58:18.930  1015  1354 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:58:18.930  6369  6805 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:58:18.930  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
08-16 17:58:18.930  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:18.930  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:18.930  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.930  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService,
08-16 17:58:18.930  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:18.930  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:58:18.930  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 17:58:18.930  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:18.940  1015  3089 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:58:18.940  1015  1138 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:18.940  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:18.940  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:18.940  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,08-16 17:58:18.940  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-16 17:58:18.940  6369  6805 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-16 17:58:18.950  6369  6805 D BluetoothBondStateMachine: make
,08-16 17:58:18.950  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:18.950  1015  1544 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:18.950  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-16 17:58:18.950  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:58:18.950  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.950  1015  1544 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:18.950  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-16 17:58:18.950  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:58:18.950  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:58:18.950  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:58:18.950  6369  6809 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:58:18.960  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:18.960  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:58:18.960  1015  1354 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:18.960  1015  1354 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.960  1015  1354 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.960  1015  1354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.960  1015  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.960  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:18.970  6369  6369 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:58:18.970  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:18.970  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:18.970  6369  6369 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:58:18.970  6369  6369 D BtGatt.GattService: start()
08-16 17:58:18.970  6369  6369 D BtGatt.GattService: start()
08-16 17:58:18.970  6369  6369 I bluedroid: get_profile_interface gatt
,08-16 17:58:18.970  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:18.970  6369  6369 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:58:18.980  1015  1542 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.980  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.980  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.980  1015  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:18.980  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:18.980  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:18.980  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:18.980  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:18.980  1015  3201 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:18.990  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:18.990  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:18.990  6369  6369 D BtGatt.GattService: mStartError = false
08-16 17:58:18.990  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:18.990  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:18.990  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:18.990  6369  6369 D HeadsetService: Received start request. Starting profile...
,08-16 17:58:18.990  6369  6369 D HeadsetService: start()
,08-16 17:58:18.990  6369  6369 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:58:18.990  6369  6369 D HeadsetStateMachine: make
,08-16 17:58:18.990  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:18.990  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:18.990  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:19.000  6369  6369 E HeadsetStateMachine: # of Max HF connection is 2
,08-16 17:58:19.000  1015  3204 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:19.000  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.000  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.000  1015  3204 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.000  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.000  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-16 17:58:19.000  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:19.000  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:19.010  1015  1543 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-16 17:58:19.010  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.010  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.010  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:19.010  1015  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.010  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:19.010  1015  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:19.010  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.010  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.010  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.010  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.020  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:19.020  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:19.020  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:19.020  1015  1384 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 17:58:19.020  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.020  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-16 17:58:19.020  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.020  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.020  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:19.020  6369  6369 I bluedroid: get_profile_interface handsfree
,08-16 17:58:19.030  1015  3200 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:19.030  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.030  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.030  1015  3200 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.030  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.040  6369  6369 I DualScoManager: Instantiating Dual Sco Manager
,08-16 17:58:19.040  6369  6369 I DualScoManager: Set HeadsetServiceHelper
,08-16 17:58:19.040  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:19.040  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:19.040  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-16 17:58:19.040  1015  1354 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:19.040  6369  6369 D BluetoothAtMessage: createCMTIContentObservers
08-16 17:58:19.040  1015  1354 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.040  1015  3089 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-16 17:58:19.040  1015  3089 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:19.040  1015  1354 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.040  1015  1354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.040  1015  1354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.040  1015  3089 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:19.040  1015  3089 D SettingsProvider: selectionArgs: false
08-16 17:58:19.040  1015  3089 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:19.040  1015  3089 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:19.050  1015  3089 D SettingsProvider: ret = -1
,08-16 17:58:19.050  6369  6813 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:58:19.050  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-16 17:58:19.050  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:19.050  6369  6805 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:19.050  6369  6813 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-16 17:58:19.050  6369  6813 D HeadsetStateMachine: map size, before remove : 0
,08-16 17:58:19.050  6369  6813 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:58:19.050  6369  6369 D HeadsetService: mStartError = false
08-16 17:58:19.050  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.050  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:19.050  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.050  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.050  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:19.050  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:19.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:19.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:19.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:19.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:19.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:19.060  6369  6805 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:58:19.060  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:58:19.060  6369  6369 D A2dpService: Received start request. Starting profile...
08-16 17:58:19.060  6369  6369 D A2dpService: start()
08-16 17:58:19.060  6369  6369 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:58:19.060  6369  6369 I bluedroid: get_profile_interface avrcp
,08-16 17:58:19.070  6369  6369 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,08-16 17:58:19.080  6369  6369 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:58:19.080  6369  6817 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,08-16 17:58:19.080  6369  6369 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:58:19.080  6369  6369 D A2dpStateMachine: make
,08-16 17:58:19.090  6369  6369 I bluedroid: get_profile_interface a2dp
,08-16 17:58:19.090  6369  6819 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 17:58:19.090  6369  6369 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:58:19.090  6369  6369 D A2dpService: mStartError = false
08-16 17:58:19.090  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.090  6369  6369 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:58:19.090  6369  6369 D HidService: Received start request. Starting profile...
08-16 17:58:19.090  6369  6369 D HidService: start()
08-16 17:58:19.090  6369  6369 I bluedroid: get_profile_interface hidhost
08-16 17:58:19.090  6369  6369 D HidService: setHidService(): set to: null
08-16 17:58:19.090  6369  6369 D HidService: mStartError = false
08-16 17:58:19.090  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:19.090  6369  6818 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:58:19.100  6369  6369 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:58:19.100  1433  1441 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:58:19.100  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:58:19.100  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:19.100  1433  1441 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:58:19.100  6369  6369 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:58:19.100  6369  6369 D HealthService: Received start request. Starting profile...
08-16 17:58:19.100  6369  6369 D HealthService: start()
,08-16 17:58:19.100  6369  6817 D BluetoothMediaBrowser: no now playing list
08-16 17:58:19.100  6369  6817 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-16 17:58:19.100  6369  6369 I bluedroid: get_profile_interface health
,08-16 17:58:19.100  6369  6369 D HealthService: mStartError = false
08-16 17:58:19.100  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.110  6369  6369 D HeadsetStateMachine: Proxy object connected
,08-16 17:58:19.110  6369  6369 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:58:19.110  6369  6813 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:19.110  6369  6369 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:58:19.110  6369  6369 D PanService: Received start request. Starting profile...
,08-16 17:58:19.110  6369  6369 D PanService: start()
,08-16 17:58:19.110  6369  6369 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:58:19.110  6369  6369 I bluedroid: get_profile_interface pan
,08-16 17:58:19.110  6369  6369 D PanService: mStartError = false
,08-16 17:58:19.110  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.110  6369  6369 D HeadsetPhoneState: sendDeviceDataStateChanged
08-16 17:58:19.110  6369  6369 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 17:58:19.110  6369  6813 D HeadsetStateMachine: Disconnected process message: 18
,08-16 17:58:19.120  6369  6369 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:58:19.120  6369  6369 D BluetoothMapService: start()
,08-16 17:58:19.120  6369  6369 D BluetoothMapService: mStartError = false
08-16 17:58:19.120  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.120  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:58:19.120  6369  6369 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:58:19.120  6369  6813 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:58:19.120  6369  6369 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 17:58:19.120  6369  6813 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:58:19.120  6369  6813 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:19.120  6369  6369 D SapService: Received start request. Starting profile...
,08-16 17:58:19.120  6369  6369 D SapService: start()
08-16 17:58:19.120  6369  6369 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:58:19.120  6369  6369 I bluedroid: get_profile_interface sap
08-16 17:58:19.120  6369  6369 D SapService: mStartError = false
08-16 17:58:19.120  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:19.120  6369  6369 D BluetoothA2dp: Proxy object connected
08-16 17:58:19.120  6369  6369 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:58:19.120  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-16 17:58:19.120  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-16 17:58:19.120  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:58:19.120  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-16 17:58:19.150  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:58:19.150  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:58:19.150  6369  6805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 17:58:19.150  6369  6805 I bluedroid: enable
,08-16 17:58:19.150  6369  6805 I bt_hci_bdroid: init
,08-16 17:58:19.150  6369  6824 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 17:58:19.150  6369  6805 I bt_vendor: bt-vendor : init
,08-16 17:58:19.150  6369  6805 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:58:19.150  6369  6805 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-16 17:58:19.150  6369  6805 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 17:58:19.150  6369  6805 D bt_userial_mct: userial_init
,08-16 17:58:19.160  6369  6805 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:58:19.160  6369  6805 I bt_vendor: Starting hciattach daemon
,08-16 17:58:19.160  6369  6805 I bt_vendor: try to set false
,08-16 17:58:19.160  6369  6805 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
,08-16 17:58:19.160  6369  6805 I bt_vendor: Starting hciattach daemon
08-16 17:58:19.160  6369  6805 I bt_vendor: try to set true
,08-16 17:58:19.180  6828  6828 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:58:19.220  6834  6834 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:58:19.230  6835  6835 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:58:19.250  6837  6837 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:58:19.260  6838  6838 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:58:19.270  6839  6839 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:58:19.280  6840  6840 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:58:19.510  6843  6843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 17:58:19.520  6844  6844 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:58:19.570  6369  6805 I bt_vendor: bluetooth satus is on
,08-16 17:58:19.570  6369  6826 D bt_userial_mct: userial_open(port:0)
08-16 17:58:19.570  6369  6826 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:58:19.570  6369  6826 I bt_vendor: Done intiailizing UART,
,08-16 17:58:19.570  6369  6826 I bt_vendor: Done intiailizing UART,
08-16 17:58:19.570  6369  6826 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-16 17:58:19.570  6369  6826 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:58:19.570  6369  6846 D bt_userial_mct: Entering userial_read_thread()
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_AVRC,
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:58:19.580  6369  6824 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-16 17:58:19.680  6369  6824 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:58:19.690  6369  6824 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ec26e9 
,08-16 17:58:19.690  6369  6824 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ec26e9 
,08-16 17:58:19.700  6369  6808 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:58:19.710  6369  6808 E bt-btif : Calling BTA_HhEnable
,08-16 17:58:19.710  6369  6808 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:58:19.710  6369  6808 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:58:19.710  6369  6808 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:58:19.710  6369  6808 I bluedroid: getModelRssiValues
,08-16 17:58:19.710  6369  6808 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:58:19.710  6369  6808 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:19.720  6369  6808 D BluetoothAdapterProperties: Name is: A5-1,
08-16 17:58:19.720  1015  1015 D SettingsProvider: name = bluetooth_name
,08-16 17:58:19.720  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:19.720  6369  6808 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:19.720  6369  6808 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:19.720  6369  6808 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:19.720  6369  6808 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 17:58:19.720  6369  6808 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 17:58:19.720  6369  6808 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 17:58:19.720  6369  6808 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:58:19.720  6369  6808 E bt-btif : btif_sock_init: !vhci_init
,08-16 17:58:19.720  6369  6808 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-16 17:58:19.720  6369  6808 D IOP_DB_BT: db_open: db_open : handle 3027906576l, read 13894 bytes onto local cache
,08-16 17:58:19.720  6369  6808 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:58:19.730  6369  6808 D IOP_DB_BT: db_query: result 1
08-16 17:58:19.730  6369  6808 I         : iop_db_open: iop_db_open status 0
08-16 17:58:19.730  6369  6808 D bte_conf: Device ID record 1 : primary
08-16 17:58:19.730  6369  6808 D bte_conf:   vendorId            = 0075
08-16 17:58:19.730  6369  6808 D bte_conf:   vendorIdSource      = 0001
08-16 17:58:19.730  6369  6808 D bte_conf:   product             = 0100
08-16 17:58:19.730  6369  6808 D bte_conf:   version             = 0200
08-16 17:58:19.730  6369  6808 D bte_conf:   clientExecutableURL = 
08-16 17:58:19.730  6369  6808 D bte_conf:   serviceDescription  = 
08-16 17:58:19.730  6369  6808 D bte_conf:   documentationURL    = 
08-16 17:58:19.730  6369  6808 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:58:19.730  6369  6808 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:58:19.730  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:19.730  6369  6805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:58:19.730  6369  6805 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:58:19.730  6369  6805 D BluetoothAdapterProperties: State =  11
,08-16 17:58:19.730  1015  1138 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:19.730  6369  6805 D BluetoothAdapterProperties: Setting state to 12
08-16 17:58:19.730  6369  6805 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:58:19.730  6369  6846 E bt_mct  : hci lib postload completed
,08-16 17:58:19.740  6369  6808 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:19.740  6369  6808 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:58:19.740  6369  6808 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:19.740  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:19.740  1015  3200 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-16 17:58:19.740  1015  3200 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:19.750  1015  3200 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:19.750  1015  3200 D SettingsProvider: selectionArgs: false
08-16 17:58:19.750  1015  3200 D SettingsProvider: selectionArgs: 1002
08-16 17:58:19.750  1015  3200 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:19.750  1015  3200 D SettingsProvider: ret = -1
,08-16 17:58:19.750  6369  6805 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:58:19.750  6369  6805 D BluetoothAdapterService: updateAdapterState state is 12
,08-16 17:58:19.750  1015  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:19.750  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.750  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.750  1015  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:19.750  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.770  6369  6805 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:58:19.770  6369  6805 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-16 17:58:19.770  6369  6805 D BluetoothAdapterService: starting service from this receiver
,08-16 17:58:19.770  1015  1353 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:19.770  1015  1353 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.770  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.770  1015  1353 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:19.770  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.780  1935  2114 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:19.780  6369  6805 I BluetoothAdapterState: Entering On State from state = 11
08-16 17:58:19.780  1935  2114 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:19.780  1324  1338 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:58:19.780  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:19.790  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-16 17:58:19.790  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.790  6369  6369 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-16 17:58:19.790  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:19.790  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:19.790  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.790  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.790  1174  2709 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:19.790  1174  2709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.800  1324  6361 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.800  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:19.800  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.800  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.800  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.800  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.800  1324  6361 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.800  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:19.800  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.800  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.800  1433  2734 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.800  1433  2734 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:19.800  6369  6369 I BluetoothPbapService: Handler(): got msg=1
,08-16 17:58:19.810  1015  3202 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:19.810  1433  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.810  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:19.810  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.810  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.810  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.810  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.810  1433  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.820  1324  1324 D BluetoothPbap: Proxy object connected
08-16 17:58:19.820  1324  1324 D PbapServerProfile: Bluetooth service connected
,08-16 17:58:19.820  1433  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.820  1324  1324 D HeadsetProfile: Bluetooth service connected
,08-16 17:58:19.820  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:19.820  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.820  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.820  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.820  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.820  1433  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.820  1324  6361 D BluetoothPan: Binding service...
,08-16 17:58:19.820  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:19.820  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.820  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.820  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.820  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.830  2865  2877 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.830  6369  6850 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:58:19.830  2865  2877 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.830  1324  1324 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:58:19.830  1324  1324 D PanProfile: Bluetooth service connected
,08-16 17:58:19.830  1324  1338 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.830  1324  1338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.830  1015  1044 D BluetoothPan: Binding service...
,08-16 17:58:19.830  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:19.830  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.830  6369  6850 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:19.830  6369  6850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:58:19.830  1324  6361 D Bluetoothsap: onBluetoothStateChange: up=true
08-16 17:58:19.830  1324  6361 D Bluetoothsap: Binding service...
08-16 17:58:19.830  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:19.830  1324  6361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:58:19.830  6369  6850 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-16 17:58:19.830  6369  6850 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:19.830  6369  6850 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:19.830  6369  6850 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367fee0e
,08-16 17:58:19.830  6369  6850 D BluetoothSocket: channel: 19
08-16 17:58:19.830  6369  6850 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:58:19.830  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 17:58:19.830  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.840  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.840  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:19.840  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.840  1324  1324 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-16 17:58:19.840  1324  6361 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-16 17:58:19.840  1324  1324 D SapProfile: Bluetooth service connected
08-16 17:58:19.840  1324  1324 D Bluetoothsap: getConnectedDevices()
,08-16 17:58:19.840  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.840  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:19.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:19.840  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.840  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:58:19.840  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.840  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:19.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.840  1433  2734 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.840  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:19.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.840  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.840  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.840  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 17:58:19.840  1433  2734 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.850  1015  1015 D BluetoothA2dp: Proxy object connected
,08-16 17:58:19.850  2865  2875 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.850  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:19.850  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.850  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.850  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.850  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.850  2865  2875 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.850  6369  6378 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:19.850  6369  6378 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:19.850  1457  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.850  1457  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.850  6337  6348 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.850  6337  6348 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:19.850  2865  6851 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:19.860  2865  6851 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.860  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:58:19.860  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.860  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.860  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.860  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.860  2865  2865 D BluetoothA2dp: Proxy object connected
,08-16 17:58:19.860  6369  6646 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:19.860  1324  1338 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:19.860  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 17:58:19.860  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.860  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.860  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.860  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.870  6176  6191 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.870  6176  6191 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.870  1324  1333 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:19.870  1324  1324 D BluetoothInputDevice: Proxy object connected
08-16 17:58:19.870  1324  1324 D HidProfile: Bluetooth service connected
08-16 17:58:19.870  1324  1333 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.870  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:19.870  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.870  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.870  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.870  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.870  1457  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:19.870  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:19.870  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:19.870  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.870  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.870  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.870  1457  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:19.870  1324  1324 D BluetoothA2dp: Proxy object connected
08-16 17:58:19.870  1324  1324 D A2dpProfile: Bluetooth service connected
,08-16 17:58:19.870  1447  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:19.880  1447  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:19.880  1324  6361 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:58:19.880  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-16 17:58:19.880  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.880  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.880  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.880  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.880  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:58:19.880  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:19.880  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:19.880  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-16 17:58:19.880  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:19.890  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:19.890  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@7d95755, true
,08-16 17:58:19.890  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:19.890  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:19.890  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-16 17:58:19.890  1433  1433 D BluetoothHeadset: registerMessageListener
,08-16 17:58:19.900  1015  1384 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:19.900  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-16 17:58:19.900  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:19.900  1779  1779 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:19.900  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:19.900  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:19.900  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:19.900  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:19.900  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:19.910  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null,
,08-16 17:58:19.910  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-16 17:58:19.910  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.910  6369  6378 D HeadsetService: registerMessageListener
,08-16 17:58:19.910  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.910  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:19.910  6369  6378 D HeadsetService: registerMessageListener
08-16 17:58:19.910  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-16 17:58:19.910  6369  6813 D HeadsetStateMachine: Disconnected process message: 70
08-16 17:58:19.910  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-16 17:58:19.910  6369  6813 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1bd4d02f
08-16 17:58:19.910  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:19.920  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-16 17:58:19.920  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-16 17:58:19.920  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:58:19.920  6369  6813 D HeadsetStateMachine: Disconnected process message: 9
,08-16 17:58:19.920  6369  6813 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:58:19.930  6369  6854 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:58:19.930  1324  1324 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-16 17:58:19.930  1324  1324 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:58:19.930  1324  1324 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:58:19.930  1324  1324 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 17:58:19.930   283   683 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-16 17:58:19.930   283   683 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:58:19.930   283   683 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:58:19.930   283   683 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,08-16 17:58:19.930   283   683 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:58:19.930   283   683 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:58:19.930   283   683 V audio_hw_primary: adev_set_parameters: exit
08-16 17:58:19.930  6369  6813 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:58:19.930  6369  6854 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:19.930  6369  6854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:19.930  6369  6854 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-16 17:58:19.930  6369  6854 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:19.930  6369  6854 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:19.930  6369  6854 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2465263c
,08-16 17:58:19.940  6369  6854 D BluetoothSocket: channel: 5
,08-16 17:58:19.940  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:19.940  1015  3201 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-16 17:58:19.940  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.950  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:19.950  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.950  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:19.950  1324  1324 D BluetoothMap: Proxy object connected
08-16 17:58:19.950  1324  1324 D MapProfile: Bluetooth service connected
08-16 17:58:19.950  1324  1324 D BluetoothMap: getConnectedDevices()
,08-16 17:58:19.950  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:19.960  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:19.960  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:19.960  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:58:19.970  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:19.970  6369  6369 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:19.970  1015  1542 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:19.970  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:58:19.970  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:19.970  1015  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:19.970  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:19.990  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:20.000  1015  3201 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:20.000  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:20.000  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:20.000  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:20.000  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:20.000  1015  1543 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:20.010  1935  6863 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:58:20.010  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:20.020  6369  6864 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:58:20.020  6369  6864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:20.020  6369  6864 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-16 17:58:20.020  6369  6864 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:20.020  6369  6864 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:20.020  6369  6864 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7c6a28
08-16 17:58:20.020  6369  6864 D BluetoothSocket: channel: 12
08-16 17:58:20.020  6369  6864 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:20.170  1015  1027 I art     : Explicit concurrent mark sweep GC freed 46335(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.414ms total 154.750ms
08-16 17:58:20.170  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:20.170  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:20.170  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:20.170  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:20.180  1015  3200 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:20.180  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:20.180  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:20.180  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:20.190  1935  6863 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:58:20.710  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:58:20.710  1015  1027 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4201, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
08-16 17:58:20.710  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0,
08-16 17:58:20.710  1015  1027 D BatteryService: stay LED for charging
,08-16 17:58:20.710  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:58:20.710  1015  1015 I MotionRecognitionService: Plugged
08-16 17:58:20.710  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:58:20.720  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,08-16 17:58:20.720  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:20.720  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
,08-16 17:58:20.720  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-16 17:58:20.740  6369  6369 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-16 17:58:20.740  6369  6813 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:58:20.740  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:20.740  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:20.750  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:21.200  1015  2753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-16 17:58:21.340   288   288 E SMD     : DCD OFF
,08-16 17:58:21.810  6176  6229 D BluetoothAdapter: disable()
,08-16 17:58:21.810  1015  1353 D SettingsProvider: name = bluetooth_on
,08-16 17:58:21.820  6369  6805 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-16 17:58:21.820  6369  6805 D BluetoothAdapterProperties: Setting state to 13
08-16 17:58:21.820  6369  6805 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 17:58:21.820  6369  6805 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:21.820  6369  6805 D BluetoothAdapterService: updateAdapterState state is 13
,08-16 17:58:21.820  1015  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:21.820  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.820  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.820  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.820  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.820  6369  6805 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:58:21.820  6369  6805 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-16 17:58:21.820  6369  6805 D BluetoothAdapterService: terminating service from this receiver
,08-16 17:58:21.820  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.830  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.830  1015  3200 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:21.830  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:21.830  6369  6369 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-16 17:58:21.830  6369  6805 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:58:21.830  6369  6805 D BluetoothAdapterProperties: mDiscovering is false
,08-16 17:58:21.830  1015  3200 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:21.830  6369  6369 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c419341, channel: 19, state: LISTENING
08-16 17:58:21.830  6369  6805 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-16 17:58:21.830  6369  6369 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c419341, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367fee0e, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@180fb0e6mSocket: android.net.LocalSocket@3e789627 impl:android.net.LocalSocketImpl@204200d4 fd:FileDescriptor[75]
08-16 17:58:21.830  6369  6369 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3e789627 impl:android.net.LocalSocketImpl@204200d4 fd:FileDescriptor[75]
,08-16 17:58:21.840  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:21.840  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-16 17:58:21.840  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:21.840  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:21.850  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:21.850  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:21.850  1174  1174 D BluetoothTile:  getBluetoothState : 13
,08-16 17:58:21.850  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:21.850  1779  1779 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:21.860  1015  1138 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:21.860  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:21.860  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:21.860  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:21.860  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:21.870  1015  3200 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:21.870  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.870  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:21.870  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:21.870  6369  6808 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:21.870  6369  6808 D BluetoothAdapterProperties: Scan Mode:20,
08-16 17:58:21.870  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:21.870  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-16 17:58:21.870  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:21.870  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.870  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:21.880  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:21.880  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:21.880  6369  6805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 17:58:21.880  6369  6805 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-16 17:58:21.880  6369  6805 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-16 17:58:21.880  6369  6805 E bt-btif : cmd socket is not created
08-16 17:58:21.880  6369  6864 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:58:21.880  6369  6805 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 17:58:21.880  6176  6176 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:58:21.880  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:21.880  6369  6824 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-16 17:58:21.880  6369  6824 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:58:21.890  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:21.890  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:21.890  6369  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 17:58:21.890  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:21.890  1015  3200 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:21.890  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:21.890  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:21.890  1015  3200 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:21.890  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-16 17:58:21.890  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.900  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:21.900  1324  1324 D BluetoothPbap: Proxy object disconnected
08-16 17:58:21.900  1324  1324 D PbapServerProfile: Bluetooth service disconnected
,08-16 17:58:21.910  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:21.910  6369  6369 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1053227d, channel: 5, state: LISTENING
,08-16 17:58:21.910  6369  6369 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1053227d, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2465263c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3195f572mSocket: android.net.LocalSocket@15ce6dc3 impl:android.net.LocalSocketImpl@16285640 fd:FileDescriptor[77]
08-16 17:58:21.910  6369  6369 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15ce6dc3 impl:android.net.LocalSocketImpl@16285640 fd:FileDescriptor[77]
,08-16 17:58:21.910  6369  6369 I BtOppRfcommListener: stopping Accept Thread
08-16 17:58:21.910  6369  6369 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2ef46979, channel: 12, state: LISTENING
08-16 17:58:21.910  6369  6369 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2ef46979, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7c6a28, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2c9f6bemSocket: android.net.LocalSocket@e20231f impl:android.net.LocalSocketImpl@175c966c fd:FileDescriptor[79]
08-16 17:58:21.910  6369  6369 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e20231f impl:android.net.LocalSocketImpl@175c966c fd:FileDescriptor[79]
08-16 17:58:21.910  6369  6864 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:58:21.910  6369  6369 V BluetoothOppManager: cleanUp...
,08-16 17:58:21.910  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:21.920  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:21.920  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-16 17:58:21.940  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:21.940  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 17:58:22.090  6369  6824 W bt-btif : ag scb idx 1 not allocated
08-16 17:58:22.090  6369  6824 W bt-btif : ag scb idx 2 not allocated
08-16 17:58:22.090  6369  6824 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 17:58:22.090  6369  6846 I bt_userial_mct: exiting userial_read_thread
08-16 17:58:22.090  6369  6846 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 17:58:22.090  6369  6808 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 17:58:22.090  6369  6826 I bt_vendor: hw_epilog_process
08-16 17:58:22.090  6369  6808 D bt_userial_mct: userial_close
08-16 17:58:22.090  6369  6808 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-16 17:58:22.180  1015  2722 D SSRM:n  : SIOP:: AP = 330
,08-16 17:58:22.770  1015  1330 E Watchdog: !@Sync 4
,08-16 17:58:23.020  6369  6808 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-16 17:58:23.020  6369  6808 I bt_vendor: bluetooth satus is on
08-16 17:58:23.020  6369  6808 I bt_vendor: bt-vendor : resetting BT status
08-16 17:58:23.020  6369  6808 I bt_vendor: Starting hciattach daemon
08-16 17:58:23.020  6369  6808 I bt_vendor: try to set false
,08-16 17:58:23.020  6369  6808 I bt_vendor: Starting hciattach daemon
08-16 17:58:23.020  6369  6808 I bt_vendor: try to set false
,08-16 17:58:23.020  6369  6808 I bt_vendor: cleanup
,08-16 17:58:23.020  6369  6824 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 17:58:23.020  6369  6808 I GKI_LINUX: GKI_exit_task 0 done
08-16 17:58:23.020  6369  6808 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-16 17:58:23.020  6369  6805 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
,08-16 17:58:23.020  1015  3200 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.020  6369  6805 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:23.020  1015  3200 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.020  6369  6805 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
,08-16 17:58:23.020  1015  3201 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.020  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:58:23.020  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-16 17:58:23.020  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:58:23.030  1015  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.020  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
08-16 17:58:23.030  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.020  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.020  1015  3200 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:23.030  1015  1543 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-16 17:58:23.020  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:23.030  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-16 17:58:23.020  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:23.020  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:23.020  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-16 17:58:23.020  6369  6369 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 17:58:23.030  6369  6369 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:58:23.030  6369  6369 D BtGatt.GattService: stop()
08-16 17:58:23.030  6369  6369 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 17:58:23.030  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.030  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:23.030  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:23.030  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-16 17:58:23.030  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:23.030  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-16 17:58:23.030  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.030  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:23.030  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:23.030  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:23.030  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:23.030  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:23.030  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-16 17:58:23.040  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.040  1015  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:23.040  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:23.040  6369  6369 D HeadsetService: Received stop request...Stopping profile...
08-16 17:58:23.040  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:23.040  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:23.040  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:23.040  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-16 17:58:23.040  1015  1384 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.040  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.040  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 17:58:23.040  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.040  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:23.040  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:23.040  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-16 17:58:23.040  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:23.040  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-16 17:58:23.050  1015  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.050  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 17:58:23.050  1324  1324 D HeadsetProfile: Bluetooth service disconnected
08-16 17:58:23.050  6369  6369 D A2dpService: Received stop request...Stopping profile...
,08-16 17:58:23.050  6369  6818 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:58:23.050  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.050  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:23.050  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:23.050  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.050  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.050  6369  6805 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:23.050  1015  1545 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:23.050  1015  1545 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.050  1015  1545 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.050  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:23.050  1015  1545 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:23.050  1015  1545 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:23.060  1324  1324 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:58:23.060  1324  1324 D A2dpProfile: Bluetooth service disconnected
08-16 17:58:23.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:23.060  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-16 17:58:23.060  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-16 17:58:23.060  2865  2865 D BluetoothA2dp: Proxy object disconnected
,08-16 17:58:23.060  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:23.060  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.060  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.060  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:23.060  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:23.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:23.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-16 17:58:23.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
08-16 17:58:23.060  6369  6805 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:23.060  6369  6805 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:23.060  6369  6805 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 17:58:23.070  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-16 17:58:23.070  6369  6369 D HidService: Received stop request...Stopping profile...
08-16 17:58:23.070  6369  6369 D HidService: Stopping Bluetooth HidService,
08-16 17:58:23.070  6369  6369 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:58:23.070  6369  6369 W bt-btif : cleanup: HH disabling or disabled already, status = 0,
,08-16 17:58:23.070  6369  6369 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:58:23.070  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:23.070  1324  1324 D BluetoothInputDevice: Proxy object disconnected
,08-16 17:58:23.070  1324  1324 D HidProfile: Bluetooth service disconnected
,08-16 17:58:23.070  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-16 17:58:23.070  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-16 17:58:23.070  6369  6369 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:58:23.080  6369  6369 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:58:23.080  6369  6369 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 17:58:23.080  6369  6369 D HealthService: Received stop request...Stopping profile...
,08-16 17:58:23.080  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:23.080  6369  6369 D PanService: Received stop request...Stopping profile...
08-16 17:58:23.080  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:23.080  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:58:23.080  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-16 17:58:23.080  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:23.080  6369  6369 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-16 17:58:23.080  6369  6369 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:23.090  6369  6369 D BluetoothA2dp: Proxy object disconnected,
08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-16 17:58:23.090  6369  6819 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-16 17:58:23.090  1324  1324 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:58:23.090  6369  6369 I GKI_LINUX: GKI_exit_task 2 done
08-16 17:58:23.090  6369  6369 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-16 17:58:23.090  6369  6369 D SapService: Received stop request...Stopping profile...
,08-16 17:58:23.090  6369  6369 D SapService: Stopping Bluetooth SapService
,08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:23.090  1324  1324 D PanProfile: Bluetooth service disconnected
08-16 17:58:23.090  1324  1324 D BluetoothMap: Proxy object disconnected
,08-16 17:58:23.090  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-16 17:58:23.090  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.090  1324  1324 D MapProfile: Bluetooth service disconnected
08-16 17:58:23.090  1324  1324 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:23.090  1324  1324 D SapProfile: Bluetooth service disconnected
08-16 17:58:23.090  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-16 17:58:23.090  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.090  6369  6369 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:58:23.090  6369  6369 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:58:23.090  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-16 17:58:23.090  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.090  6369  6369 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:23.090  6369  6369 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:58:23.090  6369  6369 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-16 17:58:23.100  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-16 17:58:23.100  6369  6369 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:23.100  6369  6369 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-16 17:58:23.100  6369  6369 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-16 17:58:23.100  6369  6369 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-16 17:58:23.100  6369  6369 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-16 17:58:23.100  6369  6805 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-16 17:58:23.100  6369  6805 D BluetoothAdapterProperties: Setting state to 10
08-16 17:58:23.100  6369  6805 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 17:58:23.100  6369  6805 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:23.100  6369  6805 D BluetoothAdapterService: updateAdapterState state is 10
,08-16 17:58:23.100  6369  6805 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:23.100  6369  6805 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-16 17:58:23.100  6369  6805 I BluetoothAdapterState: Entering OffState
,08-16 17:58:23.100  1935  2114 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.100  1935  2114 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.100  1324  6361 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 17:58:23.100  1174  2341 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.100  1174  2341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.110  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.110  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.110  1433  2734 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:23.110  1433  2734 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.110  2865  2875 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.110  2865  2875 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.110  1324  6361 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.110  1324  6361 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.110  1324  1333 D Bluetoothsap: onBluetoothStateChange: up=false
,08-16 17:58:23.110  1324  1333 D Bluetoothsap: Unbinding service...
,08-16 17:58:23.120  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:23.120  6369  6377 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.120  6369  6377 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.120  1457  2968 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.120  1457  2968 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.120  6337  6348 D BluetoothAdapter: onBluetoothStateChange: up=false
08-16 17:58:23.120  6337  6348 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.120  2865  2877 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:23.120  6369  6378 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:23.120  1324  1338 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 17:58:23.120  6176  6188 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.130  6176  6188 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.130  6176  6188 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-16 17:58:23.130  6176  6188 D BluetoothLeAdvertiser: Exit stop advertising
,08-16 17:58:23.130  6176  6188 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-16 17:58:23.130  6176  6188 D BluetoothLeScanner: Exiting stopAllScan
,08-16 17:58:23.130  1324  6361 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 17:58:23.130  1447  1456 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-16 17:58:23.130  1447  1456 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-16 17:58:23.130  1324  1333 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:58:23.130  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-16 17:58:23.130  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:58:23.140  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:23.140  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
,08-16 17:58:23.140  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:23.150  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:23.150  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:23.150  1174  1739 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:23.150  1174  1174 D BluetoothTile:  getBluetoothState : 10
08-16 17:58:23.150  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:23.150  1174  1739 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:23.150  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:23.150  1174  1174 D BluetoothAdapter: 1018936756: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:23.150  6369  6808 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 17:58:23.150  1015  1250 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:23.150  1779  1779 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-16 17:58:23.150  6369  6369 I GKI_LINUX: GKI_exit_task 1 done
08-16 17:58:23.150  6369  6369 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-16 17:58:23.150  1015  3089 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-16 17:58:23.150  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:23.150  6369  6369 I BluetoothServiceJni: cleanupNative: return from cleanup,
08-16 17:58:23.150  1935  2125 D BluetoothAdapter: 649232868: getState() :  mService = null. Returning STATE_OFF
08-16 17:58:23.150  1935  2125 D BluetoothAdapter: 649232868: getState() :  mService = null. Returning STATE_OFF
,08-16 17:58:23.150  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:23.160  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:23.160  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:23.160  1015  3089 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:23.160  6369  6369 I art     : System.exit called, status: 0
08-16 17:58:23.160  6369  6369 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:58:23.160  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.160  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:23.160  1015  3089 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:23.160  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:23.170  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:23.170  1015  1250 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:23.170  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.170  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:23.170  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:23.170  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:23.180  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:23.190  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:23.190  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:23.190  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-16 17:58:23.200  1015  1384 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-16 17:58:23.200  1015  1384 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-16 17:58:23.200  1015  1384 W BroadcastQueue: android.os.TransactionTooLargeException
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-16 17:58:23.200  1015  1384 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:23.200  1015  1384 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-16 17:58:23.200  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:23.200  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:23.200  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:23.200  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:23.210  6883  6883 E Zygote  : MountEmulatedStorage(),
08-16 17:58:23.210  1015  1384 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6883 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-16 17:58:23.210  6883  6883 E Zygote  : v2
,08-16 17:58:23.210  6883  6883 I libpersona: KNOX_SDCARD checking this for 1002
08-16 17:58:23.210  6883  6883 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:23.220  6883  6883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:23.220  6883  6883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-16 17:58:23.230  6883  6883 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:23.240   312   312 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 754us total 29.719ms
,08-16 17:58:23.260  6883  6883 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:23.260  6883  6883 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:23.270   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 750us total 27.412ms
,08-16 17:58:23.270  6883  6883 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 17:58:23.270  6883  6883 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 17:58:23.290   312   312 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 707us total 20.512ms
,08-16 17:58:23.300  6883  6883 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding GattService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding HeadsetService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding A2dpService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding HidService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding HealthService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding PanService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding SapService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding SapClientService
08-16 17:58:23.340  6883  6883 D BtSettings.ProfileConfig: Adding HidDevService
,08-16 17:58:23.340  6883  6883 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-16 17:58:23.350  1015  1138 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-16 17:58:23.350  1015  1138 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  1138 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  1138 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1138 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  1138 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1138 D SettingsProvider: ret = -1
,08-16 17:58:23.350  1015  1543 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-16 17:58:23.350  1015  1543 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  1543 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-16 17:58:23.350  1015  1543 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1543 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:23.350  1015  1543 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1543 D SettingsProvider: ret = -1
,08-16 17:58:23.350  1015  3204 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-16 17:58:23.350  1015  3204 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  3204 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  3204 D SettingsProvider: selectionArgs: false
,08-16 17:58:23.350  1015  3204 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  3204 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  3204 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  1542 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-16 17:58:23.350  1015  1542 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:23.350  1015  1542 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:58:23.350  1015  1542 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1542 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  1542 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1542 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-16 17:58:23.350  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-16 17:58:23.350  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  1028 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:23.350  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1028 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  3200 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-16 17:58:23.350  1015  3200 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  3200 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-16 17:58:23.350  1015  3200 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  3200 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  3200 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  3200 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  1544 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:23.350  1015  1544 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  1544 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  1544 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1544 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  1544 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-16 17:58:23.350  1015  1544 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  1354 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-16 17:58:23.350  1015  1354 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.350  1015  1354 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  1354 D SettingsProvider: selectionArgs: false
,08-16 17:58:23.350  1015  1354 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  1354 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1354 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  1353 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:23.350  1015  1353 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:23.350  1015  1353 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  1353 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  1353 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:23.350  1015  1353 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  1353 D SettingsProvider: ret = -1
08-16 17:58:23.350  1015  3201 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:23.350  1015  3201 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-16 17:58:23.350  1015  3201 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.350  1015  3201 D SettingsProvider: selectionArgs: false
08-16 17:58:23.350  1015  3201 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.350  1015  3201 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.350  1015  3201 D SettingsProvider: ret = -1
08-16 17:58:23.360  1015  1545 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-16 17:58:23.360  1015  1545 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.360  1015  1545 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.360  1015  1545 D SettingsProvider: selectionArgs: false
08-16 17:58:23.360  1015  1545 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:23.360  1015  1545 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.360  1015  1545 D SettingsProvider: ret = -1
08-16 17:58:23.360  1015  3089 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-16 17:58:23.360  1015  3089 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:23.360  1015  3089 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:23.360  1015  3089 D SettingsProvider: selectionArgs: false
,08-16 17:58:23.360  1015  3089 D SettingsProvider: selectionArgs: 1002
08-16 17:58:23.360  1015  3089 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:23.360  1015  3089 D SettingsProvider: ret = -1
08-16 17:58:23.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...
,08-16 17:58:23.370  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:23.370  1015  1543 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:23.370  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:23.370  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.370  1015  1543 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:23.370  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:23.380  1935  6899 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:58:23.380  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:23.390  1015  3200 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:23.390  1015  3200 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:23.390  1015  3200 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:23.390  1015  3200 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:23.400  1935  6899 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-16 17:58:24.340   288   288 E SMD     : DCD OFF
,08-16 17:58:24.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:24.820  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:58:24.820  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:25.370   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:26.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:27.140  1015  1995 V SAMP_SPCM_test: CSC File load.. 
,08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling,
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn,
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-16 17:58:27.140  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-16 17:58:27.180  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-16 17:58:27.180  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,08-16 17:58:27.180  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,08-16 17:58:27.180  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,08-16 17:58:27.180  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering,
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction,
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:58:27.190  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag u,nder uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-16 17:58:27.200  1015  1995 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-16 17:58:27.230  1015  1995 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-16 17:58:27.350   288   288 E SMD     : DCD OFF
,08-16 17:58:27.360   324   324 I ServiceManager: Waiting for service AtCmdFwd...,
,08-16 17:58:27.820  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:27.820  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c0031a4 added. We now have 6 listener(s)
,08-16 17:58:27.820  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:27.820  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:27.820  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@240d4b0d added. We now have 7 listener(s)
08-16 17:58:27.820  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:27.820  6176  6229 I System.out: IsBluetoothEnabled
,08-16 17:58:27.820  6176  6229 D BluetoothAdapter: disable()
,08-16 17:58:27.830  1015  1544 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-16 17:58:27.830  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:27.830  6176  6229 D BluetoothAdapter: enable()
,08-16 17:58:27.830  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-16 17:58:27.830  1015  1027 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-16 17:58:27.830  1015  1027 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 17:58:27.830  1015  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:27.830  1015  1027 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:27.840  1015  1027 D SettingsProvider: name = bluetooth_on
,08-16 17:58:27.840  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:27.840  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:27.840  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-16 17:58:27.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-16 17:58:27.860  6883  6883 D BluetoothAdapterState: make
,08-16 17:58:27.860  6883  6883 I bluedroid: init
,08-16 17:58:27.870  6883  6905 I BluetoothAdapterState: Entering OffState
,08-16 17:58:27.870  6883  6883 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:58:27.870  6883  6883 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 17:58:27.870  6883  6883 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 17:58:27.870  6883  6883 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:58:27.870  6883  6883 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-16 17:58:27.870  6883  6883 I bluedroid: get_profile_interface socket
08-16 17:58:27.870  6883  6883 I bluedroid: get_profile_interface map_client
08-16 17:58:27.870  6883  6908 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-16 17:58:27.880  6883  6883 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-16 17:58:27.880  6883  6908 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:58:27.880  6883  6908 E BluetoothServiceJni: populateRssiValuesNative
08-16 17:58:27.880  6883  6908 I bluedroid: getModelRssiValues
,08-16 17:58:27.880  6883  6908 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:58:27.880  6883  6908 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:27.880  6883  6908 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:58:27.880  1015  1015 D SettingsProvider: name = bluetooth_name
,08-16 17:58:27.890  6883  6883 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:27.890  1015  1384 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:58:27.890  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.890  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.890  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:27.890  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.890  6883  6891 I bluedroid: config_hci_snoop_log
,08-16 17:58:27.890  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-16 17:58:27.890  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-16 17:58:27.900  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
08-16 17:58:27.900  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-16 17:58:27.900  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:27.900  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-16 17:58:27.900  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-16 17:58:27.900  6883  6883 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-16 17:58:27.900  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-16 17:58:27.910  6883  6905 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON,
08-16 17:58:27.910  6883  6905 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:58:27.910  6883  6905 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 17:58:27.910  6883  6905 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-16 17:58:27.910  6883  6905 D BluetoothAdapterService: updateAdapterState state is 11
,08-16 17:58:27.910  6883  6905 D BluetoothAdapterService: Autoconnection is available 
,08-16 17:58:27.910  6883  6905 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-16 17:58:27.920  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-16 17:58:27.920  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.920  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-16 17:58:27.920  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:27.920  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.920  1174  1174 D BluetoothTile:  getBluetoothState : 11
,08-16 17:58:27.930  6883  6905 D BluetoothSecureManager: getInstant: null
08-16 17:58:27.930  6883  6905 D BluetoothSecureManager: calling getMethod for getService
08-16 17:58:27.930  6883  6905 D BluetoothSecureManager: calling getService
,08-16 17:58:27.930  6883  6905 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@d43b27b
,08-16 17:58:27.930  1015  1354 D BluetoothSecureManagerService: isSecureModeEnabled
08-16 17:58:27.930  1015  1354 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-16 17:58:27.930  6883  6905 D BtConfig.SecureMode: isSecureModeOn:false
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-16 17:58:27.930  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:27.930  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:27.930  1779  1779 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:27.930  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-16 17:58:27.930  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-16 17:58:27.940  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:27.940  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-16 17:58:27.940  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.940  1015  1354 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:27.940  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:27.940  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:27.940  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-16 17:58:27.940  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:27.940  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:27.940  6883  6905 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-16 17:58:27.940  6883  6905 D BluetoothBondStateMachine: make
,08-16 17:58:27.940  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:27.950  1015  3202 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:27.950  1015  3202 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.950  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.950  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:27.950  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:27.950  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-16 17:58:27.950  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-16 17:58:27.950  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-16 17:58:27.950  6883  6909 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:58:27.960  1015  3089 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:27.960  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.960  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:27.960  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:27.960  1015  3089 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:27.960  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.960  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.960  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-16 17:58:27.960  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-16 17:58:27.960  6883  6883 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:58:27.960  6883  6883 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:58:27.960  6883  6883 D BtGatt.GattService: start()
08-16 17:58:27.960  6883  6883 D BtGatt.GattService: start()
08-16 17:58:27.960  6883  6883 I bluedroid: get_profile_interface gatt
,08-16 17:58:27.960  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:27.960  6883  6883 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:58:27.970  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:27.970  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-16 17:58:27.970  1015  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:27.970  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.970  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.970  1015  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:27.970  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-16 17:58:27.980  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:27.980  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-16 17:58:27.980  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-16 17:58:27.980  1015  3204 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:27.980  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:27.980  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:27.980  1015  3204 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:27.980  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:27.990  6883  6883 D BtGatt.GattService: mStartError = false,
08-16 17:58:27.990  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:27.990  6883  6883 D HeadsetService: Received start request. Starting profile...
,08-16 17:58:27.990  6883  6883 D HeadsetService: start()
,08-16 17:58:27.990  6883  6883 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 17:58:27.990  6883  6883 D HeadsetStateMachine: make
,08-16 17:58:27.990  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-16 17:58:27.990  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-16 17:58:27.990  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-16 17:58:28.000  6883  6883 E HeadsetStateMachine: # of Max HF connection is 2,
,08-16 17:58:28.000  1015  3202 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:28.000  1015  3202 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.000  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.000  1015  3202 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.000  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.010  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-16 17:58:28.010  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-16 17:58:28.010  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-16 17:58:28.010  1015  1250 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-16 17:58:28.010  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.010  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.010  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.010  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:28.010  1015  1542 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-16 17:58:28.010  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.010  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.010  1015  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.010  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-16 17:58:28.010  6883  6883 I bluedroid: get_profile_interface handsfree
08-16 17:58:28.010  1015  1544 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:28.010  1015  1544 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.020  1015  1544 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.020  1015  1544 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.020  1015  1544 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.020  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-16 17:58:28.020  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-16 17:58:28.020  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-16 17:58:28.020  1015  1353 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:28.020  1015  1353 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.020  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.020  1015  1353 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.020  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.030  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-16 17:58:28.030  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-16 17:58:28.030  6883  6905 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-16 17:58:28.030  1015  3201 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:28.030  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.030  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.030  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.030  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.030  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-16 17:58:28.030  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-16 17:58:28.030  6883  6905 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-16 17:58:28.030  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:28.030  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.040  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.040  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.040  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.040  6883  6883 I DualScoManager: Instantiating Dual Sco Manager,
08-16 17:58:28.040  6883  6883 I DualScoManager: Set HeadsetServiceHelper
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:28.040  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:28.040  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-16 17:58:28.040  6883  6883 D BluetoothAtMessage: createCMTIContentObservers
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-16 17:58:28.040  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-16 17:58:28.040  6883  6905 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-16 17:58:28.040  6883  6905 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-16 17:58:28.040  6883  6905 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-16 17:58:28.040  1015  3200 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-16 17:58:28.040  1015  3200 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:28.050  1015  3200 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:28.050  1015  3200 D SettingsProvider: selectionArgs: false
08-16 17:58:28.050  1015  3200 D SettingsProvider: selectionArgs: 1002
,08-16 17:58:28.050  1015  3200 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:28.050  1015  3200 D SettingsProvider: ret = -1
,08-16 17:58:28.050  6883  6913 D HeadsetStateMachine: Enter Disconnected: -2
,08-16 17:58:28.050  6883  6883 D HeadsetService: mStartError = false
,08-16 17:58:28.050  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:28.050  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-16 17:58:28.050  6883  6883 D A2dpService: Received start request. Starting profile...
,08-16 17:58:28.050  6883  6883 D A2dpService: start()
,08-16 17:58:28.060  6883  6883 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:58:28.060  6883  6883 I bluedroid: get_profile_interface avrcp
,08-16 17:58:28.060  6883  6913 D HeadsetStateMachine: Clear mHeadsetBrsf
08-16 17:58:28.060  6883  6913 D HeadsetStateMachine: map size, before remove : 0
08-16 17:58:28.060  6883  6913 D HeadsetStateMachine: map size, after remove: 0
,08-16 17:58:28.060  6883  6883 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:58:28.080  6883  6883 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-16 17:58:28.080  6883  6883 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:58:28.080  6883  6883 D A2dpStateMachine: make
,08-16 17:58:28.080  6883  6918 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-16 17:58:28.090  6883  6883 I bluedroid: get_profile_interface a2dp
08-16 17:58:28.090  6883  6920 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-16 17:58:28.090  6883  6883 E bt-btif : warning : media task started media_task_refcnt 1 
,08-16 17:58:28.090  6883  6883 D A2dpService: mStartError = false
08-16 17:58:28.090  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:28.090  6883  6919 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:58:28.090  6883  6883 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:58:28.090  6883  6883 D HidService: Received start request. Starting profile...
08-16 17:58:28.090  6883  6883 D HidService: start()
08-16 17:58:28.090  6883  6883 I bluedroid: get_profile_interface hidhost
08-16 17:58:28.090  6883  6883 D HidService: setHidService(): set to: null
08-16 17:58:28.090  6883  6883 D HidService: mStartError = false
08-16 17:58:28.090  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:28.090  6883  6883 D HeadsetStateMachine: Try to query the phonestate on bind
,08-16 17:58:28.090  1433  6876 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:58:28.090  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-16 17:58:28.100  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:28.100  1433  6876 I Telecom : BluetoothPhoneService: Result of Message : true
,08-16 17:58:28.100  6883  6883 D HeadsetStateMachine: Proxy object connected
,08-16 17:58:28.100  6883  6883 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:58:28.100  6883  6883 D HealthService: Received start request. Starting profile...
08-16 17:58:28.100  6883  6883 D HealthService: start()
,08-16 17:58:28.100  6883  6883 I bluedroid: get_profile_interface health
,08-16 17:58:28.100  6883  6883 D HealthService: mStartError = false
08-16 17:58:28.100  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:28.100  6883  6883 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-16 17:58:28.100  6883  6913 D HeadsetStateMachine: Disconnected process message: 11
08-16 17:58:28.100  6883  6883 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:58:28.100  6883  6883 D PanService: Received start request. Starting profile...
,08-16 17:58:28.100  6883  6883 D PanService: start()
08-16 17:58:28.100  6883  6883 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 17:58:28.110  6883  6883 I bluedroid: get_profile_interface pan
,08-16 17:58:28.110  6883  6883 D PanService: mStartError = false
08-16 17:58:28.110  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:28.110  6883  6918 D BluetoothMediaBrowser: no now playing list
,08-16 17:58:28.110  6883  6918 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-16 17:58:28.110  6883  6883 D BluetoothMapService: Received start request. Starting profile...
08-16 17:58:28.110  6883  6883 D BluetoothMapService: start()
,08-16 17:58:28.110  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-16 17:58:28.120  6883  6883 D BluetoothMapService: mStartError = false
08-16 17:58:28.120  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:28.120  6883  6883 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-16 17:58:28.120  6883  6883 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-16 17:58:28.120  6883  6913 D HeadsetStateMachine: Disconnected process message: 18
08-16 17:58:28.120  6883  6883 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-16 17:58:28.120  6883  6883 D SapService: Received start request. Starting profile...
08-16 17:58:28.120  6883  6883 D SapService: start()
08-16 17:58:28.120  6883  6883 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-16 17:58:28.120  6883  6883 I bluedroid: get_profile_interface sap
08-16 17:58:28.120  6883  6883 D SapService: mStartError = false
08-16 17:58:28.120  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
08-16 17:58:28.120  6883  6883 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-16 17:58:28.120  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-16 17:58:28.120  6883  6883 D BluetoothA2dp: Proxy object connected
08-16 17:58:28.120  6883  6883 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-16 17:58:28.120  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-16 17:58:28.120  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-16 17:58:28.120  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-16 17:58:28.120  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-16 17:58:28.120  6883  6913 D HeadsetStateMachine: Disconnected process message: 10
08-16 17:58:28.120  6883  6913 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:58:28.120  6883  6913 D HeadsetStateMachine: Disconnected process message: 11
,08-16 17:58:28.130  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:28.150  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-16 17:58:28.150  6883  6883 E BluetoothAdapterService(1063252157): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-16 17:58:28.150  6883  6905 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-16 17:58:28.150  6883  6905 I bluedroid: enable
08-16 17:58:28.150  6883  6924 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-16 17:58:28.150  6883  6905 I bt_hci_bdroid: init
,08-16 17:58:28.150  6883  6905 I bt_vendor: bt-vendor : init
08-16 17:58:28.150  6883  6905 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 17:58:28.150  6883  6905 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 17:58:28.150  6883  6905 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-16 17:58:28.150  6883  6905 D bt_userial_mct: userial_init
,08-16 17:58:28.160  6883  6905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 17:58:28.160  6883  6905 I bt_vendor: Starting hciattach daemon
08-16 17:58:28.160  6883  6905 I bt_vendor: try to set false
,08-16 17:58:28.160  6883  6905 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-16 17:58:28.160  6883  6905 I bt_vendor: Starting hciattach daemon
08-16 17:58:28.160  6883  6905 I bt_vendor: try to set true
,08-16 17:58:28.180  6928  6928 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-16 17:58:28.230  6934  6934 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-16 17:58:28.240  6935  6935 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:58:28.250  6937  6937 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:58:28.260  6938  6938 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-16 17:58:28.270  6939  6939 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-16 17:58:28.280  6940  6940 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-16 17:58:28.370   324   324 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-16 17:58:28.560  6943  6943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-16 17:58:28.570  6944  6944 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-16 17:58:28.620  6883  6905 I bt_vendor: bluetooth satus is on
,08-16 17:58:28.620  6883  6926 D bt_userial_mct: userial_open(port:0)
08-16 17:58:28.620  6883  6926 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 17:58:28.620  6883  6926 I bt_vendor: Done intiailizing UART,
,08-16 17:58:28.620  6883  6926 I bt_vendor: Done intiailizing UART
08-16 17:58:28.620  6883  6926 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 17:58:28.620  6883  6926 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_SAP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 17:58:28.620  6883  6924 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
08-16 17:58:28.630  6883  6946 D bt_userial_mct: Entering userial_read_thread()
,08-16 17:58:28.730  6883  6924 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-16 17:58:28.730  6883  6924 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3fc06e9 
,08-16 17:58:28.730  6883  6924 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3fc06e9 
,08-16 17:58:28.750  6883  6908 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-16 17:58:28.750  6883  6908 E bt-btif : Calling BTA_HhEnable
,08-16 17:58:28.760  6883  6908 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-16 17:58:28.760  6883  6908 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-16 17:58:28.760  6883  6908 E BluetoothServiceJni: populateRssiValuesNative
,08-16 17:58:28.760  6883  6908 I bluedroid: getModelRssiValues
,08-16 17:58:28.760  6883  6908 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-16 17:58:28.760  6883  6908 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-16 17:58:28.760  1015  1015 D SettingsProvider: name = bluetooth_name
,08-16 17:58:28.760  6883  6908 D BluetoothAdapterProperties: Name is: A5-1
,08-16 17:58:28.770  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:28.770  6883  6908 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-16 17:58:28.770  6883  6908 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:58:28.770  6883  6908 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:58:28.770  6883  6908 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-16 17:58:28.770  6883  6908 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-16 17:58:28.770  6883  6908 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-16 17:58:28.770  6883  6908 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-16 17:58:28.770  6883  6908 E bt-btif : btif_sock_init: !vhci_init
08-16 17:58:28.770  6883  6908 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-16 17:58:28.770  6883  6908 D IOP_DB_BT: db_open: db_open : handle 3024728080l, read 13894 bytes onto local cache
08-16 17:58:28.770  6883  6908 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-16 17:58:28.770  6883  6908 D IOP_DB_BT: db_query: result 1
08-16 17:58:28.770  6883  6908 I         : iop_db_open: iop_db_open status 0
,08-16 17:58:28.770  6883  6908 D bte_conf: Device ID record 1 : primary
,08-16 17:58:28.770  6883  6908 D bte_conf:   vendorId            = 0075
08-16 17:58:28.770  6883  6908 D bte_conf:   vendorIdSource      = 0001
,08-16 17:58:28.770  6883  6908 D bte_conf:   product             = 0100
08-16 17:58:28.770  6883  6908 D bte_conf:   version             = 0200
,08-16 17:58:28.770  6883  6908 D bte_conf:   clientExecutableURL = 
08-16 17:58:28.770  6883  6908 D bte_conf:   serviceDescription  = 
,08-16 17:58:28.770  6883  6908 D bte_conf:   documentationURL    = 
08-16 17:58:28.770  6883  6908 D bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:58:28.770  6883  6908 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:58:28.780  6883  6905 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-16 17:58:28.780  6883  6905 D BluetoothAdapterProperties: ScanMode =  20
,08-16 17:58:28.780  6883  6905 D BluetoothAdapterProperties: State =  11
,08-16 17:58:28.780  1015  1542 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-16 17:58:28.780  6883  6905 D BluetoothAdapterProperties: Setting state to 12
08-16 17:58:28.780  6883  6905 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 17:58:28.780  6883  6908 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-16 17:58:28.780  6883  6908 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:58:28.780  6883  6908 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:58:28.780  1015  3201 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-16 17:58:28.780  1015  3201 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-16 17:58:28.780  1015  3201 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-16 17:58:28.780  1015  3201 D SettingsProvider: selectionArgs: false
08-16 17:58:28.780  1015  3201 D SettingsProvider: selectionArgs: 1002
08-16 17:58:28.790  1015  3201 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-16 17:58:28.790  1015  3201 D SettingsProvider: ret = -1
,08-16 17:58:28.790  6883  6905 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-16 17:58:28.790  6883  6905 D BluetoothAdapterService: updateAdapterState state is 12
08-16 17:58:28.790  6883  6946 E bt_mct  : hci lib postload completed
,08-16 17:58:28.790  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-16 17:58:28.790  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.790  1015  1028 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:58:28.790  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.790  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.790  6883  6905 D BluetoothAdapterService: Autoconnection is available 
08-16 17:58:28.790  6883  6905 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-16 17:58:28.790  6883  6905 D BluetoothAdapterService: starting service from this receiver
08-16 17:58:28.790  1935  1946 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.790  1935  1946 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.800  1015  1250 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:28.800  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-16 17:58:28.800  1324  1333 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:58:28.800  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.800  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.800  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.800  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:28.810  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-16 17:58:28.810  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.810  6883  6905 I BluetoothAdapterState: Entering On State from state = 11
,08-16 17:58:28.810  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.810  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.810  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.810  1174  2709 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:28.820  1174  2709 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.820  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:28.820  1324  1338 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.820  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:28.820  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.830  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.830  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.830  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.830  6883  6883 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-16 17:58:28.830  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.830  1324  1338 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:58:28.830  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:28.830  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.830  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.830  1433  2734 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.830  1433  2734 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.830  1433  1442 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-16 17:58:28.830  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.830  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.830  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 17:58:28.830  1433  1442 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.830  1433  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.830  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.830  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.840  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.840  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.840  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.840  1433  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.840  1324  6361 D BluetoothPan: Binding service...
,08-16 17:58:28.840  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:28.840  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.840  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.840  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.840  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.840  2865  6852 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.840  2865  6852 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.850  6883  6883 I BluetoothPbapService: Handler(): got msg=1
08-16 17:58:28.850  6883  6949 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.850  6883  6949 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.850  1324  1324 D BluetoothPbap: Proxy object connected
08-16 17:58:28.850  1324  1324 D PbapServerProfile: Bluetooth service connected
,08-16 17:58:28.850  1015  1544 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:28.850  1324  1338 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.850  1324  1338 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.850  1015  1044 D BluetoothPan: Binding service...
08-16 17:58:28.850  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-16 17:58:28.850  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-16 17:58:28.850  1324  6361 D Bluetoothsap: onBluetoothStateChange: up=true
,08-16 17:58:28.850  1324  6361 D Bluetoothsap: Binding service...
,08-16 17:58:28.850  1324  6361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-16 17:58:28.850  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-16 17:58:28.850  1324  1324 D HeadsetProfile: Bluetooth service connected
08-16 17:58:28.850  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.860  6883  6951 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:28.860  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:28.860  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.860  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.860  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.860  1324  6361 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-16 17:58:28.860  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 17:58:28.860  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.860  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.860  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:28.860  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-16 17:58:28.860  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:58:28.860  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.860  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:28.860  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.860  1433  1441 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.860  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:28.860  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:28.860  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.870  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:28.870  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.870  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3f951ac2 added. We now have 8 listener(s)
08-16 17:58:28.870  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.870  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-16 17:58:28.870  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:28.870  1433  1441 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.870  6883  6914 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.870  6883  6951 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:28.870  6883  6951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:28.870  2865  2877 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.870  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-16 17:58:28.870  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-16 17:58:28.870  1015  1015 D BluetoothA2dp: Proxy object connected
08-16 17:58:28.870  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.870  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.870  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.870  1015  3089 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-16 17:58:28.870  1015  3089 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:28.870  1015  3089 D SecContentProvider2: mCursor = null
,08-16 17:58:28.870  2865  2877 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.870  1324  1324 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:58:28.870  1015  3089 D WifiService: setWifiEnabled: false pid=6176, uid=10155
,08-16 17:58:28.870  1015  3089 D SettingsProvider: name = wifi_on
08-16 17:58:28.870  1457  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.870  1457  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-16 17:58:28.870  1324  1324 D PanProfile: Bluetooth service connected
,08-16 17:58:28.870  6337  6348 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.870  6337  6348 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.870  2865  2875 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.880  2865  2875 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.880  1015  1044 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-16 17:58:28.880  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.880  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.880  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.880  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-16 17:58:28.880  6883  6951 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-16 17:58:28.880  6883  6951 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:28.880  6883  6951 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:28.880  6883  6951 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@367fee0e
,08-16 17:58:28.880  2865  2865 D BluetoothA2dp: Proxy object connected
08-16 17:58:28.880  6883  6951 D BluetoothSocket: channel: 19
08-16 17:58:28.880  6883  6951 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-16 17:58:28.880  1324  6361 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:58:28.880  1324  1324 D Bluetoothsap: BluetoothSAP Proxy object connected
08-16 17:58:28.880  1324  1324 D SapProfile: Bluetooth service connected
,08-16 17:58:28.880  1324  1324 D Bluetoothsap: getConnectedDevices()
,08-16 17:58:28.880  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-16 17:58:28.880  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.880  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.880  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.880  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.890  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:28.890  1015  1250 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-16 17:58:28.890  6176  6184 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-16 17:58:28.890  1015  1250 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-16 17:58:28.890  1015  1250 D SecContentProvider2: mCursor = null
,08-16 17:58:28.890  1324  1324 D BluetoothInputDevice: Proxy object connected
08-16 17:58:28.890  1015  1250 D WifiService: setWifiEnabled: true pid=6176, uid=10155
08-16 17:58:28.890  1324  1324 D HidProfile: Bluetooth service connected
08-16 17:58:28.890  1015  1250 W ActivityManager: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:28.890  1015  1250 W WifiService: Failed getting userId using ActivityManagerNative
08-16 17:58:28.890  1015  1250 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6176, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-16 17:58:28.890  1015  1250 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-16 17:58:28.890  1015  1250 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-16 17:58:28.890  1015  1250 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-16 17:58:28.890  1015  1250 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-16 17:58:28.890  1015  1250 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-16 17:58:28.890  1015  1250 D SettingsProvider: name = wifi_on
,08-16 17:58:28.890  6176  6184 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.900  1324  1333 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:58:28.900  1324  1333 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.900  1015  1044 W ActivityManager: userId = 0, bbcId = -10000,
08-16 17:58:28.900  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-16 17:58:28.900  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.900  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.900  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-16 17:58:28.900  1324  1324 D BluetoothA2dp: Proxy object connected
08-16 17:58:28.900  1324  1324 D A2dpProfile: Bluetooth service connected
,08-16 17:58:28.900  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
08-16 17:58:28.900  1457  1472 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-16 17:58:28.900  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-16 17:58:28.900  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-16 17:58:28.900  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.900  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.900  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.900  1457  1472 E BluetoothHeadset: BluetoothHeadset service is binded
,08-16 17:58:28.900  1447  1456 D BluetoothAdapter: onBluetoothStateChange: up=true
08-16 17:58:28.900  1447  1456 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-16 17:58:28.910  1324  6361 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:58:28.910  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-16 17:58:28.910  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.910  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:28.910  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.910  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:28.910  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-16 17:58:28.910  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-16 17:58:28.920  1324  1324 D BluetoothMap: Proxy object connected
08-16 17:58:28.920  1324  1324 D MapProfile: Bluetooth service connected
08-16 17:58:28.920  1324  1324 D BluetoothMap: getConnectedDevices()
,08-16 17:58:28.920  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:28.920  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
,08-16 17:58:28.920  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-16 17:58:28.930  1433  1433 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@30e4456a, true
,08-16 17:58:28.930  1433  1433 D BluetoothHeadset: registerMessageListener
,08-16 17:58:28.940  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,08-16 17:58:28.940  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-16 17:58:28.940  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:28.940  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:28.940  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:58:28.940  1174  1174 D BluetoothTile:  getBluetoothState : 12
,08-16 17:58:28.950  1174  1739 D BluetoothTile:  handleUpdatestate:false name:null
,08-16 17:58:28.950  1779  1779 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-16 17:58:28.950  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:28.950  1015  3202 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-16 17:58:28.960  1015  1027 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-16 17:58:28.960  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-16 17:58:28.960  1015  3204 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:28.960  1015  3204 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.960  6883  6914 D HeadsetService: registerMessageListener
08-16 17:58:28.960  1015  3204 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.960  1015  3204 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:28.960  1015  3204 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:28.960  1324  1324 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:28.960  6883  6914 D HeadsetService: registerMessageListener
08-16 17:58:28.960  6883  6913 D HeadsetStateMachine: Disconnected process message: 70
,08-16 17:58:28.960  6883  6913 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1bd4d02f
,08-16 17:58:28.960  1433  1433 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-16 17:58:28.960  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-16 17:58:28.970  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-16 17:58:28.970  1433  1433 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-16 17:58:28.970  1433  1433 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-16 17:58:28.970  1324  1324 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-16 17:58:28.970  1324  1324 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-16 17:58:28.970  1324  1324 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-16 17:58:28.970  1324  1324 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-16 17:58:28.970  6883  6956 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-16 17:58:28.980  6883  6956 D BluetoothSocket: bindListen(): myUserId = 0
08-16 17:58:28.980  6883  6956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:28.980  6883  6913 D HeadsetStateMachine: Disconnected process message: 9
,08-16 17:58:28.980  6883  6956 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
,08-16 17:58:28.980  6883  6956 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:28.980  6883  6956 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:28.980  6883  6956 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2465263c
,08-16 17:58:28.980  6883  6913 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-16 17:58:28.980  6883  6956 D BluetoothSocket: channel: 5
,08-16 17:58:28.980  1324  1324 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:58:28.980  1015  3089 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-16 17:58:28.980  1015  3089 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-16 17:58:28.990  1015  3089 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:28.990  1015  3089 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:28.990  1015  3089 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-16 17:58:28.990   283   705 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-16 17:58:29.000   283   705 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-16 17:58:29.000   283   705 V voice   : voice_set_parameters: exit with code(-2)
08-16 17:58:29.000   283   705 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-16 17:58:29.000   283   705 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-16 17:58:29.000   283   705 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-16 17:58:29.000   283   705 V audio_hw_primary: adev_set_parameters: exit
08-16 17:58:29.000  6883  6913 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-16 17:58:29.000  1324  1324 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:58:29.000  1324  1324 D BluetoothNotiBroadcastReceiver: onReceive
,08-16 17:58:29.010  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:58:29.010  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-16 17:58:29.020  6883  6883 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:29.020  6883  6883 D BtConfig.SecureMode: isSecureModeOn:false
,08-16 17:58:29.020  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-16 17:58:29.020  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-16 17:58:29.020  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:29.020  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-16 17:58:29.020  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-16 17:58:29.040  1935  1935 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-16 17:58:29.040  1015  3201 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-16 17:58:29.040  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:29.050  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:29.050  1015  3201 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:29.050  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:29.050  1935  6962 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-16 17:58:29.050  1935  1935 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-16 17:58:29.050  1015  3201 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-16 17:58:29.060  1015  1353 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:29.060  1015  1353 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:29.060  1015  1353 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-16 17:58:29.060  1015  1353 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:29.070  1015  3202 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-16 17:58:29.080  1015  3202 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:29.080  1015  3202 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-16 17:58:29.080  1015  3202 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-16 17:58:29.080  6883  6966 D BluetoothSocket: bindListen(): myUserId = 0
,08-16 17:58:29.080  6883  6966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:58:29.080  6883  6966 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-16 17:58:29.080  6883  6966 D BluetoothSocket: bindListen(), new LocalSocket 
08-16 17:58:29.080  6883  6966 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-16 17:58:29.080  6883  6966 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c7c6a28
,08-16 17:58:29.080  6883  6966 D BluetoothSocket: channel: 12
08-16 17:58:29.080  6883  6966 I BtOppRfcommListener: Accept thread started.
,08-16 17:58:29.090  1935  6962 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-16 17:58:29.290  1015  1042 D Tethering: interfaceAdded wlan0,
,08-16 17:58:29.290  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:29.290  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:29.290  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:29.300  1015  1042 D Tethering: interfaceAdded p2p0
,08-16 17:58:29.300  1015  1129 E Tethering: No numeric data
,08-16 17:58:29.300  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:29.300  1015  1129 D Tethering: clearTetheredNotification()
08-16 17:58:29.300  1015  1129 D Tethering: InitialState.processMessage what=4
08-16 17:58:29.310  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:29.310  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.310  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:29.310  1174  1174 D HotspotTile: updateTetherState():false, false
08-16 17:58:29.310  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:29.310  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:29.310  1015  1129 E Tethering: No numeric data
08-16 17:58:29.310  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 17:58:29.310  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
08-16 17:58:29.320  1015  1129 D Tethering: clearTetheredNotification()
,08-16 17:58:29.320  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.320  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-16 17:58:29.320  1174  1174 D HotspotTile: updateTetherState():false, false
,08-16 17:58:29.320  1015  1123 V NetworkStats: performPollLocked() took 13ms
,08-16 17:58:29.320  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.320  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.320  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:29.330  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:29.330  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:29.330  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.330   278   995 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-16 17:58:29.330  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.330   278   995 D SoftapController: Softap fwReload - Ok
,08-16 17:58:29.330  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:29.330  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:29.330   278   995 D CommandListener: Setting iface cfg
08-16 17:58:29.330   278   995 D CommandListener: Trying to bring down wlan0
,08-16 17:58:29.330   278   995 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:58:29.340  1015  1123 V NetworkStats: performPollLocked() took 10ms
08-16 17:58:29.340  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.340  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.340  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:29.340  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-16 17:58:29.340  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-16 17:58:29.340  1015  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-16 17:58:29.350  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:29.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-16 17:58:29.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:29.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:29.350  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:29.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:29.350  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-16 17:58:29.350  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-16 17:58:29.350  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:29.360  1174  1174 D HotspotTile: onReceive : 2, 0
,08-16 17:58:29.360  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:29.370  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:29.370  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:29.370  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:29.370  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:29.370  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:29.370  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:29.370  3588  3588 I Hs20UtilService: Starting #17
08-16 17:58:29.370  3588  3624 I Hs20UtilService: Message received 5011
,08-16 17:58:29.380  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:29.380  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:29.380  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:29.380  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:29.400  6974  6974 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-16 17:58:29.400  6974  6974 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 17:58:29.400  6974  6974 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-16 17:58:29.420  6974  6974 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-16 17:58:29.420   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6974
,08-16 17:58:29.420   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-16 17:58:29.420  6974  6974 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-16 17:58:29.420  6974  6974 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.420  6974  6974 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-16 17:58:29.420  6974  6974 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
08-16 17:58:29.420   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6974
08-16 17:58:29.420   386   386 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-16 17:58:29.570   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,08-16 17:58:29.580  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-16 17:58:29.650  6974  6974 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-16 17:58:29.650  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-16 17:58:29.660  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-16 17:58:29.660   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6974
08-16 17:58:29.660   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-16 17:58:29.660  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 17:58:29.660  6974  6974 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.660  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-16 17:58:29.660  6974  6974 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.660  6974  6974 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.660  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.660  6974  6974 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.660  6974  6974 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.660  6974  6974 I wpa_supplicant: Blacklist: Clear (all) 
08-16 17:58:29.660  6974  6974 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:29.660  6974  6974 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:29.660  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.660  6974  6974 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-16 17:58:29.660  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.660  6974  6974 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.660  6974  6974 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 17:58:29.660  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:29.660  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:29.660  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:29.760  6974  6974 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-16 17:58:29.950  6974  6974 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-16 17:58:29.950  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-16 17:58:29.960  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,08-16 17:58:29.970   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6974
08-16 17:58:29.970   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-16 17:58:29.970  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
08-16 17:58:29.970  6974  6974 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.970  6974  6974 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-16 17:58:29.970  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,08-16 17:58:29.980  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
08-16 17:58:29.980   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6974
08-16 17:58:29.980   386   386 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
08-16 17:58:29.980  6974  6974 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-16 17:58:29.980  6974  6974 I wpa_supplicant: ssSupport state is = 1
08-16 17:58:29.980  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:29.980  6974  6974 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-16 17:58:29.980  6974  6974 E wpa_supplicant: SIM READ ERROR
08-16 17:58:29.980  6974  6974 I wpa_supplicant: wpa_default_ap_write_once
08-16 17:58:29.980  6974  6974 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-16 17:58:29.980  6974  6974 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 17:58:29.990  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.990  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.990  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:29.990  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:58:29.990  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-16 17:58:29.990  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:30.100  6974  6974 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-16 17:58:30.100  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-16 17:58:30.140  6974  6974 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-16 17:58:30.140  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-16 17:58:30.140  6974  6974 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 17:58:30.290  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false,
08-16 17:58:30.290  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-16 17:58:30.290  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-16 17:58:30.350   288   288 E SMD     : DCD OFF,
08-16 17:58:30.350  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-16 17:58:30.350  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-16 17:58:30.350  6974  6974 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-16 17:58:30.350  6974  6974 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-16 17:58:30.350  6974  6974 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-16 17:58:30.350  6974  6974 E wpa_supplicant: SIM READ ERROR,
08-16 17:58:30.350  6974  6974 I wpa_supplicant: Blacklist: Clear (all) 
,08-16 17:58:30.360  6974  6974 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-16 17:58:30.370  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-16 17:58:30.370  6974  6974 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-16 17:58:30.370  1015  1126 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:58:30.380  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:30.380  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:30.380  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:30.380  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:30.380  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:30.380  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:30.380  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-16 17:58:30.380  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-16 17:58:30.380  1174  1739 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-16 17:58:30.380  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:30.390  1015  1126 E WifiConfigStore: Not a HS20
,08-16 17:58:30.390  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 17:58:30.390  1174  1174 D HotspotTile: onReceive : 3, 0
,08-16 17:58:30.390  1324  1324 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:30.400  6176  6176 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:30.400  6176  6176 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:30.400  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-16 17:58:30.410  1015  1384 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-16 17:58:30.410  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:30.410  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,08-16 17:58:30.410  6974  6974 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-16 17:58:30.410  6974  6974 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-16 17:58:30.410  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:30.410  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:30.410  6974  6974 I wpa_supplicant: reset timer : RESET_TIMER 0
,08-16 17:58:30.410  6974  6974 I wpa_supplicant: P2P: Current p2p state = IDLE
08-16 17:58:30.410  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:30.410  6974  6974 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,08-16 17:58:30.410  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-16 17:58:30.410  6974  6974 I wpa_supplicant: First Scan Start
,08-16 17:58:30.410  6974  6974 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-16 17:58:30.410  3588  3588 I Hs20UtilService: Starting #18,
,08-16 17:58:30.410  3588  3624 I Hs20UtilService: Message received 5011
08-16 17:58:30.410  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-16 17:58:30.410  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 17:58:30.410  1015  1126 I WifiNative-HAL: startHal
08-16 17:58:30.410  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9c8ef88c
08-16 17:58:30.410  1015  1126 I WifiNative-HAL: Could not start hal
,08-16 17:58:30.420  6392  6392 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:58:30.420  1015  1126 E WifiNative-wlan0: do suspend true
,08-16 17:58:30.420  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-16 17:58:30.430   278   995 D CommandListener: Setting iface cfg
08-16 17:58:30.430   278   995 D CommandListener: Trying to bring up p2p0
,08-16 17:58:30.430  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:58:30.430  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-16 17:58:30.430  1015  1125 D WifiP2pService: P2pEnablingState
08-16 17:58:30.430  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 17:58:30.430  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-16 17:58:30.430  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:30.430  1015  1125 D WifiP2pService: P2p socket connection successful
08-16 17:58:30.430  1015  1149 I WifiNative-HAL: startHal
08-16 17:58:30.430  1015  1125 D WifiP2pService: P2pEnabledState
08-16 17:58:30.430  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9daa19bc
,08-16 17:58:30.430  1015  1149 I WifiNative-HAL: Could not start hal
08-16 17:58:30.430  1015  1149 E WifiScanningService: could not start HAL
08-16 17:58:30.430  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-16 17:58:30.430  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:30.430  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-16 17:58:30.430  6450  6450 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-16 17:58:30.430  6450  6450 D SecurityLogAgent: StateMachine : Current State = 1
08-16 17:58:30.430  6450  6450 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-16 17:58:30.430  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:30.430  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,08-16 17:58:30.430  1015  1126 E WifiNative-wlan0: invaild command id : 215
08-16 17:58:30.430  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-16 17:58:30.430  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED,
08-16 17:58:30.430  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:30.430  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-16 17:58:30.430  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:30.430  1015  1045 D WifiDisplayController: disconnect
08-16 17:58:30.430  1015  1045 D WifiDisplayController: updateConnection
08-16 17:58:30.430  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-16 17:58:30.440  6974  6974 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:58:30.440  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-16 17:58:30.440  6974  6974 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-16 17:58:30.440  6974  6974 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-16 17:58:30.440  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-16 17:58:30.440  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-16 17:58:30.440  1015  1126 E WifiNative-wlan0: invaild command id : 215
,08-16 17:58:30.440  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:30.440  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:30.450  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-16 17:58:30.450  1015  1353 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-16 17:58:30.450  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-16 17:58:30.450  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-16 17:58:30.450  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-16 17:58:30.450  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 17:58:30.450  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-16 17:58:30.450  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-16 17:58:30.450  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-16 17:58:30.450  1015  1125 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-16 17:58:30.450  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  secondary type: null
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  wps: 0
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  grpcapab: 0
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  devcapab: 0
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  status: 3
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  wfdInfo: null
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  groupownerAddress: null,
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  GOdeviceName: null
,08-16 17:58:30.450  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-16 17:58:30.450  1015  1045 D WifiDisplayController:  SConnectInfo : null
,08-16 17:58:30.460  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:30.460  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:30.460  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-16 17:58:30.460  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:30.460  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:30.460  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-16 17:58:30.460  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:58:30.460  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:30.460  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:30.470  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:30.470  6417  6417 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-16 17:58:30.470  6417  6417 D FileShare-Client: Outbound.stopDelayTimer - 
,08-16 17:58:30.480  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-16 17:58:30.480  6432  6432 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-16 17:58:30.480  1015  1125 D WifiP2pService: InactiveState
,08-16 17:58:30.480  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-16 17:58:30.480  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:30.480  6974  6974 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-16 17:58:30.490  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-16 17:58:30.490  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-16 17:58:30.770  1015  3201 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-16 17:58:30.770  1015  3201 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4178, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-16 17:58:30.770  1015  3201 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-16 17:58:30.770  1015  3201 D BatteryService: stay LED for charging
08-16 17:58:30.770  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-16 17:58:30.770  1015  1015 I MotionRecognitionService: Plugged
,08-16 17:58:30.770  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-16 17:58:30.780  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-16 17:58:30.780  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-16 17:58:30.780  1417  1417 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-16 17:58:30.780  1417  1417 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-16 17:58:30.800  6883  6883 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-16 17:58:30.800  6883  6913 D HeadsetStateMachine: Disconnected process message: 10
,08-16 17:58:30.810  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:30.810  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:30.810  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:30.920  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:30.930  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:30.930  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:58:30.930  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:58:30.940  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1650fb57 Bundle[{}]
,08-16 17:58:30.940  6176  6229 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:58:30.940  6176  6229 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 17:58:30.940  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:58:30.940  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:58:30.940  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 17:58:30.940  6176  6229 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:58:30.950  6176  6229 I System.out: Running OutgoingSocketThread
,08-16 17:58:30.950  6176  6983 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1163)
,08-16 17:58:30.960  6176  6983 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48603
08-16 17:58:30.960  6176  6983 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:58:31.640  6974  6974 I wpa_supplicant: nl80211: Received scan results (31 BSSes),
,08-16 17:58:31.640  6974  6974 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-16 17:58:31.650  1015  6980 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
08-16 17:58:31.650  6974  6974 I wpa_supplicant: Trying to associate with SSID '4E47373030',
,08-16 17:58:31.650  6974  6974 I wpa_supplicant: Trying to associate with  'G700'
,08-16 17:58:31.650  6974  6974 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-16 17:58:31.650  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
,08-16 17:58:31.670  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:31.670  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:31.760  6974  6974 E wpa_supplicant: Cmd 35605 not handled
,08-16 17:58:31.760  6974  6974 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.760  6974  6974 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-16 17:58:31.760  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.760  6974  6974 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-16 17:58:31.760  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-16 17:58:31.760  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.760  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-16 17:58:31.760  6974  6974 I wpa_supplicant: Associated with F4.99.3E
08-16 17:58:31.760  6974  6974 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.760  6974  6974 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-16 17:58:31.760  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:58:31.770  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-16 17:58:31.770  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-16 17:58:31.770  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:31.770  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-16 17:58:31.770  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-16 17:58:31.770  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-16 17:58:31.770  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-16 17:58:31.770  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-16 17:58:31.770  1015  1042 D Tethering: interfaceStatusChanged wlan0, true,
08-16 17:58:31.770  6974  6974 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-16 17:58:31.770  6974  6974 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-16 17:58:31.780  6974  6974 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-16 17:58:31.780  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-16 17:58:31.780  1015  1129 E Tethering: No numeric data
,08-16 17:58:31.780  6974  6974 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:58:31.780  6974  6974 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-16 17:58:31.780  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 17:58:31.780  1015  1129 D Tethering: clearTetheredNotification()
,08-16 17:58:31.780  6974  6974 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-16 17:58:31.780  6974  6974 I wpa_supplicant: Blacklist: Clear (temp) 
08-16 17:58:31.780  6974  6974 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-16 17:58:31.780  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true,
08-16 17:58:31.780  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-16 17:58:31.780  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-16 17:58:31.780  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:31.780  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:31.790  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-16 17:58:31.790  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.790  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-16 17:58:31.790  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated,
08-16 17:58:31.790  1174  1174 D HotspotTile: updateTetherState():false, false
08-16 17:58:31.790  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:31.790  1015  1123 V NetworkStats: performPollLocked() took 6ms
08-16 17:58:31.790  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.800  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 17:58:31.800  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:31.800  1015  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-16 17:58:31.800  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-16 17:58:31.810  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-16 17:58:31.810  1015  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-16 17:58:31.810  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:31.810  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:31.810  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.810  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.810  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.810  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:31.820  1015  1384 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:31.810  1015  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-16 17:58:31.820  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:31.810  1015  1128 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:31.810  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:31.820  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:31.820  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:31.820  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:31.820  3588  3588 I Hs20UtilService: Starting #19
,08-16 17:58:31.820  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:31.830  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:31.830  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-16 17:58:31.830  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:58:31.830  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-16 17:58:31.830  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-16 17:58:31.830  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-16 17:58:31.830  1324  1324 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-16 17:58:31.830  1324  3051 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-16 17:58:31.840   278   995 D CommandListener: Setting iface cfg
,08-16 17:58:31.840  1015  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:58:31.850  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-16 17:58:31.850  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:31.850  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:31.850  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:31.860  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:31.860  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:31.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.860  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:31.870  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-16 17:58:31.870  1015  1126 D SecContentProvider2: mCursor = null
,08-16 17:58:31.870  1015  1126 E WifiNative-wlan0: do suspend false
,08-16 17:58:31.870  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:58:31.870  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:31.950  6176  6229 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1164)
,08-16 17:58:31.950  6176  6229 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1164)
,08-16 17:58:31.950  6176  6229 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1169)
,08-16 17:58:31.960  6176  6229 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 17:58:31.960  6176  6229 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1170)
,08-16 17:58:31.960  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:31.960  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34afb0d3 added. We now have 2 listener(s)
,08-16 17:58:31.970  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:58:31.970  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:31.970  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:31.970  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:31.970  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce0c410 added. We now have 9 listener(s)
08-16 17:58:31.970  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:31.970  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:31.970  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:31.980  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:31.980  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 17:58:31.980  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:31.980  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:58:31.980  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:31.980  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.980  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e210e added. We now have 3 listener(s)
,08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dba872f added. We now have 10 listener(s)
08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:31.990  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:31.990  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:31.990  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:31.990  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34afb0d3 removed from the list
,08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce0c410 removed from the list
,08-16 17:58:31.990  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:31.990  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:31.990  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ce0c410 not in the list
08-16 17:58:31.990  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dba872f removed from the list
,08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:31.990  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:31.990  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:31.990  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41e210e removed from the list
,08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:31.990  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af6113c added. We now have 2 listener(s)
,08-16 17:58:32.000  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:58:32.000  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-16 17:58:32.000  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.000  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.000  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146dcec5 added. We now have 9 listener(s)
,08-16 17:58:32.000  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.000  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:32.000  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.010  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:32.010  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:58:32.010  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:58:32.010  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.020  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.020  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f2674b added. We now have 3 listener(s)
,08-16 17:58:32.020  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.020  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:58:32.020  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:32.020  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:32.020  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:32.020  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32b10528 added. We now have 10 listener(s)
,08-16 17:58:32.020  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:32.020  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:58:32.020  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:58:32.020  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:58:32.020  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:32.030  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:32.030  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:32.030  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:32.040  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:32.040  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:32.040  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:58:32.040  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:32.040  6883  6949 D BtGatt.GattService: registerClient() - UUID=a5f25189-8a5d-49aa-a0ff-b57bd296b287
,08-16 17:58:32.090  6883  6908 D BtGatt.GattService: onClientRegistered() - UUID=a5f25189-8a5d-49aa-a0ff-b57bd296b287, clientIf=6,
,08-16 17:58:32.090  6176  6184 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-16 17:58:32.090  6883  6955 D BtGatt.GattService: start scan with filters
,08-16 17:58:32.090  6883  6912 D BtGatt.ScanManager: handling starting scan
08-16 17:58:32.090  6989  6989 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-16 17:58:32.090  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:32.090  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:58:32.090  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:32.090  6883  6912 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5ff0bd
,08-16 17:58:32.100  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:58:32.100  6883  6908 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:32.100  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.100  6883  6912 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:32.100  6883  6912 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-16 17:58:32.100  6989  6989 I dhcpcd  : version 5.5.6 starting,
08-16 17:58:32.100  6883  6912 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-16 17:58:32.100  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-16 17:58:32.100  6989  6989 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-16 17:58:32.100  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-16 17:58:32.110  6883  6912 D BtGatt.ScanManager: Starting BLE batch scan,
08-16 17:58:32.110  6883  6912 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:58:32.110  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.110  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:32.110  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:32.110  6883  6908 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-16 17:58:32.110  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.130  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-16 17:58:32.130  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.130  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:58:32.140  6176  6229 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation,
08-16 17:58:32.140  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.140  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:58:32.140  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.140  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-16 17:58:32.140  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:58:32.140  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:32.140  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:58:32.140  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:32.140  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:32.140  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:32.140  6883  6892 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:32.140  6883  6891 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:32.150  6883  6912 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 27
,08-16 17:58:32.150  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-16 17:58:32.150  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:32.150  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:32.150  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:32.150  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:32.150  6883  6912 D BtGatt.ScanManager: filter size is 1
,08-16 17:58:32.150  6883  6912 D BtGatt.ScanManager: delete FilterIndex - 3
,08-16 17:58:32.160  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.160  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:32.160  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:32.160  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:58:32.160  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-16 17:58:32.160  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.160  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.160  6883  6912 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:32.160  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:32.170  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:58:32.170  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.170  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-16 17:58:32.170  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.170  6883  6912 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
,08-16 17:58:32.170  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:32.170  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.170  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:58:32.170  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.170  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.170  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 17:58:32.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2af6113c removed from the list
08-16 17:58:32.170  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.170  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146dcec5 removed from the list
08-16 17:58:32.170  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.170  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.170  6883  6908 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:32.170  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.180  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.180  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.180  6989  6989 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-16 17:58:32.180  6989  6989 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-16 17:58:32.180  6989  6989 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-16 17:58:32.180  6989  6989 I dhcpcd  : bssid match
08-16 17:58:32.180  6989  6989 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.180  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@146dcec5 not in the list
08-16 17:58:32.180  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.180  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.180  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32b10528 removed from the list
08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.180  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.180  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.180  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.180  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25f2674b removed from the list
,08-16 17:58:32.180  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:32.180  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a54bd4 added. We now have 2 listener(s)
,08-16 17:58:32.180  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:58:32.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:32.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:58:32.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.190  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2174117d added. We now have 9 listener(s)
08-16 17:58:32.190  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:32.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:32.190  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.200  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:32.200  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:32.200  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:32.200  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.200  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a1674c3 added. We now have 3 listener(s)
,08-16 17:58:32.200  1015  2722 D SSRM:n  : SIOP:: AP = 330
,08-16 17:58:32.200  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:58:32.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.200  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.200  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f55140 added. We now have 10 listener(s)
08-16 17:58:32.200  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.200  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.200  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.200  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:32.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:32.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:32.200  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:32.210  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.210  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:58:32.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:32.210  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:32.220  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:58:32.220  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:32.220  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:58:32.220  6883  6914 D BtGatt.GattService: registerClient() - UUID=c78cb662-fb7e-472c-b18e-00ae8373546d
,08-16 17:58:32.260  6989  6989 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
08-16 17:58:32.260  6883  6908 D BtGatt.GattService: onClientRegistered() - UUID=c78cb662-fb7e-472c-b18e-00ae8373546d, clientIf=6
08-16 17:58:32.260  6176  6184 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:58:32.260  6883  6892 D BtGatt.GattService: start scan with filters
08-16 17:58:32.260  6883  6912 D BtGatt.ScanManager: handling starting scan
08-16 17:58:32.270  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:32.270  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:32.270  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:32.270  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:32.270  6883  6908 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:32.270  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.270  6883  6912 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:32.270  6883  6912 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:32.270  6883  6912 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-16 17:58:32.270  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:58:32.270  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.270  6883  6912 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:32.270  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.270  6883  6912 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-16 17:58:32.270  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:32.270  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:58:32.270  6883  6908 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-16 17:58:32.270  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.280  6989  6989 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
08-16 17:58:32.280  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:58:32.280  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:58:32.280  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.290  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:58:32.290  6176  6229 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-16 17:58:32.290  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:32.290  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.290  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:32.290  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.290  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.290  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:32.290  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.290  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14a54bd4 removed from the list
08-16 17:58:32.290  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.290  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2174117d removed from the list
08-16 17:58:32.290  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.290  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:32.290  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.290  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
08-16 17:58:32.290  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.290  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.300  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2174117d not in the list
08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:58:32.300  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:32.300  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:32.300  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:58:32.300  6883  6955 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:32.310  6883  6914 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:32.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:32.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:58:32.310  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
,08-16 17:58:32.310  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
,08-16 17:58:32.310  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-16 17:58:32.320  6883  6912 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
08-16 17:58:32.320  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.320  6883  6912 D BtGatt.ScanManager: filter size is 1
08-16 17:58:32.320  6883  6912 D BtGatt.ScanManager: delete FilterIndex - 4
08-16 17:58:32.320  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:58:32.320  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-16 17:58:32.320  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:32.320  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:32.320  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.320  6883  6912 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:32.320  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,08-16 17:58:32.320  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:58:32.330  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.330  6883  6912 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-16 17:58:32.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.330  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:32.330  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:32.330  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.330  6883  6908 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:32.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.330  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.330  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14f55140 removed from the list
08-16 17:58:32.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.330  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.330  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.330  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.330  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a1674c3 removed from the list
08-16 17:58:32.330  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.330  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@157e416c added. We now have 2 listener(s)
,08-16 17:58:32.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-16 17:58:32.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.340  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.340  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2438f335 added. We now have 9 listener(s)
08-16 17:58:32.340  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:58:32.340  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:58:32.350  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.350  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:58:32.360  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:32.360  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:32.360  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.360  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30fb93b added. We now have 3 listener(s)
,08-16 17:58:32.360  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:58:32.360  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.360  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:58:32.360  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.360  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.360  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.360  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16c40858 added. We now have 10 listener(s)
08-16 17:58:32.360  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.360  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.360  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:58:32.360  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:58:32.360  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:58:32.360  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:58:32.370  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-16 17:58:32.370  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:58:32.380  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:58:32.390  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-16 17:58:32.390  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:58:32.390  6176  6229 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:58:32.390  6883  6892 D BtGatt.GattService: registerClient() - UUID=21c81b5c-047d-48da-aad4-181907f1b865
,08-16 17:58:32.440  6883  6908 D BtGatt.GattService: onClientRegistered() - UUID=21c81b5c-047d-48da-aad4-181907f1b865, clientIf=6
,08-16 17:58:32.440  6176  6191 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-16 17:58:32.440  6883  6891 D BtGatt.GattService: start scan with filters
,08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: handling starting scan
08-16 17:58:32.440  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:58:32.440  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:58:32.440  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:58:32.440  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:58:32.440  6883  6908 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-16 17:58:32.440  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: allow scan with filters
08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-16 17:58:32.440  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-16 17:58:32.440  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:58:32.440  6883  6912 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-16 17:58:32.450  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:32.450  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:58:32.450  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:58:32.450  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-16 17:58:32.450  6883  6908 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-16 17:58:32.450  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.460  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-16 17:58:32.460  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.460  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,08-16 17:58:32.460  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.460  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:32.460  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.460  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.460  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:58:32.460  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.460  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@157e416c removed from the list
08-16 17:58:32.460  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.460  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2438f335 removed from the list
08-16 17:58:32.460  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.460  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.460  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.460  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-16 17:58:32.460  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.460  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.470  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2438f335 not in the list
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:58:32.470  6883  6955 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:58:32.470  6883  6914 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:58:32.470  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:58:32.470  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:58:32.480  6883  6912 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,08-16 17:58:32.480  6883  6912 D BtGatt.ScanManager: filter size is 1
,08-16 17:58:32.480  6883  6912 D BtGatt.ScanManager: delete FilterIndex - 5
,08-16 17:58:32.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
,08-16 17:58:32.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:58:32.480  6883  6908 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-16 17:58:32.480  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.480  6883  6912 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 17:58:32.480  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16c40858 removed from the list,
08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:58:32.480  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.480  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.480  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.480  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30fb93b removed from the list
08-16 17:58:32.480  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:58:32.480  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9d5204 added. We now have 2 listener(s),
,08-16 17:58:32.480  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 17:58:32.480  6176  6176 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:58:32.480  6176  6176 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:58:32.480  6883  6908 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-16 17:58:32.480  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-16 17:58:32.480  6883  6912 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-16 17:58:32.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-16 17:58:32.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:58:32.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.490  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:58:32.490  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@241153ed added. We now have 9 listener(s)
,08-16 17:58:32.490  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:58:32.490  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:58:32.490  6883  6908 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-16 17:58:32.490  6883  6908 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-16 17:58:32.500  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:58:32.510  6176  6229 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:58:32.510  6176  6229 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:58:32.510  6176  6229 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:58:32.510  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:58:32.510  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e14b3 added. We now have 3 listener(s)
,08-16 17:58:32.510  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.510  6176  6176 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
,08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:58:32.520  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:58:32.520  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9f8a70 added. We now have 10 listener(s)
,08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
08-16 17:58:32.520  6176  6229 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:58:32.520  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:58:32.520  6176  6229 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.520  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:58:32.520  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9d5204 removed from the list
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.520  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@241153ed removed from the list
08-16 17:58:32.520  6176  6229 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.520  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:58:32.520  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:58:32.520  6176  6229 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@241153ed not in the list
08-16 17:58:32.520  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:58:32.520  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-16 17:58:32.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:58:32.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:58:32.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:58:32.530  6176  6229 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b9f8a70 removed from the list
,08-16 17:58:32.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:58:32.530  6176  6229 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:58:32.530  6176  6229 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-16 17:58:32.530  6176  6229 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-16 17:58:32.530  6176  6229 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e14b3 removed from the list
,08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:58:32.530  6176  6229 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:58:32.530  6176  7021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1177, name: My test thread name)
,08-16 17:58:32.540  6176  7021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1177, thread name: My test thread name)
08-16 17:58:32.540  6176  7021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1177, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:58:32.540  6176  7022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1179, name: My test thread name)
,08-16 17:58:32.540  6176  7022 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1179, thread name: My test thread name)
08-16 17:58:32.540  6176  7022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1179, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-16 17:58:32.540  6176  6229 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
08-16 17:58:32.540  6176  6229 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-16 17:58:32.540  6176  6229 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-16 17:58:32.540  6176  6229 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-16 17:58:32.540  6176  6229 D com.test.thalitest.ThaliTestRunner: Total duration: 23372 ms,
08-16 17:58:32.540  6176  6229 I jxcore-log: Total number of executed tests:  80
08-16 17:58:32.540  6176  6229 I jxcore-log: 
,08-16 17:58:32.540  6176  6229 I jxcore-log: Number of passed tests:  80
08-16 17:58:32.540  6176  6229 I jxcore-log: 
08-16 17:58:32.540  6176  6229 I jxcore-log: Number of failed tests:  0
08-16 17:58:32.540  6176  6229 I jxcore-log: 
,08-16 17:58:32.540  6176  6229 I jxcore-log: Number of ignored tests:  0
08-16 17:58:32.540  6176  6229 I jxcore-log: 
,08-16 17:58:32.540  6176  6229 I jxcore-log: Total duration:  23372
08-16 17:58:32.540  6176  6229 I jxcore-log: 
,08-16 17:58:32.540  6176  6229 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:58:32.540  6176  6229 I jxcore-log: 
,08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.550  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.550  6176  6229 I jxcore-log: 
08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
08-16 17:58:32.560  6176  6176 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.560  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.560  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
,08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: ,
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.570  6176  6229 I jxcore-log: 
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: ,
08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.570  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:58:32.570  6176  6229 I jxcore-log: 
,08-16 17:58:32.670  6176  6176 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:58:32.670  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.670  6176  6229 I jxcore-log: 
,08-16 17:58:32.690  1015  1126 E WifiNative-wlan0: do suspend true
,08-16 17:58:32.710  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-16 17:58:32.720  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-16 17:58:32.720  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-16 17:58:32.720  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-16 17:58:32.720  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.720  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.720  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-16 17:58:32.720  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.720  1015  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-16 17:58:32.720  1015  1126 E WifiStateMachine: VerifyingLinkState enter
,08-16 17:58:32.730  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [210],
,08-16 17:58:32.730  1015  1128 E ConnectivityService: updateNetworkInfo()
,08-16 17:58:32.730  1015  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-16 17:58:32.730  1015  1128 D ConnectivityService: Adding iface wlan0 to network 503,
,08-16 17:58:32.740  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-16 17:58:32.740  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:32.740  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:32.740  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:58:32.740  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-16 17:58:32.750  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.750  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:32.750  1015  1542 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:32.750  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.750  1015  1542 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-16 17:58:32.750  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.750  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.750  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.750  1015  1542 W ActivityManager: userId = 0, bbcId = -10000
,08-16 17:58:32.750  1015  1542 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.750  1015  1542 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:32.750  1015  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-16 17:58:32.750  3588  3588 I Hs20UtilService: Starting #20
08-16 17:58:32.750  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:32.750  1324  1324 I NearbySettings: MountReceiver.onReceive - Keep current state
08-16 17:58:32.750  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:32.770  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-16 17:58:32.770  1015  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,08-16 17:58:32.770  1015  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
08-16 17:58:32.770  1015  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
08-16 17:58:32.780  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.780  1015  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:58:32.780  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-16 17:58:32.780  1015  1128 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-16 17:58:32.780  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.780  1015  1128 D ConnectivityService: LTETest block dns file not exists
08-16 17:58:32.780  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.780  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.780  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.780  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:58:32.780  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 17:58:32.780  1015  3201 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:32.780  1015  3201 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:32.780  1015  3201 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:32.780  1015  3201 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.780  1015  3201 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-16 17:58:32.780  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:32.780  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:32.780  1015  1128 E ConnectivityService: updateNetworkInfo()
08-16 17:58:32.780  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 17:58:32.780  1015  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:32.780  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
,08-16 17:58:32.780  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 17:58:32.780  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-16 17:58:32.780  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 17:58:32.780  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-16 17:58:32.780  1015  6986 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-16 17:58:32.780   278   991 D EnterpriseController: uids 1000
,08-16 17:58:32.780   278   991 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-16 17:58:32.780   278   991 D Netd    : getNetworkForDns: using netid 503 for uid 1000
08-16 17:58:32.790  3588  3588 I Hs20UtilService: Starting #21
08-16 17:58:32.790  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-16 17:58:32.790  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-16 17:58:32.790  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
08-16 17:58:32.790  3588  3624 I Hs20UtilService: Message received 5007
08-16 17:58:32.790  1015  1128 D ConnectivityService:    accepting network in place of null
,08-16 17:58:32.790  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-16 17:58:32.790  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-16 17:58:32.790  1457  1457 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-16 17:58:32.790  1457  1457 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-16 17:58:32.790  1015  1015 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-16 17:58:32.790  1015  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 17:58:32.790  1015  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-16 17:58:32.790  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-16 17:58:32.800  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-16 17:58:32.800  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-16 17:58:32.800  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.800  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.800  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.800  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.810  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-16 17:58:32.810  1324  1324 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-16 17:58:32.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-16 17:58:32.810  1015  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-16 17:58:32.810  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-16 17:58:32.810  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:58:32.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-16 17:58:32.810  1324  1324 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-16 17:58:32.810  1324  1324 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:58:32.810  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503],
,08-16 17:58:32.820  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-16 17:58:32.820  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:32.820  1015  1123 V NetworkStats: updateIfacesLocked()
08-16 17:58:32.820  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-16 17:58:32.820  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-16 17:58:32.820  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.820  1015  1123 V NetworkStats: performPollLocked() took 3ms
08-16 17:58:32.820  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-16 17:58:32.820  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-16 17:58:32.820  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.820  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.820  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.820  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.820  1174  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:58:32.820  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
08-16 17:58:32.820  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:32.820  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:58:32.820  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-16 17:58:32.820  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:58:32.820  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-16 17:58:32.830  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:58:32.830  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.830  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:32.830  6176  6176 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-16 17:58:32.830  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.830  6176  6229 I jxcore-log: 
,08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:32.830  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:32.830  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:32.840  1015  1384 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-16 17:58:32.840  1015  1384 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-16 17:58:32.840  1015  1384 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:32.840  1015  1384 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:32.840  1015  1384 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-16 17:58:32.850  1324  1324 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-16 17:58:32.850  3588  3588 I Hs20UtilService: Starting #22
08-16 17:58:32.850  1324  1324 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-16 17:58:32.850  3588  3624 I Hs20UtilService: Message received 5007
,08-16 17:58:32.850  1015  1250 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-16 17:58:32.850  1015  1542 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-16 17:58:32.850  1015  1542 D SecContentProvider2: mCursor = null
,08-16 17:58:32.850  1015  1543 D SecContentProvider2: uri = 15 selection = getToastGravity
08-16 17:58:32.850  1015  1543 D SecContentProvider2: mCursor = null
,08-16 17:58:32.860  1015  3089 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-16 17:58:32.860  1015  3089 D SecContentProvider2: mCursor = null
,08-16 17:58:32.860  1015  3202 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset,
08-16 17:58:32.860  1015  3202 D SecContentProvider2: mCursor = null
,08-16 17:58:32.860  7023  7023 D AndroidRuntime: ,
,08-16 17:58:32.860  7023  7023 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 17:58:32.860  1015  1354 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-16 17:58:32.860  1015  1354 D SecContentProvider2: mCursor = null
,08-16 17:58:32.860  1015  1384 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-16 17:58:32.860  1015  1384 D SecContentProvider2: mCursor = null
,08-16 17:58:32.860  7023  7023 D AndroidRuntime: CheckJNI is OFF
08-16 17:58:32.860  7023  7023 D AndroidRuntime: readGMSProperty: start
08-16 17:58:32.860  7023  7023 D AndroidRuntime: readGMSProperty: already setted!!
,08-16 17:58:32.860  7023  7023 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-16 17:58:32.860  7023  7023 D AndroidRuntime: readGMSProperty: could not set the property(default)!!,
08-16 17:58:32.860  7023  7023 D AndroidRuntime: readGMSProperty: end
08-16 17:58:32.860  7023  7023 D AndroidRuntime: addProductProperty: start,
,08-16 17:58:32.870  1015  6986 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-16 17:58:32.890   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,08-16 17:58:32.900  1015  1544 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-16 17:58:32.900  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:58:32.930  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:58:32 GMT], X-Android-Received-Millis=[1471363112945], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471363112915]}
,08-16 17:58:32.930  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 17:58:32.930  1015  6986 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-16 17:58:32.940  1015  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-16 17:58:32.940  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-16 17:58:32.940  1015  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.,
08-16 17:58:32.940  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:32.940  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 17:58:32.940  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 17:58:32.940  1174  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-16 17:58:32.980  6176  6176 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:58:32.980  6176  6229 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:58:32.980  6176  6229 I jxcore-log: 
,08-16 17:58:33.030  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,08-16 17:58:33.030  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-16 17:58:33.030  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-16 17:58:33.030  1174  1174 D StatusBar.NetworkController: updateDataNetType()
08-16 17:58:33.030  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-16 17:58:33.030  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-16 17:58:33.030  7023  7023 E AffinityControl: AffinityControl: registerfunction enter
,08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-16 17:58:33.040  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-16 17:58:33.040  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-16 17:58:33.060  7023  7023 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:58:33.080  1015  3201 D PackageManager: START PACKAGE DELETE: observer{676201226},
08-16 17:58:33.080  1015  3201 D PackageManager: pkg{<packageName>}
08-16 17:58:33.080  1015  3201 D PackageManager: user{0}
08-16 17:58:33.080  1015  3201 D PackageManager: caller{2000}
08-16 17:58:33.080  1015  3201 D PackageManager: flags{2}
,08-16 17:58:33.080  1015  3201 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-16 17:58:33.080  1015  3201 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-16 17:58:33.080  1015  3201 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-16 17:58:33.080  1015  3201 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-16 17:58:33.080  1015  3201 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-16 17:58:33.080  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-16 17:58:33.080  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-16 17:58:33.080  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-16 17:58:33.080  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-16 17:58:33.080  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-16 17:58:33.080  1015  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-16 17:58:33.090  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-16 17:58:33.090  1015  1040 I ActivityManager: Killing 6176:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-16 17:58:33.090  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{f90b7cb u0 com.test.thalitest/.MainActivity t128}
,08-16 17:58:33.100  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-16 17:58:33.210   258  1100 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,08-16 17:58:33.210  1015  3089 I WindowState: WIN DEATH: Window{9edf7ab u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 17:58:33.210   258  1100 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,08-16 17:58:33.220  1015  3089 D InputDispatcher: Focus left window: 6176
,08-16 17:58:33.230  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
08-16 17:58:33.230  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101,
,08-16 17:58:33.250  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-16 17:58:33.250  1015  1055 I ActivityManager:   Force finishing activity ActivityRecord{f90b7cb u0 com.test.thalitest/.MainActivity t128 f}
,08-16 17:58:33.250  1015  1055 W ActivityManager: Duplicate finish request for ActivityRecord{f90b7cb u0 com.test.thalitest/.MainActivity t128 f}
,08-16 17:58:33.260  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-16 17:58:33.280  3126  3126 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-16 17:58:33.290  1015  1040 D InputDispatcher: Focused application released
,08-16 17:58:33.290  5652  5652 I art     : Explicit concurrent mark sweep GC freed 15821(920KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 6MB/11MB, paused 771us total 37.273ms
,08-16 17:58:33.300  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 17:58:33.310  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 17:58:33.310  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:58:33.320  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:58:33.320  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 17:58:33.320  3126  3126 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 3
,08-16 17:58:33.330  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-16 17:58:33.330  1779  1779 E SamsungIME: mOCRHelper is null
08-16 17:58:33.330  3789  3789 I art     : Explicit concurrent mark sweep GC freed 23238(1406KB) AllocSpace objects, 3(48KB) LOS objects, 39% free, 15MB/26MB, paused 1.572ms total 79.167ms
,08-16 17:58:33.350   288   288 E SMD     : DCD OFF
,08-16 17:58:33.370  1015  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
,08-16 17:58:33.370  1015  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-16 17:58:33.370  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.370  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-16 17:58:33.370  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-16 17:58:33.380  1015  1123 V NetworkStats: performPollLocked() took 11ms
,08-16 17:58:33.380  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.380  3126  3126 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-16 17:58:33.390  3126  3126 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-16 17:58:33.390  3625  3625 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 16 17:58:33 GMT+02:00 2016
,08-16 17:58:33.410  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.430  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-16 17:58:33.430  1447  1447 D RegisteredServicesCache: empty dynamic service
,08-16 17:58:33.440  6498  6498 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 17:58:33.450  1015  1354 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-16 17:58:33.450  1015  1354 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-16 17:58:33.460  1447  1447 D RegisteredComponentCache: Collect Tech packages for Knox
,08-16 17:58:33.460  1447  1447 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.460  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 3
,08-16 17:58:33.470  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-16 17:58:33.480  3126  3126 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-16 17:58:33.480  1015  1015 I art     : Explicit concurrent mark sweep GC freed 87547(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 28MB/42MB, paused 5.727ms total 218.219ms
,08-16 17:58:33.480  1015  1055 I art     : WaitForGcToComplete blocked for 194.316ms for cause Explicit
,08-16 17:58:33.490  3126  3126 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-16 17:58:33.490  3126  3126 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,08-16 17:58:33.490  3126  3126 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,08-16 17:58:33.510  1015  1542 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-16 17:58:33.510  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-16 17:58:33.510  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-16 17:58:33.510  1015  1542 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-16 17:58:33.510  1015  1542 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-16 17:58:33.510  3126  3126 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,08-16 17:58:33.600  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-16 17:58:33.600  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-16 17:58:33.600  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.600  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-16 17:58:33.600  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-16 17:58:33.600  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-16 17:58:33.610  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-16 17:58:33.610  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-16 17:58:33.610  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-16 17:58:33.610  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-16 17:58:33.610  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:58:33.610  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-16 17:58:33.610  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-16 17:58:33.610  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:58:33.610  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:58:33.620  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: uID is 10155
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-16 17:58:33.620  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-16 17:58:33.620  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
08-16 17:58:33.620  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-16 17:58:33.620  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-16 17:58:33.620  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-16 17:58:33.630  1015  2722 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-16 17:58:33.630  1015  1161 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-16 17:58:33.630  1015  1161 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,08-16 17:58:33.670  1015  1055 I art     : Explicit concurrent mark sweep GC freed 16925(1263KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 3.225ms total 182.846ms
,08-16 17:58:33.670  1015  1384 I art     : WaitForGcToComplete blocked for 329.059ms for cause Explicit
,08-16 17:58:33.690  1015  1055 D PackageManager: delete codoeFile: 
,08-16 17:58:33.700  1174  1174 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-16 17:58:33.700  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-16 17:58:33.700  1015  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-16 17:58:33.700  1015  1055 D PackageManager: result of delete: 1{676201226}
,08-16 17:58:33.710  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
08-16 17:58:33.710  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.710  1174  1174 D PanelView: There is/are notification(s) 
08-16 17:58:33.710  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 17:58:33.710  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,08-16 17:58:33.710  1174  1174 D PanelView: There is/are notification(s) 
08-16 17:58:33.710  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-16 17:58:33.710  7023  7023 D AndroidRuntime: Shutting down VM
,08-16 17:58:33.780  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-16 17:58:33.820  1015  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-16 17:58:33.820  1015  1384 I art     : Explicit concurrent mark sweep GC freed 6174(322KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 2.579ms total 154.088ms
,08-16 17:58:33.820  1015  1543 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-16 17:58:33.820  1015  1543 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.820  1015  1250 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 17:58:33.820  1015  1250 D SecContentProvider2: mCursor = null
,08-16 17:58:33.820   258   258 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,08-16 17:58:33.820  1935  2110 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:58:33.820  1015  1543 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:33.820  1015  1543 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:33.820  1015  1543 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-16 17:58:33.830  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-16 17:58:33.830  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-16 17:58:33.830  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-16 17:58:33.830  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-16 17:58:33.830  1015  3204 D InputDispatcher: Focus entered window: 3126
,08-16 17:58:33.830  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-16 17:58:33.830  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-16 17:58:33.830  3126  3126 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-16 17:58:33.840  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.840  3625  3625 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-16 17:58:33.840  1015  1384 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-16 17:58:33.840  1015  1384 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-16 17:58:33.840  1015  1384 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-16 17:58:33.840  3126  3126 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-16 17:58:33.840  3625  3625 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-16 17:58:33.840  3126  3126 V ActivityThread: updateVisibility : ActivityRecord{2c5351bb token=android.os.BinderProxy@39bf8b6e {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-16 17:58:33.850  3625  3625 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-16 17:58:33.850  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.850  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.850  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.850  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.850  3625  3625 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-16 17:58:33.850  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.860  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-16 17:58:33.860  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.860  1015  1028 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-16 17:58:33.860  7042  7042 E Zygote  : MountEmulatedStorage()
,08-16 17:58:33.860  7042  7042 I libpersona: KNOX_SDCARD checking this for 10094
08-16 17:58:33.860  7042  7042 E Zygote  : v2
08-16 17:58:33.860  7042  7042 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.870  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
08-16 17:58:33.870  7042  7042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:33.870  1015  1384 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7042 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-16 17:58:33.870  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START,
08-16 17:58:33.870  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-16 17:58:33.870  1015  1028 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6176 uid 10155
,08-16 17:58:33.870  7042  7042 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:33.870  1174  1174 D PanelView: There is/are notification(s) 
08-16 17:58:33.880  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
08-16 17:58:33.880  7042  7042 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-16 17:58:33.880  1015  7046 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-16 17:58:33.880  1779  1779 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-16 17:58:33.880  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.880  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.880  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.880  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.880  3126  3126 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@39bf8b6e time:149338
,08-16 17:58:33.890  7053  7053 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.890  7053  7053 E Zygote  : v2
08-16 17:58:33.890  7053  7053 I libpersona: KNOX_SDCARD checking this for 10044
08-16 17:58:33.890  7053  7053 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:33.900  7053  7053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:33.900  1015  1040 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7053 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-16 17:58:33.900  7053  7053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:33.900  7053  7053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.910  1015  1045 W ActivityManager: mDVFSHelper.release()
,08-16 17:58:33.910  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2dddad13 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149366
,08-16 17:58:33.920  7023  7023 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
08-16 17:58:33.920  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-16 17:58:33.920  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.920  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.920  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:33.920  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:33.940  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-16 17:58:33.940  7073  7073 E Zygote  : MountEmulatedStorage()
08-16 17:58:33.940  7073  7073 I libpersona: KNOX_SDCARD checking this for 10149
08-16 17:58:33.940  7073  7073 E Zygote  : v2
08-16 17:58:33.940  7073  7073 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:33.940  7053  7053 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:33.940  7053  7053 D ActivityThread: Added TimaKeyStore provider
08-16 17:58:33.940  7073  7073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:33.940  7073  7073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-16 17:58:33.950  7073  7073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:33.950  7042  7042 D TimaKeyStoreProvider: TimaSignature is unavailable
08-16 17:58:33.950  1015  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7073 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 17:58:33.950  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-16 17:58:33.950  7042  7042 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.960  5738  7070 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
08-16 17:58:33.960  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-16 17:58:33.960  1015  1055 D PackageManager: userId{-1}
08-16 17:58:33.960  1015  1055 D PackageManager: andCode{true}
,08-16 17:58:33.960  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:33.960  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.970  3625  7041 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-16 17:58:33.970  3625  7041 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-16 17:58:33.970  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-16 17:58:33.980  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-16 17:58:33.980  7073  7073 D ActivityThread: Added TimaKeyStore provider
,08-16 17:58:33.980  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:33.990  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-16 17:58:33.990  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:33.990  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-16 17:58:34.000  3625  3625 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-16 17:58:34.010  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:34.010  5738  7070 I art     : Explicit concurrent mark sweep GC freed 693(50KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 663us total 41.695ms
,08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-16 17:58:34.020  7053  7053 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-16 17:58:34.020  1015  1384 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-16 17:58:34.030  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.030  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.030  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.030  1015  1384 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:34.040  7092  7092 E Zygote  : MountEmulatedStorage()
,08-16 17:58:34.040  7092  7092 E Zygote  : v2
08-16 17:58:34.040  7092  7092 I libpersona: KNOX_SDCARD checking this for 1000
08-16 17:58:34.040  7092  7092 I libpersona: KNOX_SDCARD not a persona
,08-16 17:58:34.050  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:34.050  7092  7092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-16 17:58:34.050  1015  1384 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-16 17:58:34.050  7092  7092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-16 17:58:34.050  7092  7092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:34.070  7092  7092 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-16 17:58:34.070  7092  7092 D ActivityThread: Added TimaKeyStore provider
08-16 17:58:34.070  7042  7042 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-16 17:58:34.070  7042  7042 D elm:15183: ELMEngine.ELMEngine( context ).
08-16 17:58:34.080  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:34.080  7042  7042 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-16 17:58:34.080  1015  1250 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-16 17:58:34.080  1015  1250 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-16 17:58:34.090  1478  1478 D Launcher.Model: reloadBadges entered.
,08-16 17:58:34.090  5915  5926 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-16 17:58:34.090  5915  5926 D BadgeProvider: sendNotify, [notify] : null
08-16 17:58:34.090  5915  5926 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-16 17:58:34.090  5915  5926 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-16 17:58:34.090  5915  5926 D BadgeProvider: update, [UpdateCount] : 1
,08-16 17:58:34.090  1015  1250 W ActivityManager: userId = 0, bbcId = -10000
08-16 17:58:34.090  1015  1250 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-16 17:58:34.090  1015  1250 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-16 17:58:34.090  7073  7073 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-16 17:58:34.090  7073  7073 D ThemeInfoUtil: isCurrentFestival = false
,08-16 17:58:34.100  7042  7042 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
08-16 17:58:34.100  1015  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-16 17:58:34.100  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:34.100  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-16 17:58:34.100  1174  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 17:58:34.100  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 17:58:34.100  1174  1700 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 17:58:34.110  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-16 17:58:34.110  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:34.110  3789  6238 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 17:58:34.110  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.110  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.110  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:34.120  7042  7042 D elm:15183: ElmAgentService : onCreate()
,08-16 17:58:34.120  7042  7107 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-16 17:58:34.120  7042  7107 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-16 17:58:34.120  7042  7107 D elm:15183: MDMBridge.getInstance()
,08-16 17:58:34.120  7042  7107 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:58:34.130  7108  7108 E Zygote  : MountEmulatedStorage()
08-16 17:58:34.130  7108  7108 E Zygote  : v2
08-16 17:58:34.130  7108  7108 I libpersona: KNOX_SDCARD checking this for 10152
,08-16 17:58:34.130  7108  7108 I libpersona: KNOX_SDCARD not a persona
08-16 17:58:34.130  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:34.130  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:34.130  7042  7107 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-16 17:58:34.130  1015  1027 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7108 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,08-16 17:58:34.140  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:34.140  1015  1545 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-16 17:58:34.140  1015  1545 D SecContentProvider2: mCursor = null
08-16 17:58:34.140  7108  7108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-16 17:58:34.140  7053  7053 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,08-16 17:58:34.140  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-16 17:58:34.140  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:34.140  7053  7053 E SQLiteDatabase: Failed to open database '/data/data/com.sec.android.gallery3d/databases/picasa.db'.,
,08-16 17:58:34.140  7053  7053 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider$SyncContext.<init>(PicasaContentProvider.java:911)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at com.sec.android.gallery3d.remote.picasa.PicasaContentProvider.attachInfo(PicasaContentProvider.java:103)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181),
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	,at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:34.140  7053  7053 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-16 17:58:34.150  7108  7108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-16 17:58:34.150  7108  7108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-16 17:58:34.150  3357  3357 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-16 17:58:34.160  3357  3357 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 17:58:34.160  3357  3357 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-16 17:58:34.160  3357  3357 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-16 17:58:34.160  3357  3357 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-16 17:58:34.160  3357  3357 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:58:34.160  3357  3357 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 17:58:34.160  3357  3357 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-16 17:58:34.160  3357  3357 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-16 17:58:34.160  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-16 17:58:34.160  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-16 17:58:34.170  6481  6481 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-16 17:58:34.170  6481  6481 I PCWCLIENTTRACE_PushUtil: sales region : global
08-16 17:58:34.170  6481  6481 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-16 17:58:34.170  6481  6481 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-16 17:58:34.170  1015  3200 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-16 17:58:34.170  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.170  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.170  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-16 17:58:34.170  1015  3200 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-16 17:58:34.170  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}

```
